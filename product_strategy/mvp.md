# AgriConnect: MVP Definition & Feature Prioritization

---

## 1. MVP Objective & Core Value Loop

### Objective
To validate that smallholder farmers (holding <5 acres) can successfully launch, maintain, and monetize an indoor or small-plot agribusiness within 45â€“60 days, achieving a net monthly income increase of â‚¹8,000â€“â‚¹15,000 with zero prior vocational experience.

```mermaid
graph LR
    A["1. Discovery & ROI"] -->|Selects Space & Budget| B["2. Day-by-Day Visual SOPs"]
    B -->|Follows Daily Task Checklist| C["3. Starter Kit Delivery"]
    C -->|Cultivates with Certified Inputs| D["4. Pre-Harvest Buyer Match"]
    D -->|Realizes Fast Cash at Harvest| E["â˜… AHA! MOMENT: First â‚¹10,000 Earned in 45 Days"]
```

---

## 2. Problem â†’ User Need â†’ Feature Mapping Matrix

Every feature in the AgriConnect MVP directly maps to an empirical survey finding from our 92-farmer research.

| # | Survey Evidence & Pain Point | User Need | MVP Feature Solution | Feature Tier |
|:---|:---|:---|:---|:---:|
| **1** | **87.0% (80/92) want to start agribusiness**; Top choices: Mushroom (20.0%), Polyhouse/Vertical (18.8%), Poultry (11.2%). | Clear understanding of which venture fits their available space and budget. | **Venture Discovery & ROI Estimator**: Visual selector (Space e.g. 100 sq.ft + Budget â‚¹3,000 â†’ Estimated profit â‚¹12,000). | **Must Have (P0)** |
| **2** | **56.5% (52/92) blocked by Lack of Awareness & Practical Training**; traditional YouTube videos are unstructured. | Day-by-day, bite-sized execution instructions without technical jargon. | **Daily Visual SOP & Task Calendar**: Step-by-step daily micro-checklists (<3 min video + audio reminders for watering/humidity). | **Must Have (P0)** |
| **3** | **38.0% (35/92) are Illiterate**; 57.1% tech discovery occurs via YouTube/WhatsApp video. | 100% non-textual, zero-friction interface. | **Voice-First Navigation & Regional Dialect UI**: Native voice search and audio prompts in Hindi/Malvi with bold pictorial cards. | **Must Have (P0)** |
| **4** | **29.3% cite "Money" (working capital deficit)**; 67.4% find modern agri-tech unaffordable. | Low-cost, certified starter inputs delivered directly to the village. | **Curated Micro Starter Kits (<â‚¹3,500)**: All-in-one certified spawn/seed packs, organic substrate, and basic spray kit. | **Must Have (P0)** |
| **5** | **21.7% request Market Support**; fear of perishability and middleman price cuts. | Guaranteed local buyer linkages before harvest maturity. | **Local B2B Buyer Matching Board**: Pre-harvest matchmaking with verified local restaurants, hotels, and mandi traders. | **Must Have (P0)** |
| **6** | Fear of crop contamination or mold during cultivation cycle. | Rapid diagnostic help when crops show discoloration. | **Photo-Based Contamination Scanner & Expert Audio SOS**: Snap a photo of infected crop bags for agronomist triage. | **Should Have (P1)** |
| **7** | **98.9% received zero govt support**; 92.8% rely on peer word-of-mouth. | High-trust social proof from nearby farmers. | **Hyperlocal Peer Proof Feed**: 60-second video testimonials of neighboring farmers displaying real harvest and payout receipts. | **Should Have (P1)** |

---

## 3. MoSCoW Prioritization Framework

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚                                 MOSCOW MVP SCOPE TABLE                                 â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚  MUST HAVE (P0) â€” Non-Negotiable Core Value Loop                                       â”‚
â”‚  1. Voice-First Onboarding & Regional Language Selector (Hindi/Malvi)                  â”‚
â”‚  2. Micro-Enterprise Discovery & Interactive Space/ROI Calculator                      â”‚
â”‚  3. Day-by-Day Visual SOP Task Checklist (Mushroom & Backyard Poultry Blueprints)      â”‚
â”‚  4. 1-Click Low-Capex Starter Kit Ordering (<â‚¹3,500 with Cash on Delivery)             â”‚
â”‚  5. Pre-Harvest Local Buyer Matchmaking Board (Small-batch harvest off-take)           â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚  SHOULD HAVE (P1) â€” High Value Post-Launch Optimizations                               â”‚
â”‚  1. Photo-based Contamination & Disease Scanner (Async agronomist review)              â”‚
â”‚  2. Hyperlocal Peer Video Testimonials & Earnings Proof Feed (<50 km radius)           â”‚
â”‚  3. Weather & Climate Push Alerts (Syncs task checklist with heat/humidity spikes)     â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚  COULD HAVE (P2) â€” Future Expansion Features                                           â”‚
â”‚  1. Micro-Financing / Pay-After-Harvest Input Split (50% upfront, 50% on harvest sale) â”‚
â”‚  2. Multi-Mandi Live Arbitrage Board (Comparative rate intelligence for surplus)       â”‚
â”‚  3. Group Produce Pooling & Collective Transport Dispatch                              â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚  WON'T HAVE / NOT NOW (Out of Scope for MVP)                                           â”‚
â”‚  1. Generic Agrochemical & Fertilizer E-Commerce Storefront (Avoid AgroStar copycat)   â”‚
â”‚  2. IoT Sensor / Polyhouse Automation Hardware Integration (Too costly for smallholder)â”‚
â”‚  3. Open Social Network / Chat Forum (High moderation cost; low conversion)            â”‚
â”‚  4. Dedicated Cold Chain Trucking Fleet (Capital intensive; utilize local buyer pickup)â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

---

## 4. MVP Scope Boundaries & Non-Goals

### Strict Non-Goals for the MVP
1. **Non-Goal 1: We are NOT building an open commodity trading platform for staples.**  
   * *Rationale*: Trading 100 quintals of Wheat or Soybean requires heavy APMC licensing, physical weighing bridges, and massive working capital. Our MVP focuses exclusively on **high-density, small-batch micro-agribusinesses (Mushroom, Exotic Greens, Poultry)**.
2. **Non-Goal 2: We are NOT building a generic agricultural e-commerce storefront.**  
   * *Rationale*: AgroStar and DeHaat already sell thousands of generic pesticide and fertilizer SKUs. AgriConnect exclusively sells **curated, high-germination starter incubation kits** tied to specific blueprints.
3. **Non-Goal 3: We are NOT requiring hardware IoT or soil sensors.**  
   * *Rationale*: Survey proved 67.4% find technology unaffordable. The MVP relies strictly on manual, low-cost visual analog tools (e.g. â‚¹150 hygrometer/thermometer).
