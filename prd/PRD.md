# AgriConnect: Product Requirements Document (PRD)

| Document Version | Author | Status | Target Release | Last Updated |
|:---|:---|:---|:---|:---|
| **v1.0 (MVP Specification)** | Product Management Team (IIT Kharagpur) | Approved for Dev | Q4 2026 / Alpha Release | September 2026 |

---

## 1. Product Overview & Executive Summary

**AgriConnect** is a mobile-first micro-enterprise incubation platform and marketplace tailored for India's small and marginal farmers (holding <5 acres). The platform bridges the massive **68.5 percentage point drop-off between agribusiness intention (87.0%) and execution (18.5%)** by providing zero-friction vernacular execution blueprints, curated low-cost starter kits (<Rs. 3,500), and guaranteed local B2B buyer off-take linkages.

---

## 2. Target Users & Core Personas
* **Primary (P0)**: Ramesh Ahirwar (28 yrs, 1.5 ac, Matriculate) - Seeks Rs. 10k-15k/mo secondary income; needs structured, risk-free execution blueprints.
* **Secondary (P1)**: Babulal Lodhi (48 yrs, 2.5 ac, Illiterate) - Risk-averse marginal farmer; requires 100% voice assistance and pictorial guidance.
* **Commercial (P2)**: Virendra Patel (34 yrs, 7.5 ac, Graduate) - Progressive farmer needing direct B2B market off-take.

---

## 3. Core Functional Requirements (FRD)

### Module 1: Vernacular Voice Discovery & Dynamic ROI Estimator (FR-01)
* **Description**: Allows farmers to explore high-margin enterprises and calculate expected profit based on available space and budget using voice inputs in Hindi and Malvi.
* **User Stories**:
  * *As a non-literate farmer, I want to speak my available indoor space and budget so that I can see how much net monthly profit I will earn.*
* **Acceptance Criteria (Gherkin)**:
  ```gherkin
  Scenario: Farmer calculates Oyster Mushroom ROI via voice
    Given the farmer opens the AgriConnect app and taps the microphone button
    When the farmer says "Mere paas ek kamra hai aur 3000 rupaye hain" in Hindi
    Then the app recognizes the space (120 sq.ft) and budget (Rs. 3,000)
    And displays an interactive "Cash-in-Hand" card showing:
      | Total Starter Cost | Rs. 3,200 |
      | Expected Yield     | 60 kg     |
      | Gross Market Value | Rs. 9,000 |
      | Net Monthly Profit | Rs. 5,800 |
    And automatically speaks out the summary in clear Hindi audio narration.
  ```

### Module 2: Day-by-Day Visual SOP Task Calendar (FR-02)
* **Description**: Delivers a 45-day sequential, step-by-step task calendar with daily voice instructions, bite-sized 60-second video clips, and offline checklist capability.
* **User Stories**:
  * *As a first-time mushroom grower, I want daily morning audio task reminders so that I maintain exact moisture and temperature without crop failure.*
* **Acceptance Criteria (Gherkin)**:
  ```gherkin
  Scenario: Daily SOP task completion in offline mode
    Given the farmer has no cellular network connection in the village
    When the farmer opens the Today Task view for "Day 14: Bag Slitting & Misting"
    Then the cached 45-second visual video clip plays smoothly
    And the farmer taps the big green "Kaam Ho Gaya" (Task Completed) button
    Then the task status updates locally and syncs to cloud automatically upon network reconnection.
  ```

### Module 3: 1-Click Certified Starter Kit Procurement (FR-03)
* **Description**: Bundles and delivers laboratory-certified mushroom spawn, PP bags, formalin sterilizer, and sprayers via Cash-on-Delivery (COD).
* **User Stories**:
  * *As a capital-conscious farmer, I want to pay for my incubation starter kit in cash upon village delivery so that I do not risk online payments.*
* **Acceptance Criteria (Gherkin)**:
  ```gherkin
  Scenario: 1-Click Starter Kit Order via COD
    Given the farmer selects the "Oyster Mushroom 50-Bag Starter Pack (Rs. 3,200)"
    When the farmer clicks "Cash on Delivery se Mangwayein"
    Then an SMS and voice OTP confirmation is triggered
    And an order dispatch notification confirms delivery to village hub within 72 hours.
  ```

### Module 4: Pre-Harvest Local B2B Buyer Matchmaking (FR-04)
* **Description**: Broadcasts expected harvest date (Day N-7) to local institutional buyers (restaurants, wholesalers, hotels) within a 40 km radius at a guaranteed floor price.
* **User Stories**:
  * *As a harvesting farmer, I want a guaranteed buyer before picking my perishable mushrooms so that I never suffer distress sales or spoilage.*
* **Acceptance Criteria (Gherkin)**:
  ```gherkin
  Scenario: Pre-harvest buyer match confirmation
    Given the farmer's crop reaches Day 38 of the 45-day cycle
    When the platform triggers an automated buyer auction within 40 km
    Then a verified B2B buyer (e.g., "Saffron Restaurant, District Center") accepts the lot at Rs. 140/kg
    And the farmer receives an audio voice call confirming pickup time and guaranteed payment slip.
  ```

---

## 4. Non-Functional Requirements (NFR)
* **NFR-1 (Performance)**: App screen load time <1.2 seconds on 2G/3G networks; initial APK download size <12 MB.
* **NFR-2 (Offline-First)**: Complete 45-day SOP visual calendar operates 100% offline with background sync queue.
* **NFR-3 (Accessibility)**: Minimum touch target of 56px x 56px for rough thumb usage; contrast ratio >= 4.5:1 (WCAG AA).
* **NFR-4 (Security & Privacy)**: AES-256 encryption on all farmer financial transactions and complete PII scrubbing on shared marketplace feeds.
