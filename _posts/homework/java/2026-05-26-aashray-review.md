---
microblog: true
toc: true
layout: post
title: CS113 Final Project Portfolio — Fortune Finders & Quant Trading
description: A semester-long portfolio blog covering full-stack work across finalpages and pagesBackend — gamified financial literacy, Spring REST APIs, ML indicators, game engine OOP, and CS113 competency evidence.
permalink: /capstone/aashray-cs113-portfolio/
authors: Aashray Rajagopalan
comments: true
sticky_rank: 2
---

# CS113 Portfolio

## Overview

This document highlights my progress throughout CS113 while connecting the concepts I learned during Sprint 7 to my larger capstone and backend development work. Over the semester, I worked on both frontend and backend systems involving Java, Spring Boot, APIs, game development, financial literacy tools, and quantitative trading simulations.

Rather than only studying data structures and object-oriented programming theoretically, I focused on applying them in real projects involving collections, algorithms, REST APIs, backend architecture, and interactive game systems.

---

# Data Structures

| Learning Objective | Project Evidence / Implementation | Assessment Evidence |
|---|---|---|
| **Collections** | Used Java collections including `ArrayList`, `HashMap`, `LinkedHashMap`, and `ConcurrentHashMap` throughout backend systems | Collection implementations in backend services and models |
| **Lists** | Implemented list traversal, dynamic insertion/removal, and grouped transaction histories | List manipulation in indicator calculations and frontend rendering |
| **Stacks / Queues** | Applied ordered waypoint progression and sequential NPC traversal systems | Queue-like progression logic in `WaypointArrow.js` |
| **Trees** | Integrated Random Forest concepts and decision-tree-based ML logic | ML model integration and backend prediction systems |
| **Sets** | Used unique NPC IDs, ticker tracking, and duplicate prevention systems | Set operations in backend validation and progression systems |
| **Dictionaries / Maps** | Built multiple key-value systems using `HashMap` and `LinkedHashMap` | Backend financial tracking and configuration systems |
| **Graphs** | Modeled waypoint progression and NPC navigation relationships | Graph-style traversal and progression logic |

---

# Algorithms

| Learning Objective | Project Evidence / Implementation | Assessment Evidence |
|---|---|---|
| **Searching** | Implemented searching across market history, transactions, and backend records | Search functionality within backend services |
| **Sorting** | Sorted historical market data and transaction histories | Comparator-based ordering and backend sorting |
| **Hashing** | Used hashing for maps, backend lookup systems, and authentication support | HashMap usage and backend lookup efficiency |
| **Algorithm Analysis** | Applied traversal and weighted scoring systems | Complexity considerations documented in services |

---

# Object-Oriented Design

| Learning Objective | Project Evidence / Implementation | Assessment Evidence |
|---|---|---|
| **Abstraction** | Used service layers and base game engine classes | Separation between controllers, services, and frontend systems |
| **Encapsulation** | Applied private fields with getters/setters | Proper access modifiers in backend entities |
| **Inheritance** | Extended game engine base classes for maps and game objects | Game object hierarchy and backend extensions |
| **Polymorphism** | Shared level contracts and ML model switching | Flexible interface-based backend logic |
| **Design Patterns** | Implemented MVC, Repository, Singleton, and DTO patterns | Organized backend and frontend architecture |

---

# Software Development

| Learning Objective | Project Evidence / Implementation | Assessment Evidence |
|---|---|---|
| **Version Control** | Used Git branches, commits, pull requests, and merge workflows | GitHub commit history and branch strategy |
| **Testing** | Performed frontend and backend API testing | Browser testing and endpoint verification |
| **Build Tools** | Used Maven, Jekyll, and Gradle-style workflows | Build configuration and deployment setup |
| **Debugging** | Resolved API, CORS, rendering, and transition issues | Debug logs and troubleshooting workflow |
| **API Development** | Built RESTful Spring Boot APIs with JSON responses | Controller endpoints and API integrations |
| **Database Integration** | Used JPA/Hibernate with SQLite persistence | Entity relationships and repository systems |

---

# Deployment

| Learning Objective | Project Evidence / Implementation | Assessment Evidence |
|---|---|---|
| **Docker** | Created Docker configurations for backend deployment | Dockerfile and compose setup |
| **DNS Configuration** | Configured deployment domain routing | Live backend deployment |
| **nginx** | Used reverse proxy deployment architecture | nginx backend routing setup |
| **CI/CD** | Used GitHub Actions deployment workflows | Automated frontend deployment |

---

# Documentation

| Learning Objective | Project Evidence / Implementation | Assessment Evidence |
|---|---|---|
| **Code Comments** | Added inline comments and JavaDoc explanations | Readable backend and frontend code |
| **API Documentation** | Documented endpoints and backend services | API reference and project README |
| **Help System** | Created tutorials, lesson pages, and in-game guidance | Educational content integration |
| **Blog Portfolio** | Maintained detailed capstone documentation | Portfolio blog and project reflections |

---

# Evidence From My Code

## Reference Commit
GitHub Commit Reference:  
https://github.com/ApplicatorsCSA/pagesBackend/commit/80ab87fae11796ee1445f505336d58c4aaac0145


## Core Concepts Practiced

I focused heavily on strengthening my understanding of:

- Java collections and data structures
- Object-oriented programming principles
- Backend architecture
- Algorithmic thinking
- API development
- Real-world software engineering workflows

---

# HashMaps & Nested Collections

## Example Structures

```java
Map<String, List<List<Object>>>
profitMap
featureImportance
questProgress
```
## Purpose of Each Structure

| Structure | Purpose |
|---|---|
| `profitMap` | Stores categorized financial transaction history |
| `featureImportance` | Stores weighted ML feature values |
| `questProgress` | Tracks ordered game progression |

These structures demonstrated:

- Multi-level organization
- Nested traversal
- Efficient lookup systems
- Backend state management
- Grouped financial data storage

---

# Object-Oriented Programming

## Example Backend Class

```java
@Entity
public class Bank {
    private HashMap<String, List<List<Object>>> profitMap;

    public double assessRiskUsingML() {
        // weighted risk logic
    }
}
```

## Example Frontend Structure

```javascript
class GameControl {
  transitionToLevel() {
    // cleanup and load next level
  }
}
```

---

# Frontend Contributions

## Fortune Finders Game Engine

### Major work included:

- Futures Exchange level
- NPC progression systems
- WaypointArrow tracking
- Canvas cleanup fixes
- Educational financial literacy integration
- SVG asset pipeline fixes

---

# Backend Contributions

## Spring Boot API Systems

### Implemented backend systems including:

- Banking APIs
- Quant trading endpoints
- Technical indicators
- Paper trading systems
- Market history retrieval
- Backend persistence

---

# Software Engineering Workflow

## Development Cycle

| Step | Frontend | Backend |
|---|---|---|
| Build | Jekyll local server | Spring Boot local server |
| Test | Browser gameplay testing | API endpoint verification |
| Verify | UI functionality checks | JSON response validation |
| Deploy | GitHub Pages | Docker deployment |

---

# Challenges & Debugging

## Problems Solved

### Frontend ↔ Backend Integration

- Incorrect API paths
- CORS configuration issues
- Localhost deployment mismatches

### Game Engine Bugs

- Ghost NPCs after transitions
- Canvas cleanup failures
- Asset rendering problems

### UI Lifecycle Issues

- Duplicate listeners
- Persistent object cleanup problems

---

# Lessons Learned

These debugging experiences taught me:

- Full-stack bugs are often integration-related
- Resource cleanup is critical
- Modular architecture improves maintainability
- Backend and frontend systems must stay synchronized

---

# Reflection

This sprint helped me move beyond memorizing AP CSA concepts and begin applying them in real software systems.

I now better understand:

- How collections organize real application data
- Why maps are essential in backend development
- How algorithms process and update information
- How OOP improves scalability and organization
- How APIs connect frontend and backend systems
- How full-stack software systems are developed

One of the biggest lessons I learned is that backend systems rely heavily on structured data organization and modular design. Instead of viewing collections and algorithms as isolated classroom topics, I now see how they power:

- Financial systems
- Trading simulations
- Game progression systems
- Analytics platforms
- REST APIs
- Backend services

---

# CS113 Competencies Demonstrated

- Collections and Lists
- Maps/Dictionaries
- Algorithms and Traversal
- Object-Oriented Programming
- Encapsulation and Abstraction
- Backend Architecture
- API Development
- Version Control
- Debugging and Testing
- Deployment Systems
- Documentation and Portfolio Development

---

# Final Thoughts

This project showed me that computer science is much more than solving isolated coding problems. Building a full-stack application required combining:

- Data structures
- Algorithms
- Object-oriented programming
- Frontend systems
- Backend APIs
- Debugging
- Deployment
- Collaboration

Most importantly, it helped me understand how software engineering can be used to create systems that are both educational and technically meaningful.