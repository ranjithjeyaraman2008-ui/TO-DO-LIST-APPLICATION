# ðŸ“ TO-DO List Application

A lightweight, feature-rich Python console application for task management. Keep your tasks organized, persistent, and accessible right from your terminal.

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## âœ¨ Features

- âœ… **Add Tasks** - Create new tasks with ease
- âœ… **Remove Tasks** - Delete completed or unnecessary tasks
- âœ… **View Tasks** - Display all tasks in a clean, organized format
- âœ… **Data Persistence** - Automatic saving to local file (never lose your progress)
- âœ… **Interactive Menu** - User-friendly command-line interface
- âœ… **Lightweight** - Minimal dependencies, fast execution
- âœ… **Cross-platform** - Works on Windows, macOS, and Linux

---

## ðŸš€ Getting Started

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ranjithjeyaraman2008-ui/TO-DO-LIST-APPLICATION.git
   cd TO-DO-LIST-APPLICATION
   ```

2. **No external dependencies required!**
   This application uses only Python's built-in libraries.

---

## ðŸ’» Usage

### Running the Application

```bash
python todo.py
```

### Interactive Menu

Once you run the application, you'll see an interactive menu with options:

```
========================================
        ðŸ“‹ TO-DO LIST APPLICATION
========================================
1. Add a new task
2. View all tasks
3. Remove a task
4. Exit
========================================
Choose an option (1-4): 
```

### Example Workflow

```
Choose an option (1-4): 1
Enter your task: Buy groceries
âœ“ Task added successfully!

Choose an option (1-4): 1
Enter your task: Complete Python project
âœ“ Task added successfully!

Choose an option (1-4): 2
Your Tasks:
1. Buy groceries
2. Complete Python project

Choose an option (1-4): 3
Enter task number to remove: 1
âœ“ Task removed successfully!

Choose an option (1-4): 4
Goodbye! Your tasks have been saved.
```

---

## ðŸ“ Project Structure

```
TO-DO-LIST-APPLICATION/
â”œâ”€â”€ README.md           # Project documentation
â”œâ”€â”€ todo.py             # Main application file
â””â”€â”€ tasks.txt           # Task storage file (auto-created)
```

---

## ðŸ”§ How It Works

1. **Task Storage** - Tasks are stored in a `tasks.txt` file in the application directory
2. **Auto-save** - Every change (add/remove) is immediately saved to the file
3. **Data Loading** - On startup, the application loads existing tasks from the file
4. **Session Independence** - Your data persists between sessions

---

## ðŸ“‹ Code Overview

### Core Functions

- `add_task()` - Adds a new task to the list
- `view_tasks()` - Displays all current tasks
- `remove_task()` - Removes a task by index
- `save_tasks()` - Writes tasks to persistent storage
- `load_tasks()` - Reads tasks from file on startup
- `main()` - Runs the interactive menu loop

### Technology Stack

- **Language**: Python 3.6+
- **Libraries**: Built-in (os, json, datetime)
- **Storage**: Plain text file (tasks.txt)

---

## ðŸŒŸ Key Advantages

| Feature | Benefit |
|---------|---------|
| **No Dependencies** | Easy setup, no version conflicts |
| **Fast Execution** | Minimal overhead, instant response |
| **Data Persistence** | Never lose your tasks |
| **Simple Interface** | Intuitive for all skill levels |
| **Extensible** | Easy to add new features |

---

## ðŸ”„ Future Enhancements

- ðŸŽ¯ Task priority levels (High, Medium, Low)
- ðŸ“… Due dates and deadlines
- ðŸ·ï¸ Task categories/tags
- ðŸ” Search and filter functionality
- âœ“ Mark tasks as complete without deleting
- ðŸŽ¨ Colored output in terminal
- ðŸ’¾ Export to CSV/PDF formats
- ðŸ” Password protection
- ðŸ“Š Task statistics and analytics

---

## ðŸ¤ Contributing

Contributions are welcome! Here's how to help:

1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/TO-DO-LIST-APPLICATION.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

5. **Open a Pull Request**

---

## ðŸ“ Usage Example

```python
# The application runs interactively, but here's the flow:

# 1. Application loads existing tasks from tasks.txt
# 2. Displays interactive menu
# 3. User selects option and provides input
# 4. Application processes the request
# 5. Changes are saved automatically
# 6. Repeat until user exits
```

---

## ðŸ› Troubleshooting

| Issue | Solution |
|-------|----------|
| `tasks.txt` not created | Ensure write permissions in the application directory |
| Tasks not saving | Check file system permissions |
| Command not recognized | Ensure Python is installed and in your PATH |
| Old tasks missing | Check that `tasks.txt` is in the application folder |

---

## ðŸ“ž Support

If you encounter any issues or have questions:

- **Open an Issue** - Report bugs or request features on GitHub
- **Check Documentation** - Review this README for common questions
- **Review Code** - The code is well-commented for reference

---

## ðŸ“„ License

This project is licensed under the **MIT License** - see details below:

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, and sublicense the Software.
```

**For full license text, see LICENSE file in the repository.**

---

## ðŸ‘¨â€ðŸ’» Author

**Ranjith Jeyaraman**
- GitHub: [@ranjithjeyaraman2008-ui](https://github.com/ranjithjeyaraman2008-ui)
- Passionate about clean code and practical applications

---

## â­ Show Your Support

If you found this project helpful, please give it a star! Your support means a lot.

```
â­ Star this repository
ðŸ´ Fork it and contribute
ðŸ“¢ Share with others
```

---

## ðŸ—ºï¸ Project Roadmap

- [x] Core task management features
- [x] Data persistence
- [ ] Task priority system
- [ ] Due date tracking
- [ ] Advanced filtering
- [ ] Dark mode terminal theme
- [ ] Performance optimizations

---

## ðŸ“Š Project Statistics

- **Language**: Python
- **File Size**: Lightweight (~5KB)
- **Dependencies**: 0 external
- **Setup Time**: < 2 minutes
- **Learning Curve**: Beginner-friendly

---

## ðŸŽ¯ Quick Start Summary

```bash
# Clone the repo
git clone https://github.com/ranjithjeyaraman2008-ui/TO-DO-LIST-APPLICATION.git

# Enter directory
cd TO-DO-LIST-APPLICATION

# Run the app
python todo.py

# Start managing your tasks!
```

---

## ðŸ’¡ Tips & Tricks

1. **Batch Operations** - Add multiple tasks in succession for faster workflow
2. **Regular Cleanup** - Remove completed tasks to keep your list focused
3. **Backup Tasks** - Periodically backup your `tasks.txt` file
4. **Extend Features** - The code is simple; feel free to modify and improve!

---

## ðŸ™ Acknowledgments

- Python community for excellent documentation
- All contributors and supporters
- Open-source community for inspiration

---

**Last Updated**: June 2, 2026  
**Version**: 1.0.0

---

Made with â¤ï¸ by [Ranjith Jeyaraman](https://github.com/ranjithjeyaraman2008-ui)

