# 📖 Project Description

This project is a **command-line To-Do List Task Tracker** built in Python with **JSON file handling** for persistent storage.  
It helps users efficiently manage tasks by allowing them to:

- Add tasks with validation (Task number, Description, Priority, Due date).
- Display all tasks or only those with **High Priority**.
- Update tasks by:
  - Marking them as completed
  - Editing the description or due date
  - Deleting tasks
- Save tasks in a `todo.json` file so data is not lost after exiting.

---

## 🛡️ Input Validations

- Task number must be numeric.
- Description must contain only letters (A–Z).
- Priority must be one of: `low`, `medium`, or `high`.
- Due date must follow the format `DD-MM-YYYY`.

---

## 📂 Data Format Example

Each task is stored in JSON as:

```json
{
  "Tasknumber": 1,
  "Description": "BuyGroceries",
  "Priority": "high",
  "Duedate": "25-08-2025",
  "status": false
}
