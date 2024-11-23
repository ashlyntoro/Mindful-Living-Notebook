# Mindful-Living-Notebook
This Python application is designed to help you monitor both your physical and mental health on a daily basis. It allows users to log their activities, sleep, diet, energy levels, mood, stress levels, and overall well-being. The app stores your data in a CSV file, making it easy to track changes over time

# Features

-Track physical health: Monitor your physical activity, sleep quality, diet, and energy levels.

-Track mental health: Log your mood, stress levels, and overall mental well-being.

-Data storage: All entries are saved in a CSV file for future reference and analysis.

-Simple interface: Interactive, command-line interface with easy navigation.

-Search Entries by Date: Search for journal entries for a specific date (e.g., YYYY-MM-DD).

# How to Use

# 1. Clone or Download the Project

Download the project or clone it from GitHub.

```bash
git clone https://github.com/your-username/wellness-journal.git
cd wellness-journal
```

# 2. Running the Application

To run the application, execute the following command in your terminal:
```bash
python wellness_journal.py
```

# 3. Main Menu
The application will present you with the following menu:

```markdown
--- Wellness Journal ---
1. Log a new entry
2. View past entries
3. Search entries by date
4. Exit
```

Option 1: Log a New Entry
This option allows you to log a new entry. You will be prompted to enter the following details:


Physical Activity: Describe your physical activity for the day (e.g., exercise, steps walked, etc.).

Sleep Quality: Rate your sleep quality on a scale of 1 to 10.

Diet: Describe your diet for the day (e.g., balanced, healthy, junk food, etc.).

Energy Level: Rate your energy level on a scale of 1 to 10.

Mood: Rate your mood on a scale of 1 to 10 (1=very low, 10=very high).

Stress Level: Rate your stress level on a scale of 1 to 10 (1=very low, 10=very high).

Mental Well-Being: Provide a brief description of your overall mental well-being (e.g., Good, Neutral, Bad).

Option 2: View Past Entries

This option allows you to view all past entries stored in the wellness_journal.csv file. Each entry is displayed with the corresponding date and time.

Option 3: 

To search for entries, input a date (e.g., 2024-11-22), and any matching entries will be displayed.

Option 4:

This option exits the application.

# 4. Data Storage
The application stores your entries in a CSV file named wellness_journal.csv. Each entry includes the following columns:

Date: The date and time when the entry was logged.

Physical Activity: The description of your physical activity.

Sleep Quality: Rating of your sleep quality (1-10).

Diet: Your diet for the day.

Energy Level: Rating of your energy level (1-10).

Mood: Rating of your mood (1-10).

Stress Level: Rating of your stress level (1-10).

Mental Well-Being: A brief description of your mental state.

# Contributing
Feel free to fork this repository, make improvements, and create pull requests. All contributions are welcome!

# License
This project is open-source and available under the MIT License.
