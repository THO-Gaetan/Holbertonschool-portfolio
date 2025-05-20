# 🎮 Project Charter – IdleQuestLine

## Project Objectives

**Purpose:**  
The purpose of *IdleQuestLine* is to create a browser-based idle RPG that offers satisfying and strategic progression with minimal active gameplay. It serves both as an engaging game for casual players and a full-stack portfolio project for Gaetan Pineiro as part of the Holberton School curriculum.

**SMART Objectives:**
- Deliver a functional MVP with timer-based work systems and an adventure mode using Phaser.js and a Firebase or Node.js backend.
- Implement a user account and cloud save system to allow secure, persistent player progression across sessions.
- Provide a smooth user experience through an intuitive interface including inventory, character sheets, and progression menus.

---

## Identify Stakeholders and Team Roles

### Stakeholders

| Type      | Stakeholder                              |
|-----------|------------------------------------------|
| Internal  | Gaetan Pineiro (Developer)               |
| Internal  | Holberton School (Instructors/Mentors)   |
| External  | End-users (Casual and idle game players) |

### Team Roles

| Role            | Name            | Responsibilities                                                  |
|-----------------|-----------------|-------------------------------------------------------------------|
| Project Manager | Gaetan Pineiro  | Oversees planning, timeline tracking, and overall project vision |
| Lead Developer  | Gaetan Pineiro  | Develops frontend and backend, implements gameplay mechanics     |
| UI/UX Designer  | Gaetan Pineiro  | Designs the game interface and menus                             |

---

## Define Scope

### In-Scope
- Timer-based work system (e.g., Lumberjack, Miner)
- Adventure mode with class selection and turn-based combat
- Character stats, inventory, and item rewards
- Cloud-based save and user authentication
- Functional frontend using Phaser.js
- Backend using Firebase or Node.js

### Out-of-Scope
- Real-time multiplayer or chat systems
- Advanced animations and detailed sprite assets
- Mobile app deployment
- In-game economy balancing for long-term monetization

---

## Identify Risks

| Risk                                          | Mitigation Strategy                                                  |
|-----------------------------------------------|-----------------------------------------------------------------------|
| Cheating via system clock manipulation        | Use server timestamps or store absolute start/end time               |
| Learning curve with Phaser.js or backend tools| Allocate research time and utilize templates and community docs      |
| Player churn due to idle monotony             | Implement frequent reward drops and unlockable progression elements  |
| Backend/storage costs                         | Use Firebase’s free tier or local storage as fallback                |
| Scope creep or overengineering                | Stick to core MVP objectives and iterative development approach      |

---

## Develop a High-Level Plan

### Timeline

| Stage                          | Duration       | Milestones                                           |
|--------------------------------|----------------|------------------------------------------------------|
| Stage 1: Idea Development      | Week 1         | Game concept finalized                               |
| Stage 2: Project Charter       | Week 2         | Documentation of purpose, scope, and planning        |
| Stage 3: Technical Documentation| Week 3–4       | Define data models, timer logic, and backend setup   |
| Stage 4: MVP Development       | Week 5–10      | Implement core systems (work, adventure, UI)         |
| Stage 5: Project Closure       | Week 11–12     | Final polish, bug fixes, presentation/demo           |

---