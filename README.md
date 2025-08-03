# 📝 JSON-Based To-Do List Task Tracker (Python)

This is a command-line To-Do List application written in **Python** that allows users to add, update, view, and delete tasks. Tasks are stored persistently using **JSON file handling**.

---

## 🚀 Features

- ✅ Add multiple tasks with:
  - Task number
  - Description (validated)
  - Priority (Low / Medium / High)
  - Due date (`DD-MM-YYYY` format)
- 📋 Display tasks:
  - All tasks
  - Only **High Priority** tasks
- ✏️ Update tasks:
  - Mark task as completed
  - Delete task
  - Modify due date or description
- 💾 Persistent storage using `todo.json`
- 🔐 Input validations for safety and correctness

---

## 📂 File Structure

```bash
├── todo.json         # Stores tasks in JSON format
├── main.py           # Main Python script 
