# Firebase Alert: Missing dSYM for iOS v2.2.10 (4)

**Date:** 2026-09-27  
**From:** Firebase (`firebase-noreply@google.com`)  
**To:** [[people/michael-michelis]] (`michael@qalzy.com`)  
**Subject:** `Missing dSYM – iOS com.qalzy.app 2.2.10 (4)`  
**Companies:** [[companies/qalzy]], Firebase, Google

---

## Summary
Firebase Crashlytics detected a missing debug symbol (dSYM) file for the latest iOS release of Qalzy:

- **App ID:** `com.qalzy.app` (iOS)
- **App Version:** `2.2.10 (4)`
- **Firebase Project:** `nutrioscale-d5150`
- **Missing dSYM UUID:** `C651630A-5615-326D-A952-7F3A4C648504`
- **Console Link:** [Upload dSYM to Firebase](https://console.firebase.google.com/project/nutrioscale-d5150/crashlytics/app/ios:com.qalzy.app/dsyms)

## Action Needed
- The mobile/iOS build pipeline needs to upload the dSYM archive corresponding to build `2.2.10 (4)` so that incoming crash logs can be properly symbolicated and debugged.
