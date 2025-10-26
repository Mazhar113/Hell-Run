# 🔥 HELLRUN – Multiplayer Survival Game

[![Build Status](https://github.com/Mazhar113/HELLRUN/actions/workflows/unity-versioned-release.yml/badge.svg)](https://github.com/Mazhar113/HELLRUN/actions/workflows/unity-versioned-release.yml)  
[![Unity Version](https://img.shields.io/badge/Unity-2023.2.0f1-blue)](https://unity.com/releases/editor/whats-new/2023.2.0)  
[![Latest Release](https://img.shields.io/github/v/release/Mazhar113/HELLRUN?label=latest%20release)](https://github.com/Mazhar113/HELLRUN/releases/latest)  
[![License](https://img.shields.io/github/license/Mazhar113/HELLRUN)](https://github.com/Mazhar113/HELLRUN/blob/main/LICENSE)

**HELLRUN** is a 3D multiplayer survival game inspired by *PUBG* and *Squid Game*.  
Every level is a deadly challenge — once you enter, it feels like hell, and only the smartest, fastest, and most strategic players survive.

---

## 🕹️ **Game Overview**

- Genre: 3D Survival / Multiplayer Battle  
- Platforms: **PC, Mobile (Android), WebGL**  
- Engine: **Unity 2023 LTS**  
- Mode: **Team vs Team Battle & Solo Survival**  
- Multiplayer: **Photon Fusion / Unity Netcode**  
- Monetization: In-game currency, ads, premium skins, season passes

---

## 🎮 **Gameplay**

- Players spawn in a mysterious arena filled with traps, fire, and dynamic challenges.  
- Each level introduces new physics-based puzzles, combat arenas, or chase sequences.  
- Teams must collaborate to survive while eliminating enemy squads.  
- Every victory earns **HELL COINS** that unlock skins, weapons, and power-ups.

---

## ⚙️ **Tech Stack**

| Component | Technology |
|------------|-------------|
| **Game Engine** | Unity 2023 LTS |
| **Multiplayer** | Photon PUN / Fusion |
| **Scripting** | C# |
| **Backend** | PlayFab / Firebase (optional) |
| **Analytics** | Unity Analytics + ML models (churn prediction, LTV estimation) |
| **AI Models** | Player segmentation, churn detection, recommendation system |
| **Build Targets** | Windows, WebGL, Android |

---

## 🧠 **Game AI and Data Science**

HELLRUN includes machine learning models to:

- Predict player **churn** and **lifetime value (LTV)**  
- Create **personalized recommendations** for store items and missions  
- Analyze player behavior to optimize difficulty and engagement

---

## 🚀 **Automatic Build and Release Workflow**

This repository includes a **GitHub Actions workflow** that automatically:

- Builds the project for **Windows**, **WebGL**, and **Android**  
- Runs **PlayMode tests**  
- Packages builds and creates **versioned releases** automatically

### Workflow Path

