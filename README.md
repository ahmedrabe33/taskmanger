# 📝 Mini Task Manager (Bash CLI)

A lightweight **Command-Line Task Manager** written in **Bash** that helps you manage daily tasks directly from your Linux terminal.

The application is installed system-wide and can be executed from anywhere using a single command.

---

## 🚀 Features

✅ Add tasks
✅ Update tasks
✅ Delete tasks
✅ Search tasks
✅ Filter by status or priority
✅ Automatic ID generation
✅ Date validation (YYYY-MM-DD)
✅ Overdue task detection
✅ Task reports & summaries

---

## 📦 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ahmedrabe33/taskmanger.git
cd taskmanger
```

### 2️⃣ Move Script to System Path

```bash
sudo mv taskmanger /usr/local/bin/
```

### 3️⃣ Make it Executable

```bash
sudo chmod +x /usr/local/bin/taskmanger
```

Now you can run the app globally.

---

## ▶️ Run Application

```bash
taskmanger
```

You can execute it from **any directory**.

---

## 📁 Data Storage

Tasks are stored automatically in:

```bash
$HOME/tasks.txt
```

The file is created automatically if it does not exist.

---

## 🗂 Task Format

Each task is saved as:

```
ID|TITLE|PRIORITY|DATE|STATUS
```

Example:

```
1|Learn Bash|high|2026-03-01|pending
```

---

## 🧭 Main Menu

```
==== MINI TASK MANAGER ====
1) Add Task
2) List Tasks
3) Update Task
4) Delete Task
5) Search
6) Reports
7) Exit
```

---

## ➕ Add Task Rules

* Title cannot be empty
* Title must start with a letter
* Duplicate titles are not allowed
* Date must follow:

```
YYYY-MM-DD
```

Priority options:

* high
* medium
* low

---

## ✏️ Update Task

Editable fields:

* Title
* Priority
* Due Date
* Status

Status values:

* pending
* in-progress
* done

---

## 🔎 Search

Search tasks using keywords inside titles.

---

## 📊 Reports

### Task Summary

Shows number of tasks by status.

### Overdue Tasks

Displays tasks where:

```
Due Date < Today AND Status != done
```

### Priority Report

Lists tasks grouped by priority.

---

## ⚙️ Technologies Used

* Bash
* awk
* sed
* grep
* Linux date utilities

---

## 💡 How It Works

* Task IDs are generated automatically using the last saved ID.
* `awk` formats tables.
* `sed` updates and deletes records.
* Date validation is handled using the Linux `date` command.

---

## 👨‍💻 Author

Ahmed Rabie

GitHub:
https://github.com/ahmedrabe33

---

## 📄 License

Open-source project for learning and educational purposes.
