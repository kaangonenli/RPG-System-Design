# RPG Systems Design & Data Architecture

![Focus](https://img.shields.io/badge/Focus-System_Design_%26_Localization-purple) ![Format](https://img.shields.io/badge/Data-JSON-yellow) ![Status](https://img.shields.io/badge/Status-Portfolio_Showcase-green)

This repository serves as a portfolio showcase demonstrating **Technical Game Design** capabilities. It bridges the gap between narrative concepts (Word/PDF) and game-ready data structures (JSON), featuring both D&D 5e localization and original IP development.

## Project Structure

| Module | File | Description |
| :--- | :--- | :--- |
| **Class Logic** | `data/classes.json` | D&D 5e classes adapted for Turkish localization, structuring progression tables into code. |
| **Race Data** | `data/races.json` | Relational data for Races & Subraces (e.g., Dwarf/Hill Dwarf) and traits. |
| **Quest System** | `data/campaign.json` | Converting *Lost Mine of Phandelver* narrative into a Quest State Machine logic. |
| **Original IP** | `data/custom_lore.json` | **Homebrew Design:** "Shorki" polymorphic race system and region-based background perks. |
| **Party Roster** | `data/characters.json` | Character data structure for a custom novel protagonist party (Maya, Ascal, Ashera). |

## Technical Highlights

### 1. Data Normalization (D&D 5e)
Converted static rule text into queryable JSON objects.
* **Challenge:** Different classes scale differently (e.g., Warlock Spell Slots vs. Rogue Sneak Attack Dice).
* **Solution:** Designed a flexible schema (`class_specific` object) to handle unique mechanics within a unified array.

### 2. Polymorphic Race Design (Original IP)
Designed the **"Shorki"** race architecture where sub-species (Felid, Testudine, Strigine) fundamentally alter gameplay stats (Speed, AC, Vision) rather than just adding flavor text.

### 3. Localization Engineering
Translated complex RPG terminology (e.g., *Saving Throw* -> *Kurtarma Atışı*) while preserving mathematical integrity and SRD 5.1 compliance.

---
**Author:** Kaan Gönenli  
*Technical Designer & Tool Developer*
