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

### Delivery Partner – Ravi

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

### Case Study 1: Ravi (Full-Time Worker)

| Scenario | Without InsuRevive | With InsuRevive |
|---------|------------------|----------------|
| Heavy Rain (3 days) | No income | Auto-trigger detected |
| Earnings | ₹0 | ₹2400 payout |
| Action Required | None / Loss absorbed | No action needed |
| Financial Impact | High loss | Income protected |

**System Flow:**

Ravi starts his week →  
Risk score (DRS) calculated →  
Weekly premium generated →  
Rainfall exceeds threshold →  
Trigger activated →  
Auto payout credited →  
Income stability maintained  

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
Weekly Plan Generated
      ↓
Live Monitoring Engine
      ↓
Trigger Detected?
      ↓
Auto Claim Engine
      ↓
Payout System
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

### Example

```
Env = 70
Zone = 60
Work = 90

DRS = 73.3 → High Risk
```

---

## Weekly Premium Model

### Formula

```
Weekly Premium = Base + (DRS × Risk Factor) - Stability Discount
```

### Parameters

| Component | Value |
|----------|------|
| Base | ₹50 |
| Risk Factor | ₹2 |
| Discount | ₹10–₹30 |

### Example

```
DRS = 70 → Risk Cost = 140

Premium = 50 + 140 - 30 = ₹160/week
```

---

## Coverage Model

```
Coverage = Avg Daily Income × Disruption Days
```

Example:

```
₹800 × 3 = ₹2400 payout
```

---

## Parametric Trigger Engine

No manual claims required.

| Trigger | Condition | Source |
|--------|----------|--------|
| Rain | >50mm | Weather API |
| Heat | >42°C | Weather API |
| Curfew | Govt alert | Alerts API |

---

## Automatic Claim Engine

```
IF trigger detected  
AND user active in zone  
→ Auto payout initiated
```

---

## Fraud Detection System

### Phase 1 (Rule-Based)

• GPS validation  
• Work activity verification  
• Duplicate claim prevention  

### Future Enhancements

• Behavior anomaly detection  
• Risk pattern scoring  

---

## Payout System

• UPI transfer (mock)  
• Wallet credit system  

---

## Dashboards

### User Dashboard

• Weekly premium  
• Risk score  
• Claims history  

### Admin Dashboard

• Total users  
• Total payouts  
• Fraud alerts  

---

## Platform Strategy & Justification

### Web-First, API-Driven Architecture

We adopt a **web-first approach** for speed and accessibility.

### Why this works

✔ No installation required  
✔ Works on low-end devices  
✔ Faster development cycle  
✔ Easily extendable to:

→ Mobile app  
→ WhatsApp interface  

### Design Philosophy

**Start lightweight → Scale intelligently**

---

## Detailed Tech Stack

### Frontend

| Component | Technology |
|----------|-----------|
| Framework | React.js |
| Styling | Bootstrap |
| State | Context API |
| UI | Responsive Design |

---

### Backend

| Component | Technology |
|----------|-----------|
| Runtime | Node.js |
| Framework | Express.js |
| API | REST |
| Auth | JWT |

---

### AI / ML Layer

| Component | Approach |
|----------|----------|
| Risk Scoring | Rule-based (Phase 1) |
| Pricing | Formula-driven |
| Fraud Detection | Rule engine |
| Future | ML models (anomaly detection) |

---

### Database

| Component | Technology |
|----------|-----------|
| Database | MongoDB |
| Hosting | MongoDB Atlas |
| Collections | Users, Policies, Claims |

---

### External Integrations

| Service | Purpose |
|--------|--------|
| Weather API | Environmental triggers |
| Maps API | Location validation |
| Govt Alerts API | Disruption detection |
| Razorpay | Payment simulation |

---

### Deployment (Planned)

• Frontend → Vercel  
• Backend → Render / Railway  
• Database → MongoDB Atlas  

---

## Development Plan

### Phase 1: Ideation & Foundation

```
Week 1:
- Problem Research
- Persona Design
- Market Analysis

Week 2:
- Workflow Design
- Risk Model (DRS)
- Premium Logic
- README + Pitch Video
```

---

### Phase 2: Build & Integration

```
Frontend UI → Backend APIs → Database Setup
        ↓
Trigger Integration → Claim Engine → Payout System
```

---

### Phase 3: Intelligence & Scaling

```
ML Integration → Fraud Detection Upgrade
        ↓
Advanced Dashboard → Real-Time Monitoring
        ↓
Scalability Improvements
```

---

## Why InsuRevive

✔ Solves a real, underserved problem  
✔ Introduces income-based insurance  
✔ Eliminates claim friction  
✔ Uses AI meaningfully  
✔ Designed for scalability  

---

## Final Pitch

> **“InsuRevive ensures that when deliveries stop, income doesn’t.”**
