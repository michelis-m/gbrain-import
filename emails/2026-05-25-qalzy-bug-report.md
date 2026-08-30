---
type: email
title: "Qalzy - Bug Report"
date: 2026-05-25
thread_id: 19e49233941dff55
source: gmail
participants:
  - michael@qalzy.com
  - denys.amelkin@gmail.com
  - giorgos@intelistyle.co.uk
  - kostas@qalzy.com
---

# Qalzy - Bug Report

Entities: [[people/kostas-koukoravas]] [[people/michael]] [[companies/qalzy]]

## 2026-05-21 06:04 — michael@qalzy.com to denys.amelkin@gmail.com

Hi Denys,

Thank you for your report.

1. Right now, we only import exercise from Health Connect and not counting steps seperately. This is however a feature we have on our backlog and we plan to implement soon
2. This should be working. I have an OURA ring and a Samsung watch that both write exercise to Health Connect and Qalzy deduplicates it and shows only one exercise. Can you send me more details on this and I can look into it.
3. Qalzy will check Health Connect once opened and get any weight values are registered there. Did you check that you have shared all the permissions with the Qalzy app?

Let me know if you have any more issues or questions.

Best,
Michael

Michael Michelis
COO
michael@qalzy.com
www.qalzy.com

## 2026-05-21 07:14 — denys.amelkin@gmail.com to michael@qalzy.com

Hello Michael,

Thank you for your response!

1. It's really great information. Thank you!

2. Here is how it looks like in Health Connect after training:
[image: image.png]
[image: image.png]
So Hevy added 74 minutes of Strength training and an additional 574 kCal to
the Total calories burned database.
Qalzy took this training and adjusted calories with an additional 1045
kCal. I wonder how this value is calculated and if I can somehow influence
this.
[image: image.png]

3. Sorry, my bad. I just noticed that some weight values were imported from
Health Connect. I will do some additional tests and come back to you.

//Denys

## 2026-05-21 07:29 — michael@qalzy.com to denys.amelkin@gmail.com

Hi Denys,

Can you send me a screenshot of the Health Connect entries for 2. ?

That would really help to troubleshoot this.

Best,
Michael

## 2026-05-21 07:46 — denys.amelkin@gmail.com to michael@qalzy.com

Oh, sorry. Sending them as an attachment.

## 2026-05-21 08:14 — michael@qalzy.com to denys.amelkin@gmail.com

Hi Denys,

Apologies I should have been more clear.

• Can you go to Seetings and search: "Health Connect" on your Android.
• Tap on "Health Connect" (should be at the bottom)
• Tap on Data and access
• Tap on Exercise > See All Data Entries > take screenshot
• then go back and tap Active Calories Burned > See All Data Entries > take screenshot

It should look like this:
Hopefully that's not too much trouble for you. Thanks in advance for all the help!

Best,
Michael

## 2026-05-21 08:37 — denys.amelkin@gmail.com to michael@qalzy.com

Hi Michael,

For Exercise it's the same since only Hevy populates this data:

[image: image.png]

However I don't have Active Calories Burned in my Health Connect DB, only
Total calories burned. My watch (OHealth) and Havy puts data there:
[image: image.png]

[image: image.png]

According to the documentation Active calories burned is a separate type of
data that doesn't count BMR and sounds logical that Qalzy is trying to use
it:
https://developer.android.com/reference/kotlin/androidx/health/connect/client/records/ActiveCaloriesBurnedRecord

Does this mean that Hevy should also put data to ActiveCaloriesBurnedRecord
to make integration working with correct calories adjustment?

//Denys

## 2026-05-22 03:38 — michael@qalzy.com to giorgos@intelistyle.co.uk, kostas@qalzy.com

---------- Forwarded message ----------
From: Denys Amelkin <denys.amelkin@gmail.com>
Date: 21 May 2026 at 16:37 +0800
To: michael@qalzy.com
Subject: Re: Qalzy - Bug Report

## 2026-05-25 09:45 — michael@qalzy.com to denys.amelkin@gmail.com

Hi Denys,

This is super helpful. The team is already working on it and we will deploy a fix on our next release. Thank you so much for the help!

Best,
Michael

## 2026-05-25 11:32 — denys.amelkin@gmail.com to michael@qalzy.com

Hi Michael,

That's awesome! Thank you very much!

//Denys
