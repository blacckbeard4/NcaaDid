# 🏀 Beyond the Court: NIL's Impact on NCAA Basketball Performance

This project explores the impact of the **Name, Image, and Likeness (NIL)** policy implemented in July 2021 on NCAA athletes, particularly **basketball players** in the U.S. and Canada.

Using causal inference and clustering analysis, we aimed to uncover:
- How NIL changed athlete performance
- Whether different player styles responded differently
- What this means for branding and recruitment strategies

---
<p align="center">
  <img src="https://i.imgur.com/spUPlPz.png" width="300">
</p>

## 📌 Background

Since July 2021, NCAA athletes in the U.S. can earn income via NIL deals (e.g., sponsorships, social media). However, school payments based on performance remain restricted, and **NIL policy varies across states**.

To study NIL's influence, we used Canadian players as a control group (who were not affected by the U.S. policy).

---

## 🎯 Key Questions

- Has NIL affected on-court behavior of athletes?
- Can we quantify that effect with performance metrics?
- Do player *types* respond differently to NIL incentives?

---

## 🔍 Methods & Metrics

### 🧪 Difference-in-Differences (DiD)


<p align="center">
  <img src="https://i.imgur.com/YO2jsvD.png" width="500">
</p>
We estimated the **causal effect** of NIL using a DiD framework comparing U.S. and Canadian player stats **pre- and post-NIL**.

**Result:**  
> U.S. players saw a **7% increase** in Game Score relative to Canadian peers post-NIL.

---

### 📊 Key Metrics Used

- **GmSc (Game Score)** – holistic individual impact measure
- **Box Plus-Minus (BPM)** – team-adjusted performance estimate
- Fouls, turnovers, points, win shares, and more

---

## 🤖 Clustering: How Player Types Responded

We segmented 500+ players into **4 behavior-based clusters**:

| Cluster Type               | Traits                               |
|---------------------------|----------------------------------------|
| 🟢 Support Role Players    | Low scoring, high defense, team-first |
| 🔴 Volume Scorers         | High usage, solo impact                |
| 🔵 Efficient Team Players | High BPM, disciplined & efficient     |
| 🟣 All-Around Performers   | Balanced offense & defense            |

<p align="center">
  <img src="https://i.imgur.com/qYt0ypT.png" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/ZnDmNzd.png" width="500">
</p>

### 📈 Major Behavior Changes Observed

- **+28% GmSc** in All-Around performers
- **+204% BPM** in Team-first players
- **+25% Points** in Volume scorers
- **-19.8% Fouls** in disciplined defenders

---

## 💡 Strategic Recommendations

1. **Use Advanced Metrics Early**  
   Spot undervalued athletes before their market value spikes.

2. **Prioritize Versatility & Team Fit**  
   All-around or support players show consistent performance gains.

3. **Segment for Smart Branding**  
   Scorers suit high-flash sponsorships; defenders suit leadership narratives.

---

## 🛠️ Tools Used

- PowerBI & Excel for dashboarding
- Python for clustering (KMeans) and causal modeling (statsmodels)
- NCAA & U SPORTS data for U.S. and Canadian athletes
- DiD estimation via pre/post-performance comparison

---

## 🧠 Learnings

- NIL did **not uniformly improve performance** — its effect depended on **player type**.
- **Team-oriented players** became more efficient, while **scorers pushed harder**.
- A player’s **style shift** can be an early signal of growth, discipline, or marketability.

---

## 🎓 Context

📍 **University of Minnesota - Carlson Analytics Lab**  
📁 Course: Exploratory Data Analytics  
📆 Date: Spring 2025  
🧑‍💼 Role: Data Science Lead

---

## 📬 Contact

Made by [Justin Varghese](https://github.com/blacckbeard4)  
Let’s connect if you're interested in **sports analytics**, **policy impact evaluation**, or **causal ML**.
