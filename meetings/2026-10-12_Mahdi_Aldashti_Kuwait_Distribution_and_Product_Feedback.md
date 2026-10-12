# Qalzy <> Mahdi Aldashti: Kuwait Distribution Wholesale Agreement & Product Feedback

**Date:** 2026-10-12  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/mahdi-aldashti]]  
**Companies:** [[companies/qalzy]], [[companies/portless]]  

---

## Summary
Commercial negotiation and product review call between Qalzy founders and Mahdi Aldashti regarding retail and wholesale distribution in Kuwait. Mahdi shared detailed product feedback from testing his sample scale (grilled vs. fried chicken classification, a French fries calorie calculation bug, and onboarding questionnaire friction). The parties formally agreed on commercial terms for an initial wholesale order of 250 units at $85/unit, with critical logistics timing tied to Qalzy's upcoming inventory migration from China to the US.

---

## Key Discussion Points

### 1. Sample Device Testing & Product Feedback
- **Food Classification:** Mahdi noted grilled chicken breast was classified as fried chicken. Kostas explained camera angle and lighting dynamics and noted continuous Gemini AI vision model improvements.
- **French Fries 1,000 Calorie Bug:** Mahdi tested store-bought seasoned fried potatoes and the app logged over 1,000 calories. Michael identified that the FatSecret database entry only existed for a 35g serving size, causing a multiplication error on larger portions. Michael resolved to patch the backend calculation immediately.
- **Onboarding Questionnaire Length:** Mahdi felt the setup questionnaire had too many questions. Kostas presented funnel data: 64% completion rate for short onboarding vs. 55% for the extensive questionnaire, but the detailed questionnaire generates significantly higher subscription conversion, retention, and customer lifetime value.
- **User Feature Proposal ("User Pantry"):** Mahdi proposed allowing users to build a personal "Pantry Library" of regular household staples (e.g. specific low-fat milk, local cereals) to serve as the scale's primary matching source before searching public databases.

### 2. Commercial Agreement & Pricing
- **Order Volume:** Initial commercial batch of **250 units**.
- **Unit Pricing:** Finalized at **$85.00 USD / unit** EXW. Kostas and Michael accepted $85 to provide Mahdi sufficient margin to invest heavily into local Kuwait retail marketing and creator seeding.
- **Launch Timing:** Mahdi is traveling for 3 weeks starting mid-October; target launch window in Kuwait is mid-November 2026.

### 3. Supply Chain & China Inventory Deadline
- **Warehouse Transition Constraint:** All Qalzy stock is currently stored in China at Portless. Qalzy is preparing to move remaining stock into the US via ocean freight.
- **Logistics Imperative:** The 250 units for Kuwait must ship directly from China before the US shipment departs. Re-exporting units from the US back to Kuwait would be financially prohibitive.
- **Next Steps on Shipping:** Mahdi will pay for freight and requested carton dimensions, gross weights, and pallet specs so his logistics agent can quote shipment.

---

## Action Items
- [ ] **Kostas Koukoravas:** Contact Ryan Torreta at Portless to request pallet configuration, carton measurements, and gross weight for 250 units.
- [ ] **Michael Michelis:** Patch the FatSecret 35g portion scaling bug on the backend and confirm fix to Mahdi via email.
- [ ] **Mahdi Aldashti:** Review shipping specs upon receipt and commit to the China freight window before traveling.
