# Netflix Data Analysis

**Overview:-**

This project focuses on analyzing a Netflix dataset to explore patterns and insights related to movies and TV shows available on the platform. The main objective was to understand Netflix’s content trends,       audience preferences, and growth over the years using data cleaning, preprocessing, and visualization techniques.

Dataset Information:-

No missing values or duplicate records were found.

The Release_Date column was converted into a proper datetime format, and only the year was extracted for analysis.

Columns like Overview, Original_Language, and Poster_URL were dropped as they were not useful for analysis.

The Popularity column contained noticeable outliers.

The Vote_Average column was categorized for better understanding.

The Genre column contained comma-separated values and extra spaces, which were cleaned and converted into categorical data.

Process and Analysis:-

The data was cleaned and processed using Pandas and NumPy. Visual analysis was performed with Matplotlib and Seaborn to identify key trends.
Some of the insights include:

Popular genres and their frequency over time.

Trends in content release by year.

Relationship between viewer ratings and popularity.

Growth pattern of Netflix content over recent years.

Key Learnings:-

Data cleaning and preprocessing

Feature engineering and handling categorical data

Exploratory Data Analysis (EDA)

Data visualization and insight generation

Conclusion:-

This project helped in understanding how Netflix’s content library has evolved and what kind of content resonates most with viewers. The findings can be used as a foundation for future projects such as recommendation systems or content popularity prediction models.
