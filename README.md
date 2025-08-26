---

# 📝 Habit Tracker (Python CLI)

A simple command-line habit tracker built in **Python** using **OOP** concepts and **pickle** for data persistence.
This project lets you create, track, update, and remove habits — and it remembers your progress across sessions.

---

## ✨ Features

* Add new habits with **category** (Health, Work, Others) and **frequency** (Daily / Weekly).
* Mark habits as completed ✅ (prevents duplicate completions for the same day).
* Track your current **streak** for each habit.
* View all habits in a neat summary.
* Remove habits when you’re done with them.
* Data is automatically saved using `pickle`, so your progress is never lost.

---

## 📦 Requirements

* Python 3.x
  *(No extra libraries needed — everything is from the standard library!)*

---

## ▶️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/habit-tracker.git
   cd habit-tracker
   ```
2. Run the script:

   ```bash
   python Data_persistence_prac.py
   ```
3. Use the interactive menu to add/view/update/remove habits.

---

## 🖥️ Menu Options

```
--------------Menu------------
| 1. View Habits             |
| 2. Add new habit           |
| 3. Update habit            |
| 4. Remove habits           |
| 5. Exit                    |
------------------------------
```

---

## ⚡ Example

```
Enter the name, category (1-Health, 2-Work, 3-Others), 
and frequency (1-Daily, 2-Weekly) of your habit:
Drink Water,1,1

1 - Drink Water, Health, Daily
Status : Completed Today ✅
Streak : 2
```

---

## 🚀 Future Improvements

* Weekly progress tracking (% of goals met each week).
* Prettier CLI output (colors, progress bars).
* Option to export habits data as JSON/CSV.
* GUI or web-based interface.

---

## 📜 License

This project is licensed under the MIT License — free to use, modify, and share.

---

👨‍💻 Made with Python and curiosity!

---
