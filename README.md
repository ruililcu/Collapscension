# Collapscension V0.7 Beta High-Tech Update
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/f8cbbd90-b66d-423c-8222-0be72316d15d" />

## Project Overview
A single-file offline HTML idle incremental game, current build **V0.7 Beta High-Tech Update**.
Contains over 1700 lines of source code with a total file size of ~70KB. Built on decimal.js full-stack high-precision big number system to support astronomical values without precision loss.

Development workflow: I independently designed & coded the entire low-level framework, numerical rules, save system and shared utility functions. Repetitive logic such as max-buy functions for nuclear plants, AI compute clusters and Dyson Spheres are generated with AI assistance. The overall architecture is fully human-controlled, so this project is NOT pure Vibe Coding, but NOT easy for long-term iteration and maintenance.

## Complete High-Tech Progression Chain (V0.7 Beta): Power → Nuclear Plant → Information Tech → AI Compute → Star Exploration → Dyson Sphere
A closed-loop civilization tech tree. Power and computing power are permanent buffs instead of consumable resources, unlocking step-by-step to reach the ultimate stellar engineering of Type II Civilization.

### 1. Power System (Permanent Production Buff, Non-Consumable)
Power is a permanent energy multiplier system that **cannot be consumed by any building**, it only acts as an unlock prerequisite for advanced tech:
- Basic Power Facilities: Unlock early base Points energy generation, lay the foundation of civilization energy supply
- Nuclear Plants: Massively boost global power multiplier, serve as threshold to unlock Information Tech and AI automation
- Core Rule: Power is a permanent passive bonus with zero consumption after construction.

### 2. Information Technology Cluster
Pre-tech unlocked by power threshold. Boost basic energy generation efficiency and act as prerequisite to unlock AI Supercomputing Centers.

### 3. AI Supercomputing Center (Compute Power)
Core stat display: **Compute! Computing power:x ... point**
- Compute Rule: Computing power does NOT consume power; power only works as an unlock requirement for AI buildings
- Function of Compute Power: Multiply global Points generation speed and drive star exploration progress
- Exclusive Feature: AI brings full-range automation mechanics, drastically cut down manual operations, auto-run resource generation & construction judgment logic.

### 4. Star Exploration
Consume computing power to expand total explored star systems `starsystems`. Every exploration raises the maximum build cap of Dyson Spheres, the only way to unlock more Dyson Sphere slots.

### 5. Dyson Sphere (Ultimate Stellar Building of This Version)
- Fixed Constant Cost: `1.00e90 Points`, price never inflates or changes
- One-Click Max Buy Function: Automatically calculate affordable quantity based on current resources & empty star slots, hard capped by total `starsystems` limit
- Permanent Buff: Dyson Sphere mult Energy x1e20+

## High-Precision Big Number Backend System
Unified be.js chain operation standards for all resources, compute power, building counts and star system caps:
- Utility Functions: `pad()` zero-padding formatter, `formatDuration()` standardized millisecond time display
- Save Export Function `Export()`: Serialize all ultra-large numerical values, reserve complete extension interface for save import
- Full scientific notation rendering, fully support values up to 1e90 and above, eliminate native JavaScript Number precision loss completely.

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
- File Size: ~70KB
- Core Dependency: decimal.js (Loaded from CDN online)

## Future Update Roadmap
1. Branch star exploration tiers to unlock higher star system caps
2. Expand AI automation features: offline production income, auto mass construction
3. Complete save import function to support full progress load
4. Add advanced stellar structures: Dyson Ring, Dyson Swarm
5. Multi-tier compute power upgrades for extra global production multipliers
