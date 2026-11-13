---
type: email
title: 'Firebase Crashlytics Alert: Missing dSYM for iOS com.qalzy.app v2.2.15 (2)'
date: '2026-11-12'
---

# Firebase Crashlytics Alert: Missing dSYM for iOS com.qalzy.app v2.2.15 (2)

**Date:** 2026-11-12  
**Parties:** Firebase Crashlytics <firebase-noreply@google.com>, [[people/michael-michelis]] <michael@qalzy.com>  
**Subject:** Missing dSYM – iOS com.qalzy.app 2.2.15 (2)  

## Key Points & Context
- **Missing Debug Symbols:**
  - Firebase Crashlytics flagged missing debug symbols (dSYM) for the latest iOS release build `2.2.15 (2)`.
  - dSYM UUID: `AA0B8F68-4854-39A4-A302-B497DAFFE55D`.
  - Impact: Without the corresponding dSYM uploaded to Firebase, crash reports from iOS devices for version 2.2.15 cannot be properly symbolicated into human-readable stack traces.
