# Battlecard: Honeywell B2M / Operational Intelligence vs SOTI

**Last Updated:** 2026-02-18
**Competitor:** Honeywell Operational Intelligence (powered by B2M Solutions / Elemez)
**Type:** Mobile Analytics & DEX Platform (NOT a full MDM)
**Threat Level:** Medium (Analytics competitor, not management competitor)

---

## 1. What is Honeywell B2M?

**B2M Solutions** (UK-based, founded 2002) provides **Elemez** — a Mobile Digital Employee Experience (DEX) platform. Honeywell OEMs this as **"Operational Intelligence"** for their devices.

**Key Point:** This is an **analytics/monitoring tool**, NOT an MDM. It tells you *what's wrong* but can't *fix it*.

### Honeywell + Samsung Partnership (2026)
Honeywell announced B2M support for **Samsung rugged devices** (XCover, Tab Active). This is a "co-opetition" play — Honeywell provides analytics for Samsung hardware they don't make.

---

## 2. SOTI vs Honeywell OpIntel: Quick Comparison

| Capability | SOTI (MobiControl + XSight) | Honeywell OpIntel (B2M) |
|:-----------|:----------------------------|:------------------------|
| **MDM/Management** | ✅ Full MDM | ❌ Analytics only |
| **Remote Control** | ✅ Industry-leading (Samsung) | ❌ None |
| **App Deployment** | ✅ Full lifecycle | ❌ None |
| **Device Analytics** | ✅ XSight (predictive) | ✅ Elemez (monitoring) |
| **OS Updates** | ✅ E-FOTA control | ❌ Monitoring only |
| **Security Policies** | ✅ Kernel-level | ❌ None |
| **Samsung Knox** | ✅ Day-zero via KSP | ⚠️ Limited visibility |
| **Pricing Model** | Quote-based | Per-device subscription |

**Bottom Line:** Honeywell OpIntel is a **point solution** for analytics. SOTI is a **platform** for management + analytics + support.

---

## 3. Kill Shots (Where SOTI Wins)

### Kill Shot #1: "They See Problems, We Fix Problems"
```
"OpIntel is like a smoke detector — it tells you there's a fire.
SOTI XSight is the fire department — we come in and put it out."
```
**Use When:** Customer asks about OpIntel's device health dashboards.
**Counter:** OpIntel can tell you a device has a failing battery. SOTI can push a profile to disable that device and redirect the user to a swap station.

### Kill Shot #2: "Analytics Without Control is Useless"
```
"What do you DO with the data OpIntel gives you?
You still need an MDM to act on it. SOTI is the MDM AND the analytics."
```
**Use When:** Customer is considering OpIntel as a standalone purchase.
**Counter:** Every OpIntel deployment requires an MDM anyway. Why pay for two platforms when SOTI does both?

### Kill Shot #3: "Remote Control is Non-Negotiable"
```
"OpIntel can report that a frontline worker's device is frozen.
SOTI can remote in and fix it in 30 seconds without a truck roll."
```
**Use When:** Customer has distributed workforce / field service.
**Counter:** Calculate the cost of one truck roll ($150-300). SOTI pays for itself on the first remote fix.

### Kill Shot #4: "Samsung Devices = SOTI Territory"
```
"OpIntel has 'support' for Samsung. SOTI has INTEGRATION with Samsung.
We're a Samsung Premier Partner with Knox day-zero support."
```
**Use When:** Customer is deploying Samsung XCover/Tab Active devices.
**Counter:** SOTI has KME, KSP, E-FOTA, and remote control that OpIntel can't match on Samsung.

---

## 4. Vulnerabilities (Where We Lose)

### Vulnerability #1: Honeywell Shop Already Committed
**Scenario:** Customer is 100% Honeywell hardware and already uses Honeywell's ecosystem.
**Counter:** Don't fight it. Position SOTI as the *management layer* under OpIntel. "OpIntel for visibility, SOTI for control."

### Vulnerability #2: Price-Sensitive Analytics-Only Buyer
**Scenario:** Customer just wants battery health dashboards, doesn't need full MDM.
**Counter:** Show XSight analytics. "If you're going to buy analytics, get the platform that comes with MDM included."

### Vulnerability #3: "Good Enough" Monitoring
**Scenario:** Customer already has an MDM (Intune, Jamf) and just wants device health.
**Counter:** This is the dangerous one. Focus on remote control value. "Your MDM can't remote into a frozen device. We can."

---

## 5. Sales Scripts by Scenario

### Scenario A: Customer Considering OpIntel for Samsung Fleet
```
REP: "I see you're looking at OpIntel for your Samsung devices. 
     Quick question — how are you planning to actually MANAGE those devices?"

[Let them answer]

REP: "Here's the thing — OpIntel is great at telling you what's happening.
     But when a device freezes in the field, who fixes it?

     SOTI doesn't just monitor. We remote in and solve the problem.
     Same dashboard. One platform. Lower cost."

CLOSE: "Let me show you a 2-minute demo of remote control on a Samsung device."
```

### Scenario B: Customer Has OpIntel, Shopping for MDM
```
REP: "Perfect — you already have visibility with OpIntel.
     Now you need control. SOTI MobiControl is the engine that 
     lets you ACT on everything OpIntel shows you.

     The question is: do you want two vendors or one?
     SOTI XSight gives you the same analytics PLUS the MDM."

CLOSE: "Let's do a side-by-side of XSight vs OpIntel dashboards."
```

### Scenario C: Customer Comparing Total Cost
```
REP: "Let's talk TCO. OpIntel charges per device for analytics.
     Then you need an MDM on top — that's two contracts, two vendors,
     two support teams.

     SOTI gives you MDM + analytics + remote support in one platform.
     One contract. One throat to choke."

MATH: "OpIntel: $X/device × 1000 devices = $X,000
       MDM: $Y/device × 1000 devices = $Y,000
       Total: $(X+Y),000

       SOTI: $Z/device × 1000 devices = $Z,000 (everything included)
       Savings: 20-30%"
```

---

## 6. Quick Reference Card

| Customer Says | You Say |
|:--------------|:--------|
| "OpIntel gives us device health" | "And we give you the power to fix it remotely" |
| "We already have OpIntel" | "Great — now add the MDM that completes it" |
| "OpIntel supports Samsung" | "SOTI INTEGRATES with Samsung. Day-zero KSP support" |
| "OpIntel is cheaper" | "OpIntel is analytics-only. You still need an MDM. We're both." |
| "We just need monitoring" | "Monitoring without control is a smoke alarm without a fire department" |

---

## 7. B2M Solutions Background (For Reference)

**Company:** B2M Solutions Ltd (UK)
**Founded:** 2002
**Product:** Elemez (Mobile DEX platform)
**Honeywell OEM Name:** Operational Intelligence
**Model:** Cloud SaaS, agent-based
**Limitation:** Analytics only — no MDM, no remote control, no security policies

**Key Insight:** B2M is a 20-year-old niche player. Honeywell is their biggest OEM. Without Honeywell, they have limited enterprise presence.

---

## 8. Competitive Positioning Summary

**Honeywell OpIntel is:**
- ✅ Good at: Battery health, app performance monitoring, crash analytics
- ❌ Bad at: Everything that requires ACTION (remote control, deployment, security)
- ⚠️ Risk: Creates "visibility without control" trap for customers

**SOTI Position:**
- "We see what they see AND we can fix it remotely"
- "One platform, not two"
- "Samsung Premier Partner — deeper integration than OpIntel can ever have"

---

**Bottom Line for Sales:**
> Honeywell OpIntel is a point solution. Don't fight it — position SOTI as the platform that *completes* it. If they're buying analytics, they need management. We're both.

---

*Sources: B2M Solutions website, Honeywell product documentation, Samsung partnership announcement (2026)*
