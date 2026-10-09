# 🎬 Netflix Content Strategy Analytics Dashboard (2008 - 2021)

An interactive Power BI Dashboard analyzing Netflix's content library expansion, catalogue freshness, and global coverage strategy from 2008 to 2021.

---

## 📌 Executive Summary

This project analyzes Netflix's global content strategy using Power BI. The dashboard evaluates 8,790 titles[cite: 1] to provide business insights into platform growth, content origin, release timelines, and content type distribution (Movies vs. TV Shows)[cite: 1].

---

## 📊 Key Highlights & Insights

### 1. Overview & Content Composition
* **Library Size**: The dataset contains 8,790 total titles[cite: 1], consisting of 6,126 Movies (69.7%)[cite: 2] and 2,664 TV Shows (30.3%)[cite: 3].
* **Peak Content Addition**: Content additions peaked in 2019 with 2,016 titles added in a single year[cite: 1]. Movies peaked in 2019[cite: 2], while TV Shows peaked in 2020[cite: 3].
* **Content Duration**: Average movie duration is 99.6 minutes[cite: 2], while TV Shows average 1.75 seasons[cite: 3].
* **Top Content Genres**: International Movies (2,752 titles)[cite: 1] and Dramas (2,426 titles)[cite: 1] dominate the platform.

### 2. Catalogue Freshness Strategy
* **Same-Year Release**: 37.0% of titles were added in their release year[cite: 4]. TV Shows show a higher freshness rate (52.2% added in release year)[cite: 6] compared to Movies (30.4%)[cite: 5].
* **Median Age on Arrival**: The median age of TV Shows upon arrival is 0 years[cite: 6], whereas Movies have a median age of 2 years[cite: 5].
* **Legacy Content**: 19.96% of content added in 2021 was over 10 years old[cite: 4], with 525 titles released before the year 2000[cite: 4].

### 3. Global Content Distribution
* **Geographic Concentration**: The Top 3 content suppliers (United States, India, United Kingdom) account for 65.33% of localized titles[cite: 7].
* **Top 10 Market Penetration**: The Top 10 countries supply 84.05% of all titles with known countries[cite: 7].
* **International Expansion**: Non-US content share peaked around 2018[cite: 7], supported by acquisitions across Japan, South Korea, France, and Spain[cite: 7].

---

## 📑 Dashboard Architecture

The Power BI report is structured into 3 interactive pages, each supporting dynamic page slicers (**All titles**, **Movies**, **TV Shows**)[cite: 1, 2, 3]:

1. **Overview**: Key performance indicators (KPIs), title growth over time, format split, and top genres[cite: 1].
2. **Catalogue Freshness**: Age distribution at arrival, stacked bar breakdown by release age bands, and average age trends[cite: 4].
3. **Global Coverage**: Regional concentration, top supplying countries, and Non-US title trends[cite: 7].

---

## 🛠️ Tools & Technologies Used

* **Business Intelligence**: Power BI Desktop
* **Data Visualizations**: Custom KPI Cards, Line & Stacked Column Charts, Donut/Pie Charts, Horizontal Bar Charts
* **DAX**: Custom measures for dynamically calculating ratios, percentages, and time-based metrics
* **Data Modeling**: Dimensional model linking titles, genres, release dates, and geographic metadata

---

## 🚀 How to View & Use

1. Clone or download this repository.
2. Open `Netflix_Content_Strategy.pbix` using **Power BI Desktop**.
3. Use the left navigation panel to switch between **Overview**, **Catalogue freshness**, and **Global coverage** pages[cite: 1, 4, 7].
4. Toggle between **All titles**, **Movies**, and **TV Shows** filters at the top of each page for detailed drill-down analysis[cite: 1, 2, 3].

---
