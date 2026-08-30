---
type: email
title: "[URGENT] Qalzy orders on hold"
date: 2026-07-27
thread_id: 19f93e628f51c451
source: gmail
participants:
  - kostas@qalzy.com
  - implementations@portless.com
  - support@portless.com
  - shane@portless.com
  - michael@qalzy.com
  - wesley@portless.com
---

# [URGENT] Qalzy orders on hold

Entities: [[people/kostas-koukoravas]] [[companies/portless]] [[people/michael]] [[companies/qalzy]]

## 2026-07-24 11:32 — kostas@qalzy.com to implementations@portless.com, support@portless.com, shane@portless.com, michael@qalzy.com, wesley@portless.com

Hi Implementations and support teams,

We can see in the portal that all our orders (even the ones with everything
in stock) are marked as ON_HOLD.

Examples:

https://portal.portless.com/orders/AO5pqu7C5AuO3xtAJMmu/show
https://portal.portless.com/orders/MTUKZ8OB255u0FvhjE00/show
https://portal.portless.com/orders/Lsq7CXwVYxtUKw8FMivD/show

Wesley mentioned that he checked the order managment system and it doesn't
seem to show any orders.

Can you please look into this urgently so we can go live?

Best,
Kostas

## 2026-07-24 13:49 — implementations@portless.com to kostas@qalzy.com, shane@portless.com, michael@qalzy.com, wesley@portless.com

Hi Kostas,

 These orders should now be updated.

 It appears that the orders were imported via CSV, and there is a new automation in place that automatically puts manually imported orders on hold. My team wasn’t aware this automation had been implemented, but the orders have now been released.

 Please note that the Portal may take a few minutes to reflect the updated status.

 Sorry for the confusion, and thanks for bringing this to our attention. Please let us know if you notice any other issues as you prepare to go live.

 Cheers, Jeff

## 2026-07-24 14:26 — michael@qalzy.com to implementations@portless.com, kostas@qalzy.com, shane@portless.com, wesley@portless.com

Hi Jeff,

Thank you for sorting this out.
I can see that we have 142 orders with errors. I can see that some are from our side due to wrong data, but most of them I think that there being rejected from your system.

For example: "The recipient name must not exceed 21 characters and cannot contain numbers." I think there are people with long names like "Ming Yan Michelle Leung".

Also: PBID0010659821 "Order rule verification failed: [Ralf Buehler] Recipient's phone number or recipient's mobile phone number: Please check the recipient's mobile phone number or phone number. Only numbers, plus signs, hyphens, parentheses, and forward slashes are allowed, and the number of characters cannot exceed 30."

I see the phone number is: 4916099110911, so I don't understand the problem.

What is the best way to go through all these?

Best,
Michael

Michael Michelis
COO
michael@qalzy.com
www.qalzy.com

## 2026-07-25 11:29 — kostas@qalzy.com to michael@qalzy.com, implementations@portless.com, shane@portless.com, wesley@portless.com

Hi Jeff,

I went through the failed orders and I can see that problems fall into
these categories:

   1. Long names - not sure what can be done about this
   2. Zip code issues - I believe there was an issue with
   convection between csv and google sheets formats so some post codes were
   treated as numbers and the trailing zeros were skipped.
   3. Phone number issues. Same problem as above with the trailing numbers
   I suspect. The error message coming from your system implies otherwise but
   I can't quite see what the problem is because the validation rules seem to
   be met.
   4. Unsupported characters like "(", "[" in names and addresses.
   5. Military post address
   <https://portal.portless.com/orders/pfmyLPMF1yeRuez5m31H/show>. Looks
   like that's not supported by your system?

Can you let me know how you propose we sort these out? One option would be
for you to delete the orders with errors from your system and I can provide
a new file with 2 and possibly* 3 fixed.

I'm unsure how to address 1, 4 and the seemingly valid numbers on 3 that
still error in your system. Please advise. Also, let me know if you ship to
military addresses.

Best,
Kostas

## 2026-07-27 16:31 — michael@qalzy.com to kostas@qalzy.com, implementations@portless.com, shane@portless.com, wesley@portless.com

Hi Jeff,

Thank you for making progress on this.

We now have a problem with new orders. They are getting tagged on Shopify as "portless_accepted" and "portless_ready", but we can't see them on the portless portal. I have raised ticket #119457399, but if you can check on your end as well if the integration is working properly that'd be great!

Best,
Michael

## 2026-07-27 18:17 — implementations@portless.com to michael@qalzy.com, kostas@qalzy.com, shane@portless.com, wesley@portless.com

Hey Kostas,

 Apologies for the delay.

 I forgot to enable the Pipe17 routing rule that sends orders to our WMS. I've turned it on now, so you should see the portless_sent_to_fulfillment tag on the order, and it should now be visible in our system.

 Regarding the fulfillment exceptions:
 - Long names: It looks like our fulfillment center has already shipped the affected orders despite the exception.
- ZIP code and phone number: I've communicated these issues to our team, and we should be able to resolve them on our end.
- Unsupported characters: It appears our team has already fixed this issue, so we can proceed with shipping those orders.

 As for military addresses, unfortunately, we do not ship to Army Post Office (APO) addresses as well as .

 Please let me know if you have any other questions.

 Thanks,
