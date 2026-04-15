# 📊 Kickstarter Projects Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&()
---

## 📌 Project Overview

This **Power BI dashboard** provides a comprehensive analysis of **Kickstarter crowdfunding campaigns** worldwide. It uncovers trends across project categories, funding success rates, currency distributions, and yearly growth patterns — helping understand what drives crowdfunding success on one of the world's largest crowdfunding platforms.

---

## 📈 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 🗂️ Total Projects | **701.8K** |
| 👥 Total Backers | **3.98K** |
| 💰 Total Pledged | **$6.48bn** |
| 🎯 Total Goal | **$33.8bn** |

---

## 🖼️ Dashboard Preview

![Dashboard Preview](screenshots/dashboard.png)

---

## 🗂️ Dataset

- **Source:** [Kaggle — kemical/kickstarter-projects](https://www.kaggle.com/kemical/kickstarter-projects)
- **Format:** 2 Sheets (CSV / Excel)
- **Size:** 323,118 rows

### Key Columns

| Column | Description |
|---|---|
| `name` | Project name |
| `main_category` | Primary category (Film & Video, Music, Games…) |
| `currency` | Currency used (USD, GBP, EUR, CAD…) |
| `deadline` | Funding deadline date |
| `goal` | Funding goal amount |
| `pledged` | Amount pledged by backers |
| `state` | Project status: `failed` / `successful` / `canceled` / `live` / `suspended` |
| `backers` | Number of backers |
| `country` | Country of origin |
| `usd_pledged_real` | Pledged amount converted to USD |
| `usd_goal_real` | Goal amount converted to USD |

---

## 📊 Dashboard Visuals

### 1️⃣ Count of Projects by Category
Horizontal bar chart showing the top categories:
- 🥇 Film & Video — **121K**
- 🥈 Music — **99K**
- 🥉 Publishing — **74K**
- Games, Technology, Design, Art, Food, Fashion...

### 2️⃣ Count of Projects by State
| State | Count |
|---|---|
| ❌ Failed | 365.9K |
| ✅ Successful | 247.0K |
| 🚫 Canceled | 71.1K |
| 🟢 Live | 7.2K |
| ⚪ Undefined | 7.1K |
| ⏸️ Suspended | 3.3K |

### 3️⃣ Total Pledged by Currency
USD dominates with ~$5bn, followed by GBP, EUR, CAD, and SEK.

### 4️⃣ Projects by Year
Line chart tracking project growth from **1970 to 2018**, peaking at **68K projects in 2015**.

---

## 🔍 Key Insights

- 🎬 **Film & Video** is the most popular category with 121K projects
- 📉 Only **~35%** of projects successfully reach their funding goal
- 📅 The platform grew rapidly between **2009 and 2015**, then declined
- 💵 **USD** accounts for the vast majority of total pledged funds
- 💸 Despite $6.48bn pledged, total goals reached $33.8bn — a massive **funding gap**

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard creation & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | KPI measures & calculated columns |
| **Kaggle** | Dataset source |
| **Git & GitHub** | Version control |

---

## 📁 Repository Structure

```
kickstarter-powerbi/
├── data/                  # Raw dataset files (download from Kaggle)
├── dashboard/
│   └── kickstarter.pbix   # Power BI report file
├── screenshots/
│   └── dashboard.png      # Dashboard preview image
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/kickstarter-powerbi.git
   ```

2. **Download the dataset** from [Kaggle](https://www.kaggle.com/kemical/kickstarter-projects) and place it inside the `/data` folder

3. **Open** `dashboard/kickstarter.pbix` in **Power BI Desktop**

4. **Refresh the data source** and update the file path to your local `/data` folder

5. **Explore** the interactive dashboard! 🎉

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
The dataset is publicly available on Kaggle under its respective terms of use.

---

<div align="center">

Made with ❤️ using **Power BI** &nbsp;|&nbsp; Data from **Kaggle** &nbsp;|&nbsp; ⭐ Star this repo if you found it helpful!

</div>
