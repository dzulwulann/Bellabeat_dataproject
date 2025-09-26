# Bellabeat Smart Device Usage Analysis

## 🧭 Project Overview  
Bellabeat, a wellness-focused wearable brand, wants to expand its reach. This project explores smart device fitness data (steps, activity, and sleep) to uncover user behavior trends. The goal is to provide actionable insights that the Bellabeat team can use to fine-tune marketing strategy, feature prioritization, and user engagement.

---

## 🎯 Business Questions (Ask Phase)  
1. What are key trends in how users use their smart devices (motion, rest, timing)?  
2. How do those trends map to Bellabeat’s target customers?  
3. How can those insights shape Bellabeat’s marketing and user retention strategies?

---

## 📚 Datasets (Prepare Phase)  
- **Daily Activity** — records of daily step counts, active minutes, etc.  
- **Hourly Steps** — per-hour breakdown of each user’s step data.  
- **Sleep Data** — nightly sleep duration and related metrics.  

**Cleaning & preprocessing steps included in the Colab:**
- Parsing timestamps and splitting into separate date / time fields  
- Converting dates to day names  
- Removing outlier records (e.g. > 10,000 steps in an hour)  
- Merging tables appropriately (inner, left joins as needed)  
- Handling missing values and duplicates  

---

## 🔍 Analysis & Visualizations  
The Colab notebook walks through:

1. Aggregating and visualizing **daily average steps by day of week**  
2. Analyzing **hourly activity patterns** (what hours see the most movement)  
3. Exploring **sleep duration trends**, including how many users get less than 7 hours  



---

## 📈 Key Insights (Share Phase)  
- **Weekend vs Weekday**: Saturdays show the highest average activity, while Sundays see the lowest engagement.  
- **Daily Rhythm**: Activity starts rising around 6–7 AM, dips after ~3 PM, then climbs again, peaking near 7 PM before tapering off.  
- **Sleep Patterns**: Out of 24 users, 12 consistently sleep less than 7 hours per night — indicating a potential area for wellness improvement.  
- **Outliers Managed**: Extreme values (e.g. >10,000 steps/hour) were flagged and excluded when analyzing general trends to avoid skew.

---

## 💡 Recommendations for Bellabeat  
- 🔔 **Push reminders or activity challenges** timed around peak hours (e.g. morning and early evening)  
- 🌙 Use **Sundays for wellness or rest-related content**, since users are less active  
- 💤 Emphasize **sleep tracking features** and encourage healthier sleep durations (≥7 hrs)  
- 🎯 Segment users: heavy vs low activity, consistent vs irregular, and tailor messages accordingly  
- 🧪 Experiment with **midday engagement nudges** to smooth the dip in activity (~3 PM)

---

## 🛠 Tools & Technologies  
- **Python** (Pandas, NumPy) for data manipulation  
- **Matplotlib / Seaborn** for charting  
- **BigQuery / SQL** (if pre-processing or large data)  
- **Google Colab / Jupyter Notebook** as the interactive environment  

---

## 📂 Project Structure  
Here’s how the repository is organized:

