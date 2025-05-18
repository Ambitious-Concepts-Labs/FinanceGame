Here's your **Phase 8: Post-Launch Maintenance** transformed into a **1-Week Unity Bootcamp Course**, complete with focused daily walkthroughs, short tutorials, and hands-on tasks. You’ll learn how to maintain, scale, and monetize your live game like a pro using *Astralore: Live Ops Demo* as your final live service simulation project.

---

# 🛠️ Unity Bootcamp – Phase 8: **Post-Launch Maintenance**

**Project:** *Astralore: Live Ops Demo*
**Goal:** Learn to run your Unity game as a live product — with updates, events, feedback tracking, and optional monetization.

---

## 🔗 Quick Navigation

- [🛠️ Unity Bootcamp – Phase 8: **Post-Launch Maintenance**](#️-unity-bootcamp--phase-8-post-launch-maintenance)
  - [🔗 Quick Navigation](#-quick-navigation)
  - [📅 Day 1 – Feedback System + Bug Fix Flow](#-day-1--feedback-system--bug-fix-flow)
    - [✅ Goals:](#-goals)
    - [📚 Tutorials:](#-tutorials)
    - [🛠 Tasks:](#-tasks)
  - [📅 Day 2 – Addressables \& Content Updates](#-day-2--addressables--content-updates)
    - [✅ Goals:](#-goals-1)
    - [📚 Tutorials:](#-tutorials-1)
    - [🛠 Tasks:](#-tasks-1)
  - [📅 Day 3 – Seasonal Events with Date Triggers](#-day-3--seasonal-events-with-date-triggers)
    - [✅ Goals:](#-goals-2)
    - [📚 Tutorials:](#-tutorials-2)
    - [🛠 Tasks:](#-tasks-2)
  - [📅 Day 4 – Monetization with Unity IAP](#-day-4--monetization-with-unity-iap)
    - [✅ Goals:](#-goals-3)
    - [📚 Tutorials:](#-tutorials-3)
    - [🛠 Tasks:](#-tasks-3)
  - [📅 Day 5 – Cosmetic Store + DLC Content](#-day-5--cosmetic-store--dlc-content)
    - [✅ Goals:](#-goals-4)
    - [📚 Tutorials:](#-tutorials-4)
    - [🛠 Tasks:](#-tasks-4)
  - [📅 Day 6 – Analytics, Retention \& Revenue Tracking](#-day-6--analytics-retention--revenue-tracking)
    - [✅ Goals:](#-goals-5)
    - [📚 Tutorials:](#-tutorials-5)
    - [🛠 Tasks:](#-tasks-5)
  - [📅 Day 7 – Live Ops Simulation \& Weekly Patch Plan](#-day-7--live-ops-simulation--weekly-patch-plan)
    - [✅ Goals:](#-goals-6)
    - [📚 Tutorials:](#-tutorials-6)
    - [🛠 Tasks:](#-tasks-6)
  - [📁 Suggested Additions to Project Structure](#-suggested-additions-to-project-structure)
  - [🧠 Tools \& Services You’ll Practice](#-tools--services-youll-practice)
  - [🎯 By the End of This Bootcamp, You Will:](#-by-the-end-of-this-bootcamp-you-will)

---

## Day 1 – Feedback System + Bug Fix Flow {#day1}

### ✅ Goals:

* Set up feedback collection and start patch workflow

### 📚 Tutorials:

* ▶️ [Unity In-Game Feedback Form (via Google Forms) – 8 min](https://youtu.be/XrcFOZGYA2k)
* ▶️ [Git Branches for Hotfixes – 6 min](https://youtu.be/pQY4nQzZq8Y)

### 🛠 Tasks:

* Add in-game feedback button that opens Discord or Google Form
* Create `v1.0.1` patch branch
* Add 1 UI bugfix or stat-balancing change
* Build and export as `v1.0.1`

---

## Day 2 – Addressables & Content Updates {#day2}

### ✅ Goals:

* Add post-launch content via Addressables

### 📚 Tutorials:

* ▶️ [Unity Addressables Quickstart – 10 min](https://youtu.be/_Z1eL1_lBgw)
* ▶️ [Load Content Dynamically – 8 min](https://youtu.be/_9QZtCDWqCg)

### 🛠 Tasks:

* Install and configure Addressables
* Create a new biome or quest as an `Addressable`
* On login, load content from remote Addressable server

---

## Day 3 – Seasonal Events with Date Triggers {#day3}

### ✅ Goals:

* Build a seasonal event system using real-world dates

### 📚 Tutorials:

* ▶️ [Unity Date-Based Events – 6 min](https://youtu.be/b0WYdGlX6LE)
* ▶️ [Enable Limited-Time Skins – 7 min](https://youtu.be/RHUaTg38cEo)

### 🛠 Tasks:

* Create `EventManager.cs` that checks `System.DateTime.Now`
* Activate Halloween skin or XP boost if it’s October
* Toggle splash screen/banner dynamically

---

## Day 4 – Monetization with Unity IAP {#day4}

### ✅ Goals:

* Add consumable IAP (gold pack) or unlock (premium zone)

### 📚 Tutorials:

* ▶️ [Unity IAP Full Setup – 12 min](https://youtu.be/2qx6fBbVBHo)
* ▶️ [Secure IAP Transactions – 8 min](https://youtu.be/yAETvU8LF6g)

### 🛠 Tasks:

* Add Unity IAP via Package Manager
* Create a `PurchaseManager.cs` for 1 product (`com.astralore.goldpack1`)
* Add UI to test purchase with sandbox/test account
* Store purchase data linked to Firebase UID or playerPrefs

---

## Day 5 – Cosmetic Store + DLC Content {#day5}

### ✅ Goals:

* Add a store UI for cosmetic items or bonus content

### 📚 Tutorials:

* ▶️ [In-Game Skin Shop – 9 min](https://youtu.be/QVLxkZY7tNc)
* ▶️ [Steam DLC Detection – 6 min](https://youtu.be/MAo-iX9O6vY)

### 🛠 Tasks:

* Add store screen with 1–2 skins for in-game currency or real money
* Use `ScriptableObjects` for items (`SkinData`)
* For Steam: Check if DLC is installed and unlock extra region/quest

---

## Day 6 – Analytics, Retention & Revenue Tracking {#day6}

### ✅ Goals:

* Add event tracking and revenue analysis tools

### 📚 Tutorials:

* ▶️ [Firebase Analytics Setup in Unity – 10 min](https://youtu.be/vNe42Uunb_M)
* ▶️ [Track IAP + Session Duration – 7 min](https://youtu.be/UFOsFM3-NPQ)

### 🛠 Tasks:

* Log events like:

  * Session start
  * Quest completed
  * Purchase made
* Track revenue via Firebase or local logs
* Output `ARPU` and `Retention` metrics into debug console or custom dashboard

---

## Day 7 – Live Ops Simulation & Weekly Patch Plan {#day7}

### ✅ Goals:

* Simulate real post-launch workflow

### 📚 Tutorials:

* ▶️ [Game LiveOps Best Practices – 8 min](https://youtu.be/80l7ZxgTy5Y)
* ▶️ [How to Run a Live Game – 12 min](https://youtu.be/AWR4l6zm90g)

### 🛠 Tasks:

* Schedule 3 weekly events (e.g., bonus XP weekend, limited-time skin)
* Create a `patch-notes.json` and display it in-game
* Mock 1 week of operation:

  * Feedback → Bugfix → IAP Sale → Seasonal Event
* Deliver final “Live Demo Build” of *Astralore*

---

## 📁 Suggested Additions to Project Structure

```plaintext
/Assets
  /LiveOps
    EventManager.cs
    SeasonalAssets/
  /IAP
    ProductConfig.cs
    PurchaseManager.cs
  /Addressables
    RemoteAssets/
      NewQuest/
      HalloweenSkin/
  /Analytics
    RevenueTracker.cs
    PlayerEvents.cs
```

---

## 🧠 Tools & Services You’ll Practice

| Tool                               | Use                                   |
| ---------------------------------- | ------------------------------------- |
| **Unity IAP**                      | In-app purchases                      |
| **Unity Addressables**             | Post-launch content delivery          |
| **Remote Config / JSON**           | Feature flags or patch display        |
| **Firebase Analytics**             | Session tracking, purchase logging    |
| **Sentry or Crashlytics**          | Post-launch error tracking            |
| **OBS / Unity Recorder**           | Marketing content (screenshots/video) |
| **Trello / Notion / Google Forms** | Feedback collection and task triage   |

---

## 🎯 By the End of This Bootcamp, You Will:

✅ Track and fix bugs after launch using real-world workflows
✅ Release new content dynamically without rebuilding
✅ Run seasonal or time-sensitive live events
✅ Monetize with Unity IAP and cosmetic stores
✅ Analyze revenue, retention, and behavior with Firebase
✅ Maintain and grow your game with a long-term operations mindset

---