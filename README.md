## 📊 Netflix Dataset Analysis & Visualization

### 🔍 Project Overview
This self-learning project focuses on cleaning, exploring, and visualizing the Netflix Titles dataset using Python.  
The main goal was to understand real-world data and improve data analytics skills using `pandas`, `matplotlib`, and `seaborn`.



### 📁 Dataset
- **Source**: [Kaggle – Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Features** include:  
  `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`



### ✅ Steps Completed
- Data Cleaning
  - Handled missing values in `director`, `cast`, `country`, and `rating`
  - Filled unknown or missing values with logical defaults (`'Not Rated'`, `'Unknown'`, etc.)
  - Converted `date_added` to proper datetime format
- Feature Extraction
  - Extracted `year_added` and `month_added` from `date_added`
  - Processed `listed_in` column to extract genres
- Data Visualization
  - Count of Movies vs TV Shows
  - Top 10 most common genres
  - Content rating distribution
  - Top countries by title count



### 📊 Key Insights
1. Netflix has released more **Movies** than **TV Shows**.
2. The most common genres are **International Movies** and **Dramas**.
3. Top contributing countries are **United States** and **India**.




### 🛠️ Tools & Libraries
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn



### ⚠️ Notes
- A warning was observed during visualization:  
  *"Palette assigning without 'hue' is deprecated and will be removed in v0.14.0"*  
  This was noted for future compatibility with Seaborn.

---
