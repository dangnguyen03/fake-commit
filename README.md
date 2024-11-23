# GitHub Activity Generator

A script to instantly create an impressive GitHub Contributions Graph for the last year. 🚀

## ⚠ Disclaimer
This script is for educational purposes and fun only. Skills should not be judged based on a graph, but if someone insists, let them be amazed by your activity!

---

## ✨ What It Looks Like

### Before 😐 😶 😒  
[Graph Before]

### After 💪 😌 ❤️ 😎  
[Graph After]

---

## 🚀 Features
- Generate commits for every day in the last year.
- Fully customizable commit frequency and count.
- Option to exclude weekends.
- Works for both private and public repositories.

---

## 📋 How to Use
1. **Create a Repository**  
   - Create an **empty GitHub repository** (do not initialize it with any files).  
2. **Download the Script**  
   - Download the `contribute.py` script.  
3. **Run the Script**  
   Execute the script with your repository link:  





## RUN

1. Run the script with maximum commits and frequency:
   ```bash
   python contribute.py --max_commits=12 --frequency=60 --repository=git@github.com:user/repo.git

2. Run the script with don't want to commit on weekends:
    ```bash
    python contribute.py --no_weekends

3. Use --days_before and --days_after to specify how many days before the current date the script should start committing, and how many days after the current date it will keep committing.
    ```bash
    python contribute.py --days_before=10 --days_after=15

