# Meta Ad Creation Standard & Defaults

**Entity / Brand:** [[companies/qalzy|Qalzy]]  
**Maintainer:** [[people/michael-michelis|Michael Michelis]], [[people/kostas-koukoravas|Kostas Koukoravas]]  
**Related Docs:** [[Meta_Ads_MCP_Setup]], [[Ad_Platform_Connectors]]  
**Last Updated:** 2026-09-19  

## Overview

Standard configuration and default operational parameters for programmatically deploying Meta video ads for [[companies/qalzy|Qalzy]] via the Meta Graph API. All new video ad deployments use these defaults unless explicitly overridden.

---

## Default Targeting & Ad Account Settings

- **Default Ad Set:** `TOF_01_[QZ]_MOF_7_VIDEO_KABELIS_V4-7` (ID: `52636253035339`)
- **Ad Account ID:** `act_1351291616909846`
- **Facebook Page ID:** `116692651460204` (Qalzy)
- **Instagram Account ID:** `17841460201437278` (`@qalzy.official`)
- **Ad Status:** Default to draft (`PAUSED`). Never launch as `ACTIVE` without explicit confirmation.
- **Conversion Tracking:**
  - Meta Pixel: `240301502164937`
  - Offsite Conversion ID: `6887916191329822` (Purchase event)
  - Onsite Conversion ID: `25109415652062046`

---

## Creative Standards & Degrees of Freedom (`asset_feed_spec`)

All standard video ads utilize dynamic creative optimization (Degrees of Freedom) with 6 proven primary body variations and 6 headline variations:

### Destination & CTA
- **Destination Link:** `https://qalzy.com/products/the-worlds-first-ai-scale-that-automatically-counts-calories`
- **Call To Action Button:** `ORDER_NOW`
- **URL Parameter Tags (`url_tags`):**
  `?utm_source=facebook&utm_medium=paid_social&utm_campaign={{campaign.name}}&utm_adset={{adset.name}}&utm_content={{ad.name}}&utm_id={{campaign.id}}`
- **Promotions:** Auto-coupon detection enabled (`is_auto_update_allowed: true`).

### 6 Primary Text Variations:
1. `⚡ Why are you still typing your food into an app in 2026?  There's a scale that does it for you. Qalzy's built-in camera recognizes what's on your plate. The scale weighs it to the gram. Calories & macros log automatically — in 4 seconds. No typing with dirty hands. No scrolling through 40 wrong database entries. ✅ 2.9M verified foods ✅ Built by the team behind a 435,000-member tracking community ✅ 5000 + users rated us 4.7/5 🚀 Flash sale - 20% off right now! Get the SCALE NOW! www.qalzy.com`
2. `Ditch the food diary typing! Qalzy's smart scale has a built-in camera that recognizes your meals and logs calories & macros in 4 seconds. • No more dirty hands or endless scrolling • 2.9M verified foods at your fingertips • Rated 4.7/5 by over 5000 users. Limited time: Get 20% off this Autumn! Shop now → www.qalzy.com`
3. `Ditch the food diary apps! Qalzy's smart scale recognizes your meal with its built-in camera and weighs it to the gram. Calories & macros logged in 4 seconds - no typing required! • 2.9M verified foods • Built by a team of tracking experts (435,000+ members) • 5,000+ users rate us 4.7/5. Limited time: 20% off this Autumn! Get Qalzy now at www.qalzy.com`
4. `Ditch the food diary hassle! Say goodbye to typing with dirty hands and endless scrolling. Qalzy's smart scale does it all: • Recognizes your food with a built-in camera • Weighs to the gram for accurate logging. Join 5000+ happy users who rate us 4.7/5! Autumn sale: get 20% off now! Limited time offer - grab yours today at qalzy.com`
5. `Ditch the food diary apps! Introducing Qalzy: a smart scale with a built-in camera that recognizes your food and logs calories & macros in 4 seconds. • No more typing with dirty hands • No scrolling through wrong database entries. Trusted by: • 2.9M verified foods • A team behind a 435,000-member tracking community • 5000+ users rated us 4.7/5. Limited time offer: 20% off! Get yours now at www.qalzy.com`
6. `Ditch the food diary apps in 2026! Introducing Qalzy: a smart scale with a built-in camera that logs your meals automatically. • Recognizes 2.9M+ verified foods • Weighs to the gram, tracks calories & macros in 4 seconds. No more typing with dirty hands or endless scrolling! Trusted by 435k trackers and rated 4.7/5 by 5000 users. Limited time offer: get 20% off now! Shop now at www.qalzy.com`

### 6 Headlines:
1. `🚀 Flash sale - 20% off right now!`
2. `Scale Up Your Nutrition in 4 Seconds`
3. `Scale Your Meal Tracking Up in 4s`
4. `⚡ Scale Your Food in 4 Seconds`
5. `2.9M Foods, 1 Scale, No Hassle`
6. `4.7/5 Stars, 5000+ Users Love It`

---

## Technical Architecture & Meta API Guidelines

### 1. Native "Create Ad" Format (`object_story_spec.video_data`)
- Video is uploaded directly to `act_1351291616909846/advideos`.
- Thumbnail frame extracted at 1s and uploaded to `act_1351291616909846/adimages` to generate `image_hash`.
- Creative is structured natively via `object_story_spec.video_data` with `video_id`, `image_hash`, and `call_to_action`.
- In Meta Ads Manager UI, this renders under native **"Create Ad"** rather than "Use Existing Post".
- **Meta App Requirement:** The underlying Meta App (`Hermes Integration`, App ID `1658416769041399`) must remain in **Live Mode** with an active Privacy Policy URL (`https://qalzy.com/policies/privacy-policy`) for `object_story_spec` ad creation to succeed.

### 2. Advantage+ Enhancements (`degrees_of_freedom_spec`)
- **Active Features (`OPT_IN`):** `enhance_cta` (with `text_extraction: OPT_IN`), `inline_comment`, `product_extensions` (with `pe_carousel: OPT_IN`), `video_filtering`.
- **Inactive Features (`OPT_OUT`):** `advantage_plus_creative`, `video_auto_crop`, `music_generation`, `carousel_to_video`, `text_optimizations`.
- **API Deprecation Rule:** Never include `"standard_enhancements": {"enroll_status": "OPT_IN"}`. Meta rejects it with error subcode 3858504.
