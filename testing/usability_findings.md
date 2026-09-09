# AgriConnect: Usability Testing Findings & V1 to V2 Iterations

## 1. Quantitative Usability Results (N=10 Participants)

| Task Description | V1 Completion Rate | V1 Time-on-Task | V2 Completion Rate | V2 Time-on-Task | Primary Friction Observed |
|:---|:---:|:---:|:---:|:---:|:---|
| **T1: Voice Discovery** | 90% | 42s | **100%** | **18s** | V1 mic button was small; enlarged to 72px in V2. |
| **T2: ROI Interpretation** | 70% | 68s | **100%** | **24s** | Gross vs Net confusion; replaced with "Cash-in-Hand" card. |
| **T3: Kit COD Order** | 80% | 55s | **100%** | **22s** | Farmers feared online payment; added green COD badge. |
| **T4: SOP Video Cache** | 90% | 30s | **100%** | **12s** | Confusion over data usage; added "Offline Ready" icon. |
| **T5: Mark Task Done** | 90% | 20s | **100%** | **8s** | Small checkbox; replaced with full-width green banner. |
| **T6: Doctor SOS Call** | 60% | 75s | **90%** | **15s** | SOS was hidden in menu; converted to persistent floating button. |
| **T7: Buyer Confirmation** | 90% | 45s | **100%** | **19s** | Pickup location ambiguity; added village landmark confirmation. |
| **OVERALL AVERAGE** | **81.4%** | **47.9s** | **98.6%** | **16.9s** | **System Usability Scale: 78.5 -> 88.0 (Grade A+)** |

---

## 2. The 5 Core UX Iterations (V1 -> V2 Evolution)

### 1. The "Cash-in-Hand" Net Profit Card
* *V1 Friction*: In testing, 3 out of 10 farmers confused Gross Revenue (Rs. 9,000) with Net Profit (Rs. 5,800), fearing hidden costs.
* *V2 Fix*: Removed the multi-column accounting table. Replaced with a single high-contrast card showing **"Rs. 5,800 Net Profit in Pocket (Jeb me Shuddh Munafa)"** alongside currency note graphics and automated voice narration.

### 2. Bottom Floating Emergency Doctor SOS Trigger
* *V1 Friction*: Non-literate farmers could not locate the crop disease help option nested inside the top settings menu.
* *V2 Fix*: Implemented a persistent 64px floating red button `[ SOS: Crop Doctor ]` anchored at the bottom right of every SOP screen, connecting to an agronomist callback in 1 tap.

### 3. Automatic Vernacular Voice Narration on Screen Mount
* *V1 Friction*: Illiterate participants (P02, P05, P08) stared at text screens waiting for instructions.
* *V2 Fix*: Screen entry triggers auto-speech synthesis in Hindi/Malvi ("Ramesh ji, aaj aapko mushroom bag me cheera lagana hai"), achieving **95%+ independent task execution** for non-literate users.

### 4. 1-Tap WhatsApp Family Consultation Share
* *V1 Friction*: Young farmers (Ramesh, Dinesh) wanted to discuss the Rs. 3,200 starter kit with their father/elder brother before buying.
* *V2 Fix*: Added a prominent green `[ Share to Family on WhatsApp ]` button that shares an audio-visual summary card directly with family members.

### 5. "Offline-Ready" Green Status Badging
* *V1 Friction*: Farmers worried that opening video SOPs would consume expensive daily mobile data or fail in fields without network.
* *V2 Fix*: Added a prominent badge `[ Offline Ready (Bina Internet Chalega) ]`, confirming videos are stored locally on the phone.
