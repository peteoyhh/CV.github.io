---
name: Video Game Industry Dashboard
tools: [Tableau]
image: assets/imgs/video_games_thumb.png
description: A three-part interactive dashboard exploring publisher performance, PC gaming dynamics, and player demographics from 1995 to 2020.
download_link: assets/tableau/video_game_dashboard.twbx
---

# 🎮 Video Game Industry Dashboard

This Tableau project presents an interactive, multi-dimensional dashboard that explores the evolution of the video game industry from 1995 to 2020.

It consists of three complementary sub-dashboards:

### 1. **Business Dashboard**
Focuses on Top 10 game publishers between 2000–2010, their best-selling titles, and regional market reliance (especially North America). It helps identify dominant players and strategic shifts in publishing.

### 2. **PC Gaming Enterprise Dashboard**
Analyzes PC sales and Steam platform ownership using 5-year time intervals. Highlights include:
- Discrepancies between ownership and sales
- Genre activity rate
- Publisher output per genre over time

### 3. **Demographic Dashboard**
Explores how game preferences vary by **age**, **region**, and **gender**, identifying:
- The 31–45 age group as the most engaged demographic
- Balanced gender interest in simulation/strategy games
- Regional preference trends

---

## 📷 Dashboard Preview

![Video Game Dashboard Screenshot]({{ site.baseurl }}/assets/imgs/video_games_thumb.png)

---

## 📥 Download Tableau Workbook

<div class="center">
  {% include elements/button.html link="{{ site.baseurl }}/assets/tableau/video_game_dashboard.twbx" text="Download Workbook (.twbx)" %}
</div>

---

## 🔗 Data & Methods

We used multiple datasets sourced from Kaggle, including:
- [Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)
- [Steam Game Stats](https://www.kaggle.com/datasets/thedevastator/steam-games-user-statistics-and-features)
- [Online Gaming Behavior](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset)

<div class="left">
  {% include elements/button.html link="https://github.com/<your-gh-username>/tableau-work/blob/main/video_game_dashboard.twbx" text="View on GitHub" %}
</div>

<div class="right">
  {% include elements/button.html link="https://www.kaggle.com/datasets" text="Explore Source Data" %}
</div>

---

## 🧠 Insights

- North American market is critical to publisher success.
- Steam ownership does not always equate to revenue (free-to-play effects).
- Simulation & strategy genres attract older and more diverse player groups.

---

## 🧩 Challenges Addressed

- **Platform duplication** (same title across consoles)
- **Steam outliers** skewing visual clarity
- **Demographic group sparsity** (gender, age normalization)

---

By combining market, platform, and player data, this project offers rich strategic insight to developers, publishers, and analysts alike.
