# CLI To-Do List App 📝

A simple **Command-Line Interface (CLI) To-Do List Application** built using **Python**.  
It allows users to **add, view, and delete tasks** stored in a text file (`tasks.txt`).

---

## Features

- ✅ Add new tasks  
- 📝 Show all tasks with numbering  
- 🗑️ Delete tasks by number  
- 💾 Tasks are saved in `tasks.txt` file  
- Pure Python, no frontend required

---

## How to Run

1. Make sure you have **Python 3** installed.  
2. Clone or download this project.  
3. Open terminal in the project folder.  
4. Run the app:

```bash
python todo_app.py
```

5. Follow the on-screen menu:  
   - `1` → Show tasks  
   - `2` → Add task  
   - `3` → Delete task  
   - `4` → Exit

---

## File Structure

```
project-folder/
│
├── tasks.txt         # Stores all tasks
├── todo_app.py       # Main Python script
└── README.md         # Project documentation
```

---

## How It Works

- Tasks are stored in a **text file** (`tasks.txt`) for persistence.  
- `load_tasks()` reads tasks from file.  
- `save_tasks()` writes tasks to file.  
- `show_tasks()` prints all tasks with numbering.  
- `main()` handles the **menu and user input**.

---

## Tech Stack

- Python 3.x  
- File handling for task storage  
- Command-line interface only (no HTML/CSS/JS)

---

## Author

**vishweshwara**

---

## Notes

- Empty tasks cannot be added.  
- Deleting requires the task number.  
- Simple, lightweight project for beginners in Python.
