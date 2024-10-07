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

Our analysis provided several key insights into Netflix’s content strategy:

- 🎥 Netflix's library is mostly made up of movies, although TV shows are a big part of the collection too.
- 🚀 Netflix’s content library has grown significantly, especially since 2015, thanks to the platform’s aggressive expansion.
- 🎭 The most common genres include "International Movies" and "Dramas", indicating Netflix's global appeal.
- 🌍 Countries like the USA and India are top contributors, supporting Netflix's global content acquisition.
- 🔞 Most of Netflix's content is rated for mature audiences, with a focus on adult and teenage viewers.
- 🎥 Movie durations remain consistent, mainly falling between 90-120 minutes.

## 💡 **Recommendations**

Here are some suggestions for Netflix to consider:

- 📈 **Content Strategy**: Given the popularity of international content and dramas, Netflix should continue expanding these categories to attract a wider audience.
- 👨‍👩‍👧 **Rating Distribution**: Netflix could introduce more family-friendly content (G or PG ratings) to appeal to younger audiences.
- 🌍 **Country-Specific Expansion**: Netflix should strengthen partnerships in top content-producing countries like India and the UK for sustained growth.
