
# 🎬 Netflix Movie Data Analysis

This project analyzes a Netflix dataset using Python to uncover trends in genres, popularity, ratings, and other interesting insights. The analysis is performed in Jupyter Notebook using pandas, matplotlib, and seaborn.

---

## 📁 Project Overview
The goal of this project is to explore Netflix movie data and visualize patterns such as:
- Most common movie genres  
- Genre popularity distribution  
- Ratings and their impact on popularity  
- Movies with the highest popularity scores  

---

## 🧰 Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation and cleaning  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical data visualization  

---

## 📊 Key Steps in the Analysis
1. **Data Loading & Cleaning**
   - Removed duplicates and handled missing values.
   - Converted columns to appropriate data types.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed unique genres and their frequency.
   - Found the most popular and top-rated movies.
   - Visualized the genre distribution using count plots.

3. **Visualization**
   - Created insightful charts using `matplotlib` and `seaborn`.
   - Example: Genre distribution bar chart:
     ```python
     sns.catplot(
         y='Genre',
         data=df,
         kind='count',
         order=df['Genre'].value_counts().index,
         color='#FF7F50'
     )
     plt.title('Genre Column Distribution')
     plt.show()
     ```

4. **Insights**
   - Identified which genres are most common on Netflix.
   - Found which movie(s) have the highest popularity.
   - Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.
   - we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movies popularity
   - Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action, Adventure and Sience Fiction.
   - The united states, thread' has the highest lowest rate in our dataset and it has genres of music, drama, 'war', 'sci-fi and history
   - year 2020 has the highest filmming rate in our dataset.


---

## 📂 Project File
- `Netflix movie data analysis.ipynb` → Contains the complete code and visualizations.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Netflix-Data-Analysis.git
