 # 📝 JSON-Based To-Do List Task Tracker (Python)

This is a command-line To-Do List application written in **Python** that allos users to add, update, view, and delete tasks. Tasks are stored persistently using **JSON file handling**.

---

## 🚀 Features

- ✅ Add multiple tasks with
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
├── main.py           # Main Python script (your code)
📦 Requirements
Python 3.x
(No external libraries required — only built-in modules)

▶️ How to Run
Clone the repository or download the code:

bash
Copy
Edit
git clone https://github.com/your-username/todo-json-task-tracker.git
cd todo-json-task-tracker
Run the Python script:

bash
Copy
Edit
python main.py
Follow the menu prompts to:

Add tasks

Display tasks

Update/delete/mark tasks

Save your progress

Exit

📌 Task Status Format
Each task contains:

json
Copy
Edit
{
  "Tasknumber": 1,
  "Description": "BuyGroceries",
  "Priority": "high",
  "Duedate": "25-08-2025",
  "status": false
}
status = false → Not completed

status = true → Completed

🛡️ Validations Included
Task number must be digits only.

Description must be letters only (A-Z/a-z).

Priority must be one of: low, medium, or high.

Due date format is strictly DD-MM-YYYY.

✨ Future Improvements (Suggestions)
Add color-coded terminal output

Integrate with GUI using Tkinter

Enable task sorting by due date or priority

Allow recurring or daily tasks

