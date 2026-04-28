⚽ UEFA Champions League Player Analysis

 📌 Project Overview

This project focuses on scraping and analyzing UEFA Champions League player statistics.

Using Selenium, I collected player-level data such as:

* Player Name
* Club
* Position
* Minutes Played
* Matches Played
* Goals
* Assists
* Distance Covered
* Top Speed

The goal of this project is to transform raw scraped data into meaningful insights about player performance, efficiency, and physical attributes.

---

 ⚙️ Tech Stack

* Python
* Selenium (Web Scraping)
* Pandas (Data Processing)
* Matplotlib / Seaborn (Visualization)

---

 🌐 Data Source

UEFA Official Website:
https://www.uefa.com/uefachampionsleague/statistics/players/

---

 🛠️ Data Collection Process

1. Automated browser using Selenium
2. Handled dynamic content (AG Grid table)
3. Extracted player data using CSS selectors
4. Implemented scrolling to load visible data
5. Stored structured data into CSV

---

 📊 Data Fields

* Rank
* Player Name
* Club
* Position
* Minutes Played
* Matches Played
* Goals
* Assists
* Distance Covered (km)
* Top Speed (km/h)

---

## 🔧 Feature Engineering

Created additional metrics for deeper analysis:

* **Goal Contribution** = Goals + Assists
* **Goals per 90 Minutes**
* **Contribution per Match**

---

## 🔍 Key Analysis Questions

* Who are the top-performing players based on goals and assists?
* Which players are the most efficient scorers (Goals per 90)?
* Do players with higher top speed perform better?
* Which position contributes the most offensively?
* Which players cover the most distance on the field?

---

## 📈 Insights (Example)

* Midfielders tend to cover the highest distance
* High speed does not always correlate with higher goals
* Some players show high efficiency despite fewer minutes
