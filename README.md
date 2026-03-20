# InsuRevive ⚡  
### AI-Powered Parametric Income Protection for Delivery Partners  

> **“We are not insuring assets — we are protecting livelihoods using AI-driven, real-time, parametric insurance.”**

---

## Problem Statement

Food delivery partners face unpredictable income loss due to:

• Weather disruptions  
• Extreme heat  
• Curfews / strikes  

✖ No existing insurance product protects daily earnings  

---

## Solution Overview

**InsuRevive** is an AI-powered platform that:

✔ Insures weekly income (not assets)  
✔ Uses parametric triggers  
✔ Enables automatic claims  
✔ Provides instant payouts  

---

## Persona & Real-World Scenario

### Delivery Partner – Vinod

- City: Hyderabad  
- Income: ₹800/day  
- Work: 9 hrs/day (full-time)  

### Scenario: Rain Disruption

- Rainfall > 50mm  
- Work stops for 3 days  

**Income Loss = ₹2400**  
**InsuRevive auto-pays ₹2400**

---

## Real-World Simulation: Before vs After InsuRevive

### Case Study 1: Vinod (Full-Time Worker)

| Scenario | Without InsuRevive | With InsuRevive |
|---------|------------------|----------------|
| Heavy Rain (3 days) | No income | Auto-trigger detected |
| Earnings | ₹0 | ₹2400 payout |
| Action Required | None / Loss absorbed | No action needed |
| Financial Impact | High loss | Income protected |

---

### Detailed System Flow & Calculations

**Step 1: Onboarding Data**

- Daily Income = ₹800  
- Work Hours = 9 hrs/day  
- City = Hyderabad  

---

**Step 2: DRS Calculation (Risk Profiling)**

```
Environmental Risk = 70
Zone Risk = 60
Work Dependency = 90

DRS = (70 + 60 + 90) / 3 = 73.3 → High Risk
```

---

**Step 3: Weekly Premium Calculation**

```
Base = ₹50
Risk Factor = 2 × DRS = 2 × 73 = 146
Stability Discount = ₹30

Weekly Premium = 50 + 146 - 30 = ₹166 (~₹160)
```

---

**Step 4: Real-Time Disruption Detection**

- Rainfall detected = 90 (high intensity)  
- AQI = 40  
- Temperature = 35  

---

**Step 5: WDI Calculation (Core Decision Model)**

```
WDI = (0.35 × 90) + (0.25 × 40) + (0.2 × 35)
    = 31.5 + 10 + 7
    = 48.5 → Moderate disruption
```

---

**Step 6: Claim Decision**

- WDI = 48.5 → Partial disruption  
- But rainfall exceeds parametric threshold (>50mm)  
→ Claim triggered  

---

**Step 7: Payout Calculation**

```
Coverage = Daily Income × Disruption Days
         = 800 × 3
         = ₹2400
```

---

**Final Outcome**

✔ Claim triggered automatically  
✔ No manual request required  
✔ ₹2400 credited instantly  

**→ Income stability maintained**

---

### Case Study 2: Ayesha (Part-Time Worker)

- Income: ₹500/day  
- Work: 5 hrs/day  

#### Scenario: Extreme Heat

- Temperature > 42°C  
- Unable to work for 2 days  

| Scenario | Without InsuRevive | With InsuRevive |
|---------|------------------|----------------|
| Heat disruption | Stops working | Trigger detected |
| Earnings | ₹0 | ₹1000 payout |
| Effort | No support | Fully automated |
| Outcome | Income loss | Stability maintained |

---

### Detailed System Flow & Calculations

**Step 1: Onboarding Data**

- Daily Income = ₹500  
- Work Type = Part-time  

---

**Step 2: DRS Calculation**

```
Environmental Risk = 65
Zone Risk = 50
Work Dependency = 50

DRS = (65 + 50 + 50) / 3 = 55 → Medium Risk
```

---

**Step 3: Disruption Detection**

- Temperature = 85 (scaled)  
- AQI = 70  
- Rain = 10  

---

**Step 4: WDI Calculation**

```
WDI = (0.35 × 10) + (0.25 × 70) + (0.2 × 85)
    = 3.5 + 17.5 + 17
    = 38 → Moderate disruption
```

---

**Step 5: Claim Trigger**

- Heat threshold exceeded (>42°C)  
→ Claim triggered automatically  

---

**Step 6: Payout Calculation**

```
Coverage = 500 × 2 = ₹1000
```

---

**Final Outcome**

✔ Heat-based trigger activated  
✔ ₹1000 payout credited  
✔ No claim filing required  

**→ Financial stability maintained**

---
---

## End-to-End Workflow

```
User Onboarding
      ↓
AI Risk Profiling (DRS)
      ↓
Weekly Plan & Premium Generated
      ↓
Real-Time Monitoring (Weather + AQI + Heat)
      ↓
WDI Calculation (Disruption Score Engine)
      ↓
Disruption Level Identified
      ↓
Auto Claim Decision (Partial / Full)
      ↓
Instant Payout
```

---

## System Architecture Overview

```
[Frontend (React)]
        ↓
[Backend API Layer]
        ↓
 ┌───────────────┬───────────────┬
 ↓               ↓               ↓
[Database]   [AI Engine]   [External APIs]
                               ↓
                    Weather / Govt Alerts
```

---

## AI Risk Profiling Engine (Core)

### DRS Formula

```
DRS = (Environmental Risk + Zone Risk + Work Dependency) / 3
```

### Components

| Factor | Description |
|--------|------------|
| Environmental Risk | Rain, heat, pollution |
| Zone Risk | Traffic, strikes |
| Work Dependency | Full-time vs part-time |

---

## AI Decision Models

### Model 1: Worker Disruption Index (WDI)

**Purpose → Determine payout level**

```
WDI = (0.35 × R) + (0.25 × A) + (0.2 × T)
```

| WDI Score | Action |
|----------|--------|
| 0–30 | No payout |
| 30–60 | Partial payout |
| 60–100 | Full payout |

---

### Example Scenarios

**Heavy Rain**

```
Rain = 90, AQI = 40, Temp = 35
WDI = 48.5 → Partial payout
```

**Extreme Heat + AQI**

```
Rain = 10, AQI = 85, Temp = 80
WDI = 40.75 → Partial payout
```

**Severe Conditions**

```
Rain = 80, AQI = 90, Temp = 85
WDI = 67.5 → Full payout
```

---

### Model 2: Risk-Based Pricing

| Risk Level | Weekly Premium |
|-----------|---------------|
| Low | ₹10 |
| Medium | ₹20 |
| High | ₹40 |

---

### Model 3: Fraud Detection

• High claim frequency → flag  
• Weather mismatch → reject  
• Location mismatch → flag  

---

## Weekly Premium Model

```
Weekly Premium = Base + (DRS × Risk Factor) - Stability Discount
```

---

## Coverage Model

```
Coverage = Avg Daily Income × Disruption Days
```

---

## Parametric Trigger Engine

| Trigger | Condition |
|--------|----------|
| Rain | >50mm |
| Heat | >42°C |
| Curfew | Govt alert |

---

## Automatic Claim Engine

```
IF trigger detected  
AND user active in zone  
→ Auto payout initiated
```

---

## Fraud Detection System

• GPS validation  
• Activity verification  
• Duplicate prevention  

---

## Payout System

• UPI transfer (mock)  
• Wallet credit  

---

## Dashboards

**User:** Premium, Risk, Claims  
**Admin:** Users, Payouts, Fraud alerts  

---

## Platform Strategy

Web-first, API-driven architecture  

✔ No install required  
✔ Works on low-end devices  
✔ Easily scalable  

---

## Tech Stack

| Layer | Technology | Purpose |
|------|-----------|--------|
| Frontend | React.js, Bootstrap | Build responsive user interface |
| Backend | Node.js, Express.js | API development and business logic |
| Database | MongoDB (Atlas) | Store users, policies, claims |
| AI Logic | Rule-based models (DRS, WDI) | Risk scoring and decision making |
| APIs | Weather API, AQI API, Maps API | Real-time environmental data |
| Payments | Razorpay (Test Mode) | Simulated payout system |
| Authentication | JWT | Secure user sessions |
| Deployment | Vercel, Render | Hosting frontend and backend |
| Version Control | GitHub | Code management |
---

## Development Plan

### Phase 1 (Completed)

✔ Research  
✔ System design  
✔ Risk + pricing models  
✔ Architecture setup  
✔ Base code ready  

⏳ Prototype in progress  

---

### Phase 2

⏳ Full MVP development  
⏳ API integration  
⏳ Claim automation  

---

### Phase 3

⏳ ML + fraud detection  
⏳ Dashboard + scaling  

---

## Why InsuRevive

✔ Real problem  
✔ Automated system  
✔ AI-driven decisions  
✔ Scalable solution  

---
## Team

**Team Name:** InsuRevive  

**Members:**

• Likhitha  
• Rishika  
• Vignesh  
• Rithwik 

---

## Final Pitch

> **“InsuRevive ensures that when deliveries stop, income doesn’t.”**
