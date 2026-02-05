# 📔 Funky Virtual Diary

A feature-rich, desktop-based personal diary application built with **Python** and **PyQt6**. This application allows users to track their daily mood, productivity, tasks, and habits, and visualizes the data over time using interactive graphs.

## ✨ Features

* **Daily Reflection:** Log your daily thoughts and reasons for unhappy moments (with importance tagging).
* **Quantitative Tracking:**
    * Happiness & Productivity sliders (1-5 scale).
    * Daily Stats: Nap hours, Meal count, Money spent.
* **MoSCoW Task Management:** Organize daily tasks into:
    * **M**ust Have
    * **S**hould Have
    * **C**ould Have
    * **W**on't Have
* **Future Planning:** Set tasks for tomorrow, define mistakes to avoid, and list personal improvements.
* **Habit Checklist:** Track daily activities like Coding, Gate Classes, Speaking Skills, Workouts, and Meditation.
* **Data Persistence:** All entries are automatically saved to a CSV file (`diary_data.csv`).
* **Visual Analytics:** Built-in "Show Graph" feature that plots your history using **Matplotlib**.

## 🛠️ Prerequisites

To run this application, you need Python installed on your system along with the following libraries:

* PyQt6
* Pandas
* Matplotlib
* Requests

## 📦 Installation

1.  **Clone or Download** the project files.
2.  **Install the dependencies** using pip:

    ```bash
    pip install PyQt6 pandas matplotlib requests
    ```

3.  **Run the application**:

    ```bash
    python main.py
    ```

## 🖥️ Usage

### 1. The Dashboard
The main window is divided into three sections:
* **Left Panel:** Focuses on current mood, unhappiness analysis, and happiness triggers.
* **Center Panel:** Displays a motivational "Quote of the Day."
* **Right Panel:** Focuses on statistical data (naps, money), habits (coding, workout), and planning for tomorrow.

### 2. Saving Data
Fill in the fields and click the **green "Save Entry" button**.
* This will create a file named `diary_data.csv` in the same directory.
* If the file already exists, it appends the new entry as a new row.

### 3. Visualizing Data
Click the **blue "Show Graph" button** to generate three windows of analysis:
1.  **Line Chart:** Compares Happiness vs. Productivity over time.
2.  **Scatter Plot:** Tracks Nap Hours (highlighting a "Healthy Zone" between 5-8.5 hours).
3.  **Pie Charts:** Shows the completion percentage of your 5 daily habits (Coding, Meditation, etc.).

## 📂 File Structure

* `main.py`: The core application code (paste your Python script here).
* `diary_data.csv`: Stores your diary entries (Created automatically after the first save).

## 🎨 Customization

### Background Image
The app loads a background image from a specific URL. To change it, find this line in the `__init__` method inside the Python code and replace the URL:

```python
self.load_background_image("YOUR_IMAGE_URL_HERE")
