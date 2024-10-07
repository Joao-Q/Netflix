# 🎬 Netflix Data Analysis Project

## 📚 **Introduction**

Welcome to the Netflix Data Analysis project! The goal of this project is to dive into Netflix's vast content library and discover trends and insights. We aim to answer key questions such as:

- 🍿 **What is the distribution of content types (Movies vs TV Shows) on Netflix?**
- 📈 **How has Netflix's content library grown over time?**
- 🎭 **What are the most common genres on Netflix?**
- 🌍 **How is Netflix content distributed across different countries?**
- 🔞 **How do content ratings vary?**
- ⏳ **How has the duration of movies changed over the years?**

## 🛠 **Data Preparation**

The dataset contains details about Netflix content like title, type, director, cast, country, release year, rating, and duration. Before jumping into the analysis, we performed several data cleaning steps:

- 🧹 **Handling Missing Values**: Missing values in columns like *country*, *cast*, and *director* were filled with 'Unknown' to preserve data for analysis.
- 🗓 **Date Formatting**: Cleaned the `date_added` column by removing whitespace and converting it to a datetime format to study trends over time.
- 🕒 **Duration Column**: For movies, the "min" string was removed from the `duration` column, and values were converted to integers for easier analysis.
- 🚫 **Fixing Incorrect Ratings**: Incorrect ratings like "74 min" and "84 min" were removed to ensure accuracy.

## 🔍 **Exploratory Analysis**

Through Exploratory Data Analysis (EDA), we uncovered several interesting insights:

### 🍿 **Content Type Distribution**
Movies outnumber TV shows on Netflix! A bar plot was used to visualize this difference.

### 🗓 **Titles Added Over Time**
Using the `date_added` column, we saw a sharp increase in the number of titles added since 2015, reflecting Netflix's rapid expansion. 📈

### 🎭 **Top Genres**
We split the `listed_in` column into individual genres and plotted the top 5. "International Movies" and "Dramas" came out on top, showing Netflix's global reach and preference for dramatic content. 🌏🎬

### 🌍 **Content Per Country**
The top 10 countries producing Netflix content were visualized, with the USA, India, and the UK leading the pack. This showcases Netflix’s global content acquisition strategy. 🇺🇸🇮🇳🇬🇧

### 🔞 **Content Ratings**
Analyzing content ratings revealed that Netflix focuses heavily on adult (TV-MA) and teenage audiences (TV-14). Netflix's content is mainly aimed at mature viewers. 📊

### ⏳ **Movie Duration Over Time**
A scatter plot showed that most Netflix movies are within the 90-120 minute range. While no significant trend was detected, it's interesting to see the consistency. 🎥

## 📊 **Conclusion**

The analysis of the Netflix dataset provided several insights:

- 🎥 Netflix’s content library is dominated by movies, although TV shows are also a significant portion of the catalog.
- 🚀 There has been rapid growth in the number of titles added to Netflix in recent years, particularly since 2015, reflecting the company’s aggressive expansion and content acquisition strategy.
- 🎭 The most popular genres on Netflix include International Movies and Dramas, with the United States and India being the top content-producing countries.
- 🔞 Content ratings suggest that Netflix caters primarily to adult and teenage audiences, with a focus on mature content.
- ⏳ While movie durations remain relatively consistent, further analysis could be done to explore whether specific genres or countries influence the length of content.

## 💡 **Recommendations**

- 📈 **Content Strategy**: Given that international content and dramas are popular, Netflix could focus on expanding these categories to appeal to a broader audience.
- 👨‍👩‍👧 **Rating Distribution**: Netflix could introduce more family-friendly content (e.g., "G" or "PG" ratings) to balance its current focus on mature audiences.
- 🌍 **Country-Specific Expansion**: With strong content contributions from countries like India and the UK, further partnerships or investments in these regions may yield continued growth.
  
## 🗂 **Dataset**

The dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)
