---
type: email
title: 'Truemed HSA/FSA Integration: Doola US Entity vs Virtual Address Clarification'
date: '2026-11-05'
---

# Truemed HSA/FSA Integration: Doola US Entity vs Virtual Address Clarification

**Date:** 2026-11-05  
**From:** [[people/kostas-koukoravas]] <kostas@qalzy.com>  
**To:** Leo Schottenstein <leo@truemed.com>  
**Subject:** Re: Qalzy <> Truemed || follow up + next steps  

## Context & Key Points
- Following up on Qalzy's preparations to launch Truemed HSA/FSA payments via ShopPay ahead of Black Friday.
- Leo Schottenstein previously suggested that other international merchants bypass full entity incorporation by utilizing Doola to obtain a registered US business address (Delaware/Wyoming) and US EIN to satisfy Stripe Connect compliance.
- Kostas clarified that Doola is an entity incorporation platform that forms legal LLCs or C-Corps rather than providing standalone virtual mailboxes. Forming a US LLC creates severe cross-border tax friction under UK HMRC rules (hybrid entity double taxation up to 70%).
- Kostas is actively resolving whether Stripe Connect / Truemed can accept Qalzy's existing US EIN and Revolut USD account with a third-party registered agent address, or whether a Delaware C-Corp subsidiary must be formalized first.
