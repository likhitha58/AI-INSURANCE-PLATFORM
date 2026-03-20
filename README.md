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

**System Flow:**

• Vinod starts his work week  
• System calculates DRS (risk profile)  
• Weekly premium is generated  
• Rainfall exceeds trigger threshold  
• Parametric trigger activates automatically  
• Claim is processed without user input  
• Payout is credited instantly  

**Outcome → Income stability maintained**

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

## Impact Summary

| Metric | Without System | With InsuRevive |
|-------|--------------|----------------|
| Income Stability | Unpredictable | Protected |
| Claim Process | Manual / None | Automated |
| Response Time | Delayed | Instant |
| User Effort | High | Zero |

---

## Key Insight

Traditional insurance reacts **after loss**.  
**InsuRevive acts at the moment of disruption.**

> This transforms insurance from reactive protection → proactive income security.

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

Frontend → React + Bootstrap  
Backend → Node.js + Express  
Database → MongoDB  
APIs → Weather + Alerts  
Payments → Razorpay (mock)  

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

## Final Pitch

> **“InsuRevive ensures that when deliveries stop, income doesn’t.”**
