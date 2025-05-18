Here’s your **1-Week Bootcamp Course: Phase 3 – RPG Systems Development**, designed to teach and walk you through everything in **seven focused days** with direct links to tutorials, articles, and tasks.

---

# 🧙‍♂️ **Unity RPG Systems Bootcamp (Phase 3)**

**Goal:** Build modular, scalable RPG systems in Unity by creating a sandbox vertical slice: ***Kingdom of Emberlight***

---

## Day 1 – Character Controller & Input {#day1}

### ✅ Objectives

* Create a modular player controller
* Add movement, dash, jump, and interaction logic

### 📚 Tutorials

* ▶️ [Player Movement (Top-down 2D) – 8 min](https://youtu.be/wGi3D8TQuqY)
* ▶️ [Interaction System – 10 min](https://youtu.be/2pzxDg3u7aQ)
* ▶️ [Dash / Double Tap Input – 12 min](https://youtu.be/0ovgTdoHcHw)

---

## Day 2 – Combat System & FSM AI {#day2}

### ✅ Objectives

* Create a melee + ranged combat system
* Build AI enemies using finite state machines

### 📚 Tutorials

* ▶️ [Melee Combat – 11 min](https://youtu.be/WRzjF_YjHpM)
* ▶️ [Ranged Attacks – 9 min](https://youtu.be/pPU2K0VI7dk)
* ▶️ [FSM Enemy AI (Idle → Patrol → Chase → Attack) – 15 min](https://youtu.be/j8_w3h5YPxw)

---

## Day 3 – Inventory & Equipment {#day3}

### ✅ Objectives

* Pick up, equip, and use items
* Implement inventory UI and item effects

### 📚 Tutorials

* ▶️ [Inventory System Basics – 16 min](https://youtu.be/vxG3pV8v1jY)
* ▶️ [ScriptableObjects for Items – 10 min](https://youtu.be/SI0M9EvvF28)
* ▶️ [Equip Weapons/Armor – 14 min](https://youtu.be/ZL1IpnRzr1s)

---

## 📅 Day 4 – Quests & Dialogue

### ✅ Objectives

* Add dialogue system
* Create multi-step quests that track progress and give rewards

### 📚 Tutorials

* ▶️ [Quest System with Tracking – 12 min](https://youtu.be/zU2a7BKHd70)
* ▶️ [Dialogue with Yarn Spinner – 20 min](https://youtu.be/OUKz1EybD68)
* ▶️ [Triggering Dialogue from Interact – 8 min](https://youtu.be/IfqOtPZK9mA)

---

## 📅 Day 5 – XP, Leveling, Skill Tree

### ✅ Objectives

* Add XP, leveling up, and unlockable skills

### 📚 Tutorials

* ▶️ [XP and Leveling System – 14 min](https://youtu.be/GHJeW8l9uNo)
* ▶️ [Skill Tree with UI – 18 min](https://youtu.be/s72Z9IYLZfw)

---

## 📅 Day 6 – Save/Load System + World Interaction

### ✅ Objectives

* Implement saving with PlayerPrefs or JSON
* Add doors, chests, and NPCs with meaningful interaction

### 📚 Tutorials

* ▶️ [Save/Load JSON System – 10 min](https://youtu.be/I6_j3Xbm6fA)
* ▶️ [Persistent Data with PlayerPrefs – 8 min](https://youtu.be/Yh6Uj1hQ8nE)
* ▶️ [Interactive Doors/Chests/NPCs – 13 min](https://youtu.be/xT2BB8uIpJ4)

---

## 📅 Day 7 – Final Assembly & Polish

### ✅ Objectives

* Connect systems into one scene
* Add animations, transitions, and polish the experience

### 📚 Tutorials

* ▶️ [Cutscenes with Timeline – 10 min](https://youtu.be/9nT1Zi1hb5k)
* ▶️ [Fade Scene Transitions – 6 min](https://youtu.be/q2fKkJzOqGc)
* ▶️ [Sound Design & Polish – 9 min](https://youtu.be/sQZ5_ZF9zYY)

---

## 🔧 Folder/File Structure

```plaintext
/Assets
  /Scripts
    /Player
    /Combat
    /Enemies
    /Inventory
    /Quests
    /Dialogue
    /SaveSystem
    /UI
  /Prefabs
    /Items
    /NPCs
    /Enemies
  /ScriptableObjects
    /Items
    /Skills
    /Quests
    /NPCs
  /Scenes
    /Village
    /CombatArea
    /BossRoom
```

---

## 🧠 Tools Used

| Tool               | Purpose                   |
| ------------------ | ------------------------- |
| Unity (URP)        | Rendering pipeline        |
| ScriptableObjects  | Items, quests, XP, skills |
| FSM via C#         | AI states, player states  |
| Yarn Spinner / Ink | Dialogue branching        |
| NavMesh            | Optional pathfinding      |
| Timeline           | Cutscenes + boss intros   |
| JSON / PlayerPrefs | Saving system             |

---

## 🏁 Outcome

By the end of this bootcamp, you’ll be able to:

* Architect fully modular RPG systems
* Scale features like inventory, quests, and leveling
* Use FSM, MVC/MVP, and Event-Driven patterns effectively
* Prototype an entire RPG in Unity with clean, maintainable systems
