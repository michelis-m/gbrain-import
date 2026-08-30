---
type: email
title: "Fwd: Recipe Glitch"
date: 2026-08-03
thread_id: 19fc673eeb93096b
source: gmail
participants:
  - kostas@qalzy.com
  - michael@qalzy.com
  - russellkasdon@gmail.com
  - hello@qalzy.com
---

# Fwd: Recipe Glitch

Entities: [[people/kostas-koukoravas]] [[people/michael]] [[companies/qalzy]]

## 2026-08-03 07:08 — kostas@qalzy.com to michael@qalzy.com

---------- Forwarded message ---------
From: Russell Kasdon <russellkasdon@gmail.com>
Date: Sun, 2 Aug 2026 at 17:14
Subject: Recipe Glitch
To: hello@qalzy.com <hello@qalzy.com>

I am having a problem with my new recipies disappearing when I make them. I
have attached the screen recording below

[image: Video File]
<https://drive.google.com/file/d/16dIRj9Lg4Om_RCYRoQz-JFG6hqrFjTje>
ScreenRecording_07-31-2026 07-18-53_1.mp4
<https://drive.google.com/file/d/16dIRj9Lg4Om_RCYRoQz-JFG6hqrFjTje>

## 2026-08-03 08:56 — michael@qalzy.com to russellkasdon@gmail.com, hello@qalzy.com

Hi Russell,

Thank you for sending the recording.
It looks like we have an upper limit of 100 recipes at the moment in the app. This is why you are not able to see the new recipes you create after a while as you have 109 recipes in the app.

I have raised this issue with our tech team and we'll increase the limit in one of our upcoming releases.

Thank you again for reporting this.

Best,
Michael

Michael Michelis
COO
michael@qalzy.com
www.qalzy.com

## 2026-08-03 08:56 — kostas@qalzy.com to michael@qalzy.com

Wow good catch! 109 recipes??

## 2026-08-03 08:57 — michael@qalzy.com to kostas@qalzy.com

idiot Grant had set a limit

## 2026-08-03 12:05 — kostas@qalzy.com to michael@qalzy.com

is this a front end or backend fix and do we have a ticket?

## 2026-08-03 12:06 — michael@qalzy.com to kostas@qalzy.com

I fixed it on master, it was on the app. Not sure if we want to introduce any sort of pagination, but I changed the limit to 1000
