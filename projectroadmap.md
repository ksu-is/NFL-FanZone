# Project Roadmap – NFL FanZone

This roadmap tracks all planned, in-progress, and completed tasks for the development of the NFL Stats & Simulation Python app. It will be updated each sprint with new tasks, checkboxes, and progress notes.

---

# 🚀 Sprint 1 – Planning & Setup

### **Goals**
- Finalize project idea
- Join the GitHub organization (ksu-is)
- Create team repository
- Write initial README.md
- Search for and clone a related repository
- Document tasks using markdown

### **Tasks**
- [x] Brainstorm and select project idea  
- [x] Post idea in Teams project sheet  
- [x] Mark idea as “Go”  
- [x] Join GitHub organization (ksu-is)  
- [x] Install GitHub Desktop  
- [x] Create repository for the project  
- [x] Learn basic markdown syntax  
- [x] Write initial README.md  
- [x] Search for related repositories  
- [x] Clone **fivethirtyeight/nfl-elo-game** for evaluation  

### **Notes on Repo Evaluation**
- The 538 Elo code runs in Jupyter notebooks and is research-oriented.  
- The code is long, complex, and not structured for easy reuse.  
- Useful concept learned: converting rating differences into probability.  
- Decision: **Do not reuse their code**, but incorporate simplified Elo logic.

---

# 🔧 Sprint 2 – Coding & Git Workflow

### **Goals**
- Begin coding all core features
- Make frequent Git commits (at least 6 meaningful ones)
- Add detailed commit messages
- Update roadmap continuously
- Build project structure and initial modules

### **Planned Tasks**
- [ ] Create full project folder structure (`src/`, `data/`, `tests/`)
- [ ] Build `app.py` with base program structure
- [ ] Add `data_loader.py` for reading team data
- [ ] Create `ratings.py` with initial rating formula
- [ ] Implement `simulate_game()` (probability-based)
- [ ] Implement `simulate_week()` and `simulate_season()`
- [ ] Create simple command-line interface
- [ ] Add sample data file (`teams.csv`)
- [ ] Test core functions with sample stats
- [ ] Update README.md with Sprint 2 features
- [ ] Add progress notes to this roadmap

### **Required Git Commits**
- [ ] Commit: Initial folder structure  
- [ ] Commit: Added data loader module  
- [ ] Commit: Added rating calculation logic  
- [ ] Commit: Added game simulation + explanation  
- [ ] Commit: Added week/season simulation  
- [ ] Commit: Updated README.md & roadmap  

---

# 🧩 Emerging Tasks (Add as Sprint Continues)
- [ ] Increase realism of rating model  
- [ ] Add interactive menu options  
- [ ] Add error handling for missing data  
- [ ] Add logs for simulation results  
- [ ] Begin drafting UI or visualization ideas for Sprint 3  

---

# ✅ Completed Tasks (Mark as Done)
_Add “DONE” next to any completed task above and check the box._

---

# 📝 Sprint Reflection Sections

### **Sprint 1 Reflection**
_Completed._

### **Sprint 2 Reflection**
_To be added at end of sprint._

---

# 📌 Notes
This roadmap is a living document. Each sprint should show:
- new tasks added  
- old tasks checked off  
- changes reflected in Git commits  
- updated README.md  

Keeping this file updated proves progress in version control, planning, and execution.


