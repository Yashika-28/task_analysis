# 📊 Task Analysis & 📔 Funky Virtual Diary

This repository contains **Task Analysis utilities** along with **Funky Virtual Diary**, a feature-rich desktop diary and productivity tracking application built using **Python** and **PyQt6**.

The project focuses on helping users analyze daily productivity, track habits, manage tasks, and visualize personal progress through interactive analytics.

---

# 📔 Funky Virtual Diary

A desktop-based personal diary application that allows users to track daily mood, productivity, habits, and planning. The application stores user data and provides graphical insights to help users improve their daily routines and decision-making.

---

## ✨ Key Features

### 🧠 Daily Reflection
- Record daily thoughts and experiences
- Track reasons for unhappy moments
- Tag importance of events

---

### 📊 Quantitative Tracking
- Happiness slider (1–5 scale)
- Productivity slider (1–5 scale)
- Track:
  - Nap hours
  - Meals consumed
  - Money spent

---

### ✅ MoSCoW Task Management
Organize tasks using priority classification:

- **Must Have**
- **Should Have**
- **Could Have**
- **Won’t Have**

---

### 🔮 Future Planning
- Plan tasks for the next day
- Record mistakes to avoid
- Define areas for personal improvement

---

### 🔁 Habit Tracking
Daily checklist includes:

- Coding
- GATE Classes
- Speaking Skills
- Workout
- Meditation

---

### 💾 Data Persistence
- Automatically stores entries in:
diary_data.csv

- Appends new records instead of overwriting existing data

---

### 📈 Visual Analytics

Includes built-in graph generation using Matplotlib:

1. **Line Chart**
   - Happiness vs Productivity comparison over time

2. **Scatter Plot**
   - Nap hour tracking
   - Highlights healthy sleep zone (5–8.5 hours)

3. **Pie Charts**
   - Displays habit completion percentage

---

# 🛠️ Tech Stack

## 🖥️ Application
- Python
- PyQt6

## 📊 Data & Visualization
- Pandas
- Matplotlib

## 🌐 Additional Utilities
- Requests

---

# 📂 Project Structure
```
task_analysis/
│
├── main.py # Core application logic
├── diary_data.csv # Stores user diary entries (auto-generated)
├── requirements.txt # Python dependency list (if present)
├── README.md # Project documentation
│
├── analysis/ # Task analysis related utilities
│ ├── data_processing.py
│ ├── analytics.py
│ └── helper_functions.py
│
├── ui_components/ # PyQt UI design modules
│ ├── dashboard.py
│ ├── graphs.py
│ └── widgets.py
│
└── assets/ # Static UI resources
├── icons/
└── images/
```

---

# ⚙️ Prerequisites

Ensure you have Python installed along with the following libraries:

- PyQt6
- Pandas
- Matplotlib
- Requests

---

# 📦 Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Yashika-28/task_analysis.git
cd task_analysis
```

2️⃣ Install Dependencies

```
pip install PyQt6 pandas matplotlib requests
```

▶️ Running the Application

```
python main.py
```

# 🖥️ Application Usage
## 🧭 Dashboard Layout
🔹 Left Panel
- Mood tracking
- Unhappiness analysis
- Happiness triggers

🔹 Center Panel
- Motivational quote display

🔹 Right Panel
- Habit tracking
- Statistical tracking
- Tomorrow planning section

## 💾 Saving Data
- Fill all fields
- Click Save Entry
- Automatically:
- Creates diary_data.csv
- Stores daily data

## 📈 Viewing Graphs
- Click Show Graph button to open:
- Happiness/Productivity trend
- Sleep analytics
- Habit completion visualization

## 🎯 Project Objectives
- Improve daily productivity awareness
- Track emotional and mental well-being
- Promote structured task management
- Provide self-improvement insights through data visualization

##🔮 Future Enhancements
- ☁️ Cloud-based data storage
- 📱 Mobile version of diary
- 🧠 AI-based productivity suggestions
- 🔔 Reminder & notification system
- 📊 Advanced analytics dashboard
- 🔐 User authentication and multi-user support

## 🤝 Contributing
Contributions are welcome!
- Fork the repository
- Create a new feature branch
- Commit changes
- Push branch
- Submit Pull Request

## 📜 License
This project is open-source and intended for educational and productivity enhancement purposes.

## 👩‍💻 Author
Developed by Yashika
