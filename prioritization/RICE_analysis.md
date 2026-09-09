# AgriConnect: Feature Prioritization & RICE Analysis

---

## 1. The RICE Scoring Framework Formulation

$$\text{RICE Score} = \frac{\text{Reach} \times \text{Impact} \times \text{Confidence}}{\text{Effort}}$$

### Scoring Parameters & Standards
* **Reach (\(R\))**: Number of users impacted per 1,000 active monthly users over a 90-day cohort period (Grounded in survey percentages).
* **Impact (\(I\))**: Relative contribution to the North Star Metric (*Net Monthly Farmer Income*):
  * `3.0` = Massive Impact (Directly creates cashflow or prevents 100% crop loss)
  * `2.0` = High Impact (Directly drives conversion or execution)
  * `1.0` = Medium Impact (Enhances engagement or reduces friction)
  * `0.5` = Low Impact (Minor optimization)
* **Confidence (\(C\))**: Certainty based on empirical field evidence vs. hypothesis:
  * `100% (1.0)` = High Confidence (Directly verified by survey data)
  * `80% (0.8)` = Medium Confidence (Strong qualitative support / secondary market data)
  * `50% (0.5)` = Low Confidence / Experimental (Unvalidated hypothesis)
* **Effort (\(E\))**: Total engineering, design, and operations effort measured in **Person-Months (PM)**.

---

## 2. RICE Prioritization Master Table

| Rank | Feature Name | Reach (\(R\)) | Impact (\(I\)) | Confidence (\(C\)) | Effort (\(E\)) | RICE Score | MVP Priority Tier | Core PM Rationale & Survey Link |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| **1** | **Day-by-Day Visual SOP Task Checklist** | 800 | 3.0 | 1.0 (100%) | 2.0 PM | **1,200.0** | **P0 (Must Have)** | Solves the **56.5% training barrier**; prevents crop failure via daily bite-sized tasks. |
| **2** | **Voice-Guided Discovery & Dynamic ROI Estimator** | 870 | 2.0 | 1.0 (100%) | 1.5 PM | **1,160.0** | **P0 (Must Have)** | Translates **87.0% latent intent** into action; shows clear profit before risking money. |
| **3** | **1-Click Certified Starter Kit (COD)** | 750 | 3.0 | 0.8 (80%) | 2.0 PM | **900.0** | **P0 (Must Have)** | Overcomes **29.3% working capital fear** with <â‚¹3,500 all-in-one certified kits. |
| **4** | **Pre-Harvest Local B2B Buyer Matchmaking** | 600 | 3.0 | 0.8 (80%) | 2.0 PM | **720.0** | **P0 (Must Have)** | Addresses **21.7% market support demand**; guarantees cashflow on harvest day. |
| **5** | **100% Vernacular Voice Navigation (Hindi/Malvi)** | 1000 | 1.5 | 1.0 (100%) | 2.5 PM | **600.0** | **P0 (Must Have)** | Eliminates friction for the **38.0% illiterate farmer cohort**; universal foundation. |
| **6** | **Hyperlocal Peer Video Proof Feed** | 700 | 1.0 | 0.8 (80%) | 1.5 PM | **373.3** | **P1 (Should Have)** | Replaces non-existent govt aid (**98.9% none**) with high-trust local peer validation. |
| **7** | **Automated Weather & Heat Stress Alerts** | 600 | 1.0 | 0.8 (80%) | 1.5 PM | **320.0** | **P1 (Should Have)** | Prevents crop heat stress by overriding daily misting tasks during heatwaves. |
| **8** | **Photo Contamination Scanner (Agronomist SOS)** | 350 | 2.0 | 0.8 (80%) | 3.0 PM | **186.7** | **P1 (Should Have)** | Protects first-time grower crops from mold; async expert callback within 3 hours. |
| **9** | **Micro-Financing / Pay-After-Harvest Split** | 400 | 2.0 | 0.5 (50%) | 4.0 PM | **100.0** | **P2 (Could Have)** | Unlocks extreme marginal farmers; deferred to Phase 3 due to NBFC/credit risk. |
| **10** | **Multi-Mandi Real-Time Arbitrage Tracker** | 200 | 1.0 | 0.8 (80%) | 2.5 PM | **64.0** | **P2 (Could Have)** | Targets **20.7% semi-medium tier** (Virendra); secondary to core smallholder loop. |

---

## 3. Detailed Justification of RICE Scores

### 1. Day-by-Day Visual SOP Task Checklist (Score: 1,200.0)
* **Reach (800)**: Every farmer who begins a cultivation cycle must interact with daily tasks.
* **Impact (3.0)**: Direct causal link to crop survival. Without daily adherence (humidity, temperature), mushroom pinheads abort, destroying 100% of yield.
* **Confidence (1.0)**: 56.5% of survey respondents explicitly blamed lack of step-by-step training for non-adoption.
* **Effort (2.0 PM)**: Standardized sequential task engine, video card carousel, offline SQLite cache.

### 2. Voice-Guided Discovery & ROI Estimator (Score: 1,160.0)
* **Reach (870)**: Aligns with the 87.0% of survey respondents seeking agribusiness diversification.
* **Impact (2.0)**: Converts passive curiosity into purchase intent by transparently showing net profit calculations.
* **Confidence (1.0)**: Empirical proof that 100% of under-45 farmers want to start if ROI is transparent.
* **Effort (1.5 PM)**: Client-side mathematical calculator with dynamic visual slider controls.

### 3. Pre-Harvest B2B Buyer Matchmaking (Score: 720.0)
* **Reach (600)**: Harvest-ready growers reaching Day 38+.
* **Impact (3.0)**: Solves the ultimate monetization bottleneck; converts physical crop into verified bank cash.
* **Confidence (0.8)**: High confidence based on survey proof (100% of diversified farmers made higher profit); 0.8 accounts for local buyer liquidity variance.
* **Effort (2.0 PM)**: Harvest broadcast queue, buyer web portal, automated SMS contract slips.
