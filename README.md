# EDA
# 🎬 Movie Data Analysis Project

This project analyzes movie datasets using Python libraries like Pandas, Matplotlib, and Seaborn. It focuses on exploring trends in ratings, runtime, release years, popularity, and country-wise production to derive actionable business insights.

## 📁 Dataset Overview

We use a merged dataset containing:
- IMDb scores
- TMDb popularity
- Runtime (minutes)
- Genres
- Country of production
- Release year

## 🔍 Key Insights

### 🎯 Correlation Heatmap
- Shows weak correlation between IMDb scores, TMDb popularity, and runtime.
- No strong linear relationship, indicating diverse factors affect movie success.

### 📊 Visualizations

#### 1. Histogram - IMDb Score
- Most movies score between **5 and 7**.
- Indicates **consistent audience expectations**.

#### 2. Histogram - Release Year
- Surge in movie production post-2000.
- Peak near 2020, slight dip possibly due to **COVID-19**.

#### 3. Pie Chart - Top Genres
- Visualizes percentage of most common genres.
- Helps content creators choose popular themes.

#### 4. Pair Plot
- Displays relationships between multiple numeric columns.
- Useful for initial **exploratory data analysis** (EDA).

#### 5. Bar Plot - Genre Frequency
- Highlights top genres like **Drama**, **Comedy**, **Action**.
- Important for understanding content demand.

#### 6. Bar Plot - Country Production
- Shows which countries dominate film production (e.g., USA, India).
- Guides **regional content strategies**.

#### 7. Line Plot - Runtime vs. Release Year
- Observes trends in how average movie length changes over time.
- Useful for determining changing audience preferences.

## 🛠️ Tech Stack

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

## 📈 Business Use Cases

- Understand **audience preferences** using score distributions.
- Plan investments by analyzing **historical production trends**.
- Guide **genre and content creation strategies** based on data.

## ✅ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/movie-data-analysis.git
   cd movie-data-analysis
