# Collapscension
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/f8cbbd90-b66d-423c-8222-0be72316d15d" />

## Project Overview
A single-file offline HTML idle incremental game, current build **V0.7 Beta High-Tech Update**.
Contains over 1700 lines of source code with a total file size of ~70KB. Built on decimal.js full-stack high-precision big number system to support astronomical values without precision loss.

Development workflow: I independently designed & coded the entire low-level framework, numerical rules, save system and shared utility functions. Repetitive logic such as max-buy functions for nuclear plants, AI compute clusters and Dyson Spheres are generated with AI assistance. The overall architecture is fully human-controlled, so this project is NOT pure Vibe Coding, but NOT easy for long-term iteration and maintenance.

## V0.7 Beta High-Tech Update
A closed-loop civilization tech tree. Power and computing power are permanent buffs instead of consumable resources, unlocking step-by-step to reach the ultimate stellar engineering of Type II Civilization.

### 1. Power System (Permanent Production Buff, Non-Consumable)
Power is a permanent energy multiplier system that **cannot be consumed by any building**, it only acts as an unlock prerequisite for advanced tech:
- Basic Power Facilities: Unlock early base Points energy generation, but boosts RP.
- Nuclear Energy Generation: Produce MASSIVE energy


### 2. The Computing Center (Compute Power)
Core stat display: **Compute! Computing power:x ... point**
- Compute Rule: Computing power does NOT consume power; power only works as an unlock requirement for AI buildings
- Function of Compute Power: Multiply global Points generation speed and drive star exploration progress
- Exclusive Feature: AI brings full-range automation mechanics, drastically cut down manual operations, auto-run resource generation & construction judgment logic.

### 3. Star Exploration
Consume computing power to expand total explored star systems `starsystems`. Every exploration raises the maximum build cap of Dyson Spheres, the only way to unlock more Dyson Sphere slots.

### 4. Dyson Sphere (Ultimate Stellar Building of This Version,Dyson Sphere mult Energy x1e20+)
Cost: `1.00e90 Points`, price never inflates or changes(It Will Buy Max,hardcapped by total `starsystems` limit)

### 5.QOL
Unlock 5 Autobuyers,every have 2 Stages.

### 6.Prestige Timer

Remember Your Last Prestige Record.

Test Update:V0.7 Alpha High-Tech 1/2 Update(Power System,The Computing Center,Star Exploration,Dyson Sphere)

## V0.6.1 Beta Research Update

### 1. Research Points
Upgrade Research Points(RP) and Research Levels.Research Levels Boosts Points.
3 Upgrades:
 - Science and Mathmatics: gain more Point base by You Purchased small molecule
 - Language: gain x5 more small molecule.`Cost: 1.00e14 Points`
 - Steam:Gain x100 more Research Points(and x10 atom gain).Cost:9.29e29
NOTE:The game is NOT AVAILABLE on Steam.
### 2. Achievements
Updated First 7 Achievements.
Every Achievements Has a x1.01 Boosts For All Basic Buildings.

### 3.Prestige Upgrades

3 Upgrades:
 - Offline Progress I:when you were away,get 5% Of your offline progress.Cost:10PP
 - Double Boost:Gain 2.5x of Point and PP.Cost:15PP
 - Multi-Dimensions PP Gain:PP Also gains atom and small molecule.Cost:30PP
 

## High-Precision Big Number Backend System
Unified be.js chain operation standards for all resources, compute power, building counts and star system caps:
- Utility Functions: `pad()` zero-padding formatter, `formatDuration()` standardized millisecond time display
- Save Import/Export
- Full scientific notation rendering, fully support values up to ee308 and above

## Lightweight Single-File Architecture
All game logic, UI rendering, high-tech numerical system and utility functions are packed into one standalone `index.html`. No bundlers, backend servers or local libraries required; only decimal.js loaded via CDN. Simply open with any browser to play offline.

## How To Run
1. Get the main file `index.html`
2. Open directly with modern browsers including Chrome / Edge / Firefox
3. Unlock Power, Nuclear Plants, Information Tech and AI Compute step by step. Spend compute power to expand star systems, then mass-produce Dyson Spheres.
4. Real-time UI display: Current compute power, total explored star systems, Dyson Sphere owned/cap, fixed cost and global production multiplier.

## Project Info
- Current Version: V0.7 Beta | High-Tech Update
- Total Lines of Code: 1700+
- File Size: ~70KB(not included be.js)
- Core Dependency: be.js(break_eternity.js)

## Future Update Roadmap
1. Inflation Upgrades(V0.7.x)
2. Infinity Point(V0.1)
3. Infinty █████████
4. ████████ Prestige layer
NOTE:THE ORIGINAL README IS WRITTEN BY AI
