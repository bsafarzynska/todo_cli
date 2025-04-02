# To-Do CLI App (CSV version)

A simple command-line To-Do List app written in Python.  
It stores tasks in a CSV file and supports adding, listing and deleting tasks from the terminal.

---

## How to Use

### 1. Add a task
```bash
python todo.py add "Buy groceries"
```

### 2. List all tasks
```bash
python todo.py list
```

### 3. Delete a task
```bash
python todo.py delete 1
```

---

## How It Works

- Tasks are stored in a file named `tasks.csv`
- Each task is saved as a single line in the CSV file
- Tasks are numbered automatically when listed

---

## Built With

- Python 3
- `csv`
- `argparse`

No external libraries required.
