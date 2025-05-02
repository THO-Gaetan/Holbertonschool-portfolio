# 🎮 IdleQuestLine - Browser-based Idle RPG

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Development Status](https://img.shields.io/badge/Status-In_Development-blue.svg)]()

```
 ___     _ _        ___                  _    _     _            
|_ _| __| | | ___  / _ \ _   _  ___ ___ | |_ | |   (_)_ __   ___ 
 | | / _` | |/ _ \| | | | | | |/ _ \_  /| __|| |   | | '_ \ / _ \
 | || (_| | |  __/| |_| | |_| |  __// / | |_ | |___| | | | |  __/
|___|\__,_|_|\___|\__\_\\__,_|\___/___|  \__||_____|_|_| |_|\___|
                                         
```

## 📖 Overview

IdleQuest is a browser-based idle RPG game that combines satisfying progression systems with minimal active gameplay. Players can engage in various work activities, go on adventures, and collect rewards—all while the game progresses even when they're not actively playing!

## 🔍 Core Features

### Work System
- **Actions:** Lumberjack, Miner, Fisher, and more professions to choose from
- **Timer Logic:** Start tasks and return later to collect your rewards
- **Rewards:** Experience points, items, and gold

### Adventure System
- **Classes:** Choose from Warriors, Rogues, Mages, and more
- **Stats:** Manage HP, ATK, DEF and other character attributes
- **Encounters:** Fight monsters and experience random events

### UI/UX
- **Main Menu:** Easy navigation through different game sections
- **Inventory:** Manage collected items and equipment
- **Character Sheet:** Track progress and customize your character

## 🛠️ Tech Stack

- **Frontend:** Phaser.js
- **Backend:** Firebase or Node.js
- **Save System:** Cloud-based with local backup
- **Authentication:** User accounts to secure progress

## 🚀 MVP Focus

Our minimum viable product concentrates on:

- 💾 Working database infrastructure
- 🔐 User authentication system
- 🖥️ Functional frontend/backend integration

### Target Problem:
Players want satisfying idle progress in short bursts of time with meaningful rewards.

### Target Audience:
- Casual gamers
- Idle game enthusiasts
- Browser-game players

## ⚠️ Risks & Mitigation Strategies

| Risk / Constraint | Mitigation Strategy |
|-------------------|---------------------|
| Timer cheating (system clock manipulation) | Use server time or store real start timestamp |
| Player churn / dropoff | Implement frequent rewards and unlock milestones |
| Limited frontend experience | Utilize Phaser templates with modular code structure |
| Server/database costs | Begin with Firebase free tier or local storage solutions |

## 🔄 Design Innovations (SCAMPER Analysis)

| Technique | Implementation Idea |
|-----------|---------------------|
| Substitute | Replace classic combat with strategic turn-based choices |
| Combine | Merge adventure mode with resource gathering mechanics |
| Adapt | Incorporate gacha-style loot systems for gathering rewards |
| Modify | Create strategic timer options (longer duration = better rewards) |
| Put to Use | Implement "offline progress" system using idle game logic |
| Eliminate | Remove complex map navigation in favor of menu-based progression |
| Reverse | Introduce time-decay mechanics where power diminishes without maintenance |

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

Pineiro Gaetan - gaetan.pineiro@gmail.com

Github Link: [https://github.com/THO-Gaetan](https://github.com/THO-Gaetan)

## 🎓 Portfolio Project

IdleQuestLine is an individual portfolio project developed as part of the Holberton School curriculum:

- **Development:** Created entirely by Pineiro Gaetan as a showcase of full-stack development skills
- **Process:** Following an iterative development approach with clear development phases and checkpoints
- **Learning Goals:** Demonstrating proficiency in frontend/backend integration, database management, and user authentication
- **Timeline:** Project development from April 21 until  July 18, 2025

This project represents the culmination of my learning experience at Holberton School and demonstrates my ability to independently design and implement a complete web application.
