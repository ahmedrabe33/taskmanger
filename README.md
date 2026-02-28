# Mini Task Manager

A simple **Bash-based task manager** to help you add, list, update, delete, search, and generate reports for tasks directly from the terminal. Tasks are stored in a plain text file (`tasks.txt`) using a pipe-separated format.

---

## Features

- ✅ **Add Task** with title, priority, due date, and status  
- ✅ **List Tasks** with filtering options (all, by status, by priority)  
- ✅ **Update Task** by ID (title, priority, date, status)  
- ✅ **Delete Task** by ID  
- ✅ **Search Task** by keyword  
- ✅ **Reports**  
  - Task summary by status (pending, in-progress, done)  
  - Overdue tasks  
  - Priority report (high, medium, low)  

- 📅 **Date Validation:** Ensures due dates are in `YYYY-MM-DD` format.  
- 🆔 **Automatic ID Generation** for new tasks.  

---

## Requirements

- Linux or macOS terminal  
- Bash shell (`#!/bin/bash`)  
- `awk`, `sed`, `grep`, `date` utilities  

---

## Installation

1. Clone or download the script:  

```bash
git clone https://github.com/ahmedrabe33/taskmanger.git
cd taskmanger
