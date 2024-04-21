### README: SC1015 Mini Project - Analysis of Movie Industry Trends

#### Overview
This project by Group 6 explores extensive trends within the movie industry, focusing on the correlation between budget allocations, revenue generation, and the popularity of films spanning from the 1980s to the present day. Utilizing the comprehensive TMDB 5000 dataset, this study offers insights into the financial dynamics and success factors in filmmaking.

#### Objectives
- To trace and analyze revenue trends across decades and identify key periods of significant financial outcomes in the film industry.
- To explore the relationship between the financial investment in movie production (budget) and its revenue returns, examining how this relationship has evolved over time.
- To evaluate the influence of popularity—as measured by metrics within the dataset—on a movie's financial success.

#### Data Description
The TMDB 5000 Movie Dataset comprises data on over 5,000 movies and includes variables such as budget, revenue, popularity scores, release dates, and genre information. This dataset was chosen for its completeness and the depth of information provided, allowing for a robust analysis of the industry's financial and operational dynamics.

#### Methodology
- **Data Acquisition and Preparation**: The dataset was downloaded from Kaggle, and initial data cleaning involved handling missing values, erroneous entries, and standardizing formats.
- **Exploratory Data Analysis (EDA)**: This phase included plotting trends over time using line graphs and generating heatmaps to examine the correlation between variables such as budget, revenue, and popularity.
- **In-depth Statistical Analysis**: We calculated Pearson correlation coefficients to quantify relationships and conducted t-tests to compare different groups within the dataset.
- **Predictive Modeling**: We employed RandomForestRegressor for its efficacy in handling nonlinear relationships and its robustness to overfitting, aiming to predict movie revenues based on budget, popularity, and other factors. Model validation was performed using cross-validation techniques.

#### Findings
The statistical analysis revealed:
- A robust positive correlation between a movie’s budget and its generated revenue, with a correlation coefficient of 0.74.
- Popularity also correlated positively with revenue but was less strong (correlation coefficient of 0.65), indicating other factors also play significant roles.
- Historical trends showed a marked increase in both average budgets and revenues from the 1990s onwards, aligning with the global expansion of the film market and technological advancements in filmmaking.

#### Future Research Directions
- Examination of the impact of digital streaming services on traditional cinema revenue models.
- Analysis of genre-specific trends to determine if certain types of movies are more financially successful or immune to market fluctuations.
- Incorporation of global economic indicators to better understand external factors affecting movie revenues.

#### References
- TMDB 5000 Movie Dataset: [Link to Dataset](https://www.kaggle.com/datasets/anandshaw2001/movie-rating-dataset)
- https://www.geeksforgeeks.org/decision-tree/
- https://www.geeksforgeeks.org/random-forest-algorithm-in-machine-learning/
- https://www.datacamp.com/tutorial/guide-to-the-gradient-boosting-algorithm
- Python Documentation for used libraries (NumPy, Pandas, Matplotlib, Seaborn, scikit-learn)
