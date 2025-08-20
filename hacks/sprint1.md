---
layout: base
title: Sprint 1 Blog
permalink: /sprint1/
---

# 🚀 Progress Update: Pong Debugging Lesson  

Over the past week, I’ve made significant progress on my **Computer Science project-based learning tools**. My goal has been to create engaging activities that blend coding, debugging, and collaboration using classic arcade games.  

---

## 🎮 Building the Pong Game  

I started by coding a **Pong Game in JavaScript and HTML Canvas**. The game includes:  
- Two paddles controlled by **W/S keys** (left) and **Arrow keys** (right).  
- A ball that bounces off walls and paddles.  
- A simple **scoring system**.  
- Real-time updates with `setInterval(loop, 1000/60)` for smooth gameplay.  

This gave me a working foundation to design a debugging-focused classroom activity. Students can immediately see how small code changes affect gameplay, which makes it perfect for learning **pair/trio programming**.  

---

## 📚 Creating the Debugging Lesson  

Using the Snake Game Debugging template I had before, I adapted it into a **Pong Debugging Lesson**. The structure includes:  

- **Pair/Trio Programming Overview** → Introduction to Agile-style collaboration.  
- **Pong Debugging Session** → Students work through real issues in the Pong code.  
- **Debugging Workflow (Mermaid diagram)** → Visual map of the problem-solving cycle.  
- **GitHub Issues + Burndown Planning** → Students learn to track bugs like real developers.  
- **Driver/Navigator/Observer Roles** → Rotation system to keep all teammates engaged.  
- **Evaluation Table** → Tracks performance across planning, coding, and code review.  
- **Reflection Questions** → Students think critically about debugging strategies.  

I also included **direct navigation links** at the top of the lesson so students can jump between sections easily — almost like an interactive manual.  

---

## 🛠️ Tools Up and Running  

To make this all possible, I’ve been setting up and testing my development tools:  

- **GitHub Issues + Kanban** → Students document and manage bugs.  
- **Live Share (VS Code)** → Enables real-time collaboration for driver/navigator debugging.  
- **Mermaid Diagrams** → Used to clearly show the debugging workflow.  
- **Markdown Lessons** → Organized and published as blog-style resources for easy student access.  

Everything is now connected and working together. This means students can **code, debug, and collaborate** in a realistic development environment — but with the fun of debugging a retro game.  

---

## ✨ Next Steps  

- Add **intentional bug injections** into Pong (e.g., ball not resetting, paddle slipping out of bounds, or score not updating).  
- Create a **GitHub Classroom repo** preloaded with Pong so students fork and start debugging.  
- Collect student feedback after the first run of the activity.  

---

## 💡 Reflection  

Looking back, I’m excited about how far I’ve come. From coding the **Pong game from scratch** to adapting a **debugging lesson template**, I now have a **complete learning activity** that blends fun, coding, and real-world workflows.  

This project has helped me strengthen my own coding, teaching, and project management skills — and I can’t wait to see how students respond to it.  

<div class="mermaid">
flowchart TD
    A[🏓 Start Pong Lesson] --> B[👨‍💻 Build Pong Game]
    B --> C{🐞 Bug Found?}
    C -->|Yes| D[📝 Document Issue]
    D --> E[🔧 Debug & Fix]
    E --> B
    C -->|No| F[✅ Working Game]
    F --> G[📊 Reflect & Blog]
    G --> H[🚀 Share with Class]
</div>

---

👉 Next milestone: **Injecting bugs into Pong and running the first classroom debugging session!**  


