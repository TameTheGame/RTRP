# RefugeeRP - Real Time Roleplay Gamemode

**A Half-Life 2 Roleplay Gamemode for Garry's Mod**
*Developed for Real Time Roleplay (RTRP) Community - Circa 2007*

---

## Overview

RefugeeRP is a comprehensive Garry's Mod roleplay gamemode created during the golden era of Garry's Mod roleplay communities. The community was originally created by "JT" in 2007, and this gamemode powered the Real Time Roleplay community servers with an immersive Fallout-like experience.

This gamemode represents a snapshot of early Garry's Mod roleplay history, featuring the classic TacoScript framework that influenced many subsequent RP gamemodes.

### Key Information
- **Original Name:** RefugeeRP (TacoScript variant)
- **Developer:** JT
- **Launched:** 2007
- **Framework:** TacoScript (March 23, 2007)

---

## Features

### 🎭 Character System
- **Character Creation** - Customizable character profiles with first and last names
- **Model Selection** - 29 citizen models (18 male, 11 female)
- **Persistent Characters** - SQL-based character saving
- **Stats System** - Progressive skill development:
  - Strength
  - Speed & Sprint
  - Medical expertise
  - Stealth capabilities

### 🏛️ Faction System
- **Refugees** - Standard civilian faction
- **SecForce** - Security force with special permissions
- **Bandits** - Resistance fighters with unique equipment access
- **Medics** - Special medical clothing and abilities

### 🎒 Inventory & Items
- **Grid-based Inventory** - Weight and size-based system
- **30+ Unique Items** including:
  - **Food & Drinks:** MREs, bananas, oranges, melons, beer, vodka, bottled water
  - **Medical Supplies:** Bandages, medicine, Tylenol
  - **Equipment:** Radios, backpacks, vests (medic/rebel)
  - **Weapons:** Extensive arsenal (see Weapons section)
  - **Trade Goods:** Newspapers, paper for letters
  - **Supply Crates:** Special ration distribution items

### 🔫 Custom Weapons
Complete "TS" (TacoScript) weapon series:
- **Pistols:** Glock 18C, P228, Enforcer
- **SMGs:** MP5K, MP7, HK P46
- **Rifles:** AK-47
- **Shotguns:** 12-Gauge, Beanbag Shotgun, Breaching Shotgun
- **Grenades:** Flashbang, Fragmentation
- **Melee:** Hands (punching, door knocking, untying)
- **Special:** Keys, Medic tools

### 💰 Economic System
- **Credits Currency** - Server-wide economy
- **Black Market** - Underground item trading
- **Factory System** - Legitimate supply purchasing
- **Business Framework** - Shop management tools
- **Dynamic Pricing** - Supply and demand mechanics

### 🚪 Property System
- **Door Ownership** - Purchase and manage properties
- **Door Sharing** - Grant access to other players
- **Knocking System** - Interactive door communication
- **Forced Entry** - Door ramming mechanics

### 📻 Communication
- **Local Chat** - Proximity-based communication
- **Radio System** - Item-based long-range communication
- **OOC Chat** - Out-of-character communication
- **Whispering** - Reduced range private messages
- **Yelling** - Extended range public messages

### 🛠️ Workshop System
- **Item Crafting** - Combine items to create new ones
- **Mixtures** - Chemical and substance combinations
- **Processing** - Transform raw materials

---

## Installation

### Requirements
- Garry's Mod (2007-2012 era recommended for authenticity)
- MySQL database (for character persistence)
- Source SDK Base

### Setup Instructions

1. **Extract Files**
   ```
   Place the RefugeeRP folder in your garrysmod/gamemodes/ directory
   ```

2. **Database Configuration**
   - Set up MySQL database
   - Import SQL schema (if available)
   - Configure database connection in server files

3. **Server Configuration**
   - Add to server startup: `+gamemode RefugeeRP`
   - Configure admin privileges
   - Set map to a supported HL2RP map

### Supported Maps
- rp_cscdesert_v2-1 (includes custom spawn points)
- Most Garry's Mod roleplay maps

---

## Gameplay Guide

### Character Creation Process
1. **Quiz System** - Answer roleplay knowledge questions
2. **Name Selection** - Choose realistic first and last name
3. **Model Selection** - Pick from available citizen models
4. **Spawn** - Begin your roleplay experience

### Chat Commands
- `/help` - Open help menu
- `/citizenclothes` - Change to citizen clothing
- `/medicclothes` - Change to medic clothing (requires medic vest)
- Various roleplay commands for actions and emotes

### Player Progression
- **Stat Development** - Skills improve through usage
- **Reputation** - Build standing within factions
- **Property** - Acquire doors and buildings
- **Equipment** - Gather weapons and supplies

### Admin Features
- Comprehensive admin menu system
- Player data management
- Prop spawn tracking
- Ban system (IP and SteamID)
- Tooltrust system for trusted builders

---

## Technical Information

### File Structure
```
RefugeeRP/
├── info.txt                 # Gamemode information
├── entities/
│   ├── entities/
│   │   └── item_prop/      # Item entity system
│   └── weapons/            # Custom weapon SWEPs
│       └── ts_*/          # TacoScript weapons
├── gamemode/
│   ├── maps/              # Map-specific configurations
│   ├── items/             # Item definitions
│   ├── tacovgui/          # Custom GUI framework
│   ├── cl_*.lua           # Client-side scripts
│   ├── player_*.lua       # Player systems
│   ├── admin*.lua         # Administration
│   ├── rp_*.lua           # Roleplay systems
│   └── init.lua           # Main server initialization
```

### Database Schema
- Character data storage
- Inventory persistence
- Property ownership records
- Ban lists and admin privileges
- Statistics tracking

### Development Notes
From the original developer (March 8, 2008):
> "Good luck to whoever reads this line of text, and may the scripting prosper." - Rick

---

## Historical Context

### Real Time Roleplay Community
RTRP was one of the early dedicated roleplay communities in Garry's Mod, focusing on a serious post-apocolyptic universe roleplay. The community emphasized:
- Character development over combat
- Immersive storytelling
- Community-driven narratives
- Strict roleplay standards

### TacoScript Legacy
TacoScript became one of the foundational frameworks for Garry's Mod roleplay, influencing:
- Future HL2RP gamemodes
- Inventory system designs
- Character persistence methods
- Admin tool development

### Era Significance
This gamemode represents the 2007-2008 era of Garry's Mod when:
- Roleplay communities were emerging
- Lua scripting was becoming sophisticated
- Community-created content was flourishing
- The modding scene was highly experimental

---

## Changelog Highlights

### July 2012 Updates
- Fixed GMod 13 compatibility issues
- Enhanced weapon saving system
- Improved stat progression balance
- Added workshop functionality
- Prop spawning restrictions
- Radio system improvements
- Tooltrust system implementation

### Notable Features
- Dual ban system (SteamID + IP)
- Advanced prop spawn logging
- Stat-based gameplay mechanics
- Black market pricing dynamics

---

## Credits

### Development Team
- **Scripter:** JT
- **Framework:** TacoScript
- **Community:** Real Time Roleplay (RTRP)

### Special Thanks
- The original RTRP community members
- Early Garry's Mod roleplay pioneers
- TacoScript framework contributors

---

## Preservation Note

This gamemode is preserved as a historical artifact of early Garry's Mod roleplay culture. While it may require modifications to run on modern Garry's Mod versions, it serves as valuable documentation of the creativity and innovation that characterized the 2007-2008 modding scene.

The code reflects the programming standards and practices of its era and should be viewed in that historical context. It represents countless hours of community-driven development and the passion of early roleplay enthusiasts.

---

## License

This gamemode was created for the Real Time Roleplay community. As a historical preservation, it should be treated with respect for its original creators and the community it served.

---

*"Launched in 2007"*

**For the memories of golden age Garry's Mod roleplay.**