# Medieval Kingdoms

**[MedievalKingdoms.net](https://medievalkingdoms.net)**

We make all our own plugins. Everything from horse physics to blacksmithing, Discord linking, and Towny addons is built in-house.

---

## Navigation

```
Medieval-Kingdoms/
|
+-- Combat & PvP
|   +-- ShieldBlocker          - Custom shield mechanics & durability system
|   +-- MedievalArchery        - Custom archery mechanics
|   +-- MedievalWeaponry       - Custom weapon system
|   +-- TownyPlunder           - Town raiding & economic conquest
|
+-- Mounts & Travel
|   +-- MedievalMounts         - Physics-based mounts with gait system & jousting (ModelEngine)
|   +-- MedievalHorses         - Realistic horse physics (acceleration, momentum, turn penalty)
|   +-- VehicleFramework       - 3D pitch/yaw/roll vehicles with turrets (ModelEngine)
|
+-- Town Management (Towny)
|   +-- TownyHappiness         - Granary/storehouse upkeep tied to a 0-100 happiness scale
|   +-- TownyWorkshops         - Bannerlords-style workshops; buy, gather & produce
|   +-- TownyLevelling         - Town levelling progression
|   +-- TownyPlunder           - Plundering mechanics for warfare & territory control
|   +-- QuartersEnhanced       - 3D cuboid sub-plots with per-area permission control
|   +-- MedievalResourcePoints - Resource point management for towns
|
+-- Economy & Crafting
|   +-- mk-smithing            - Blacksmithing crafting loop (ItemsAdder v4 / Paper 1.21.4)
|   +-- NoMoreCooked           - Custom food system with stages and fridge storage
|   +-- MedievalFishtraps      - Fishing trap mechanics
|   +-- MedievalMuhle          - Mill / grain processing
|
+-- World & Survival
|   +-- Medieval-Farming       - Custom farming mechanics
|   +-- Medieval-Cave-ins      - Cave-in events
|   +-- VineBlocker            - Stop vines from spreading
|   +-- ShulkerBlocker         - Disable shulker box interactions
|   +-- Recipeblocker          - Block specific crafting recipes
|
+-- Skills & Progression
|   +-- MedievalSkills         - Skill tree using spendable skill points instead of vanilla XP
|   +-- MedievalLiteracy       - Literacy / knowledge progression
|   +-- LockPick               - Lock-picking minigame with skill tiers
|   +-- MedievalGambling       - Gambling mechanics
|
+-- Security & Admin
|   +-- ContainerLock          - Lock containers with configurable lock items
|   +-- MedievalChestLock      - Chest locking
|   +-- MKAntiAlt              - Alt-account detection & player fingerprinting (Velocity)
|   +-- epidemic-update        - Updated epidemic plugin (Paper 1.21.4)
|
+-- Infrastructure
|   +-- VelocitySRV            - Linking bridge between Minecraft & Discord
|   +-- MedievalPlugin         - Internal plugin template
|   +-- MedievalKingdomsWebsite - Official website (TypeScript)
|   +-- GenisisTimer           - Server utility timer plugin
|
+-- Inventory & UI
    +-- MedievalInventoryManager - Force ItemsAdder items into configured slots
    +-- MedievalWeaponry         - Custom weapon & item management
```

---

## About

**Medieval Kingdoms** is a custom Minecraft server focused on medieval roleplay and strategy. Most of our mechanics are built from scratch rather than relying on off-the-shelf plugins.

| Area | What we have |
|---|---|
| Economy | Blacksmithing, custom food, workshops |
| Towns | Resource-driven Towny upkeep, happiness, plot subdivision |
| Combat | Reworked shields, custom archery, town plundering |
| Mounts | Stamina and gait-based horse/mount physics with ModelEngine |
| Progression | Skill trees, literacy, lock-picking, levelling |
| Security | Alt-account detection, container locking, Discord account linking |

---

## Key Plugins

### [ShieldBlocker](https://github.com/Medieval-Kingdoms/ShieldBlocker)
Turns off vanilla axe-stun, applies custom per-hit durability damage, and limits players to 2 shields in their inventory.

### [MedievalMounts](https://github.com/Medieval-Kingdoms/MedievalMounts)
Mount system built on ModelEngine R4 with stamina, Walk/Trot/Gallop gaits, 6 mount types, jousting, and an action-bar HUD.

### [TownyHappiness](https://github.com/Medieval-Kingdoms/TownyHappiness)
Replaces Towny's gold upkeep with a granary and storehouse resource system. Town happiness runs from 0 to 100 and affects gameplay bonuses.

### [TownyWorkshops](https://github.com/Medieval-Kingdoms/TownyWorkshops)
Bannerlords-style workshops for towns. Buy a workshop, stock it, and let it produce resources over time.

### [mk-smithing](https://github.com/Medieval-Kingdoms/mk-smithing)
Full blacksmithing crafting loop for Paper 1.21.4 with ItemsAdder v4 integration.

### [MedievalSkills](https://github.com/Medieval-Kingdoms/MedievalSkills)
Swaps out vanilla XP for a skill point system. Players earn points passively from XP orbs and spend them on combat, movement, health, and role upgrades. Supports PlaceholderAPI.

### [TownyPlunder](https://github.com/Medieval-Kingdoms/TownyPlunder)
Adds plundering to Towny so towns can raid each other for resources and territory.

### [QuartersEnhanced](https://github.com/Medieval-Kingdoms/QuartersEnhanced)
Lets you split Towny town plots into 3D cuboid areas with their own permission settings, ownership limits, and auto-reset.

### [MKAntiAlt](https://github.com/Medieval-Kingdoms/MKAntiAlt)
Velocity plugin that fingerprints players and flags likely alt accounts with a risk score.

### [VelocitySRV](https://github.com/Medieval-Kingdoms/VelocitySRV)
Bridges Minecraft and Discord. Handles mandatory account linking, chat sync, and join/leave messages.

---

## Links

| | |
|---|---|
| Website | [MedievalKingdoms.net](https://medievalkingdoms.net) |
| GitHub | [github.com/Medieval-Kingdoms](https://github.com/Medieval-Kingdoms) |
| Discord | Available via the website |

---

*All repos are private. If you want to work with us, get in touch on Discord.*
