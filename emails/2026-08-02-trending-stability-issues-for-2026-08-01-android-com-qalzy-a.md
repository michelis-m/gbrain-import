---
type: email
title: "Fwd: Trending stability issues for 2026-08-01 – Android com.qalzy.app"
date: 2026-08-02
thread_id: 19fc0eb608bb1012
source: gmail
participants:
  - kostas@qalzy.com
  - michael@qalzy.com
---

# Fwd: Trending stability issues for 2026-08-01 – Android com.qalzy.app

Entities: [[people/kostas-koukoravas]] [[people/michael]] [[companies/qalzy]]

## 2026-08-02 05:21 — kostas@qalzy.com to michael@qalzy.com

FYI - I didn’t know you pushed it live
Sent from my iPhone

Begin forwarded message:

*From:* firebase-noreply@google.com
*Date:* 2 August 2026 at 08:13:20 EEST
*To:* kostas@qalzy.com
*Subject:* *Trending stability issues for 2026-08-01 – Android com.qalzy.app*

﻿Trending stability issues for 2026-08-01
Firebase

| Qalzy•com.qalzy.app# Trending stability issues for 2026-08-01 | |

| ## Trending issuesIssues rapidly gaining momentum |
| io.flutter.view.AccessibilityBridge$Api31Impl.isBoldText[](https://console.firebase.google.com/project/nutrioscale-d5150/crashlytics/app/android:com.qalzy.app/issues/e4f589a1768d33cb82d431f744ac74a8?time=last-seven-days) java.lang.NoSuchFieldError - No instance field fontWeightAdjustment... 2.2.7 (80)10 crashes2 users |

[View Crashlytics dashboard](https://console.firebase.google.com/project/nutrioscale-d5150/crashlytics/app/android:com.qalzy.app/issues?time=last-seven-days)

This email is to notify you about important service information regarding your Firebase project

Manage your [Alert settings](https://console.firebase.google.com/project/nutrioscale-d5150/settings/alerts)

## 2026-08-02 05:48 — michael@qalzy.com to kostas@qalzy.com

This is weird, it's not live:
I'll check the crash

Michael Michelis
COO
michael@qalzy.com
www.qalzy.com

## 2026-08-02 06:23 — michael@qalzy.com to kostas@qalzy.com

Maybe that was one of their testers?
Current product release is Build 77 (2.2.6) and now is ready to go live Build 80 (2.2.7), which should not be affected by this bug. (only happens in OnePlus/Redmi phones).

## 2026-08-02 06:24 — kostas@qalzy.com to michael@qalzy.com

Ok so needs to be fixed in 2.2.7 before we release?

## 2026-08-02 06:26 — michael@qalzy.com to kostas@qalzy.com

No, should be okay. This was a problem in a previous build it seems with the flutter version
