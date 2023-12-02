# Tableau Football Dashboard - https://public.tableau.com/app/profile/aishwarya.belekar/viz/OmkAishApuDashboard/Dashboard1?publish=yes

## Introduction

Welcome to the Tableau Football Dashboard repository! This dashboard is designed to present football data, including player market value trends, player comparisons, and other relevant insights. The football industry relies heavily on statistical analysis for player performance improvement, scouting, injury prevention, and overall team quality enhancement. This dashboard harnesses the power of data to help teams, fans, journalists, and sports analytics companies make informed decisions.

## Dataset

### Dataset 1 – FIFA 19 Kaggle Dataset

- **Description:** This dataset contains various numerical and categorical parameters related to football players.
- **Numerical Parameters (Measures):** Potential, skills, work-rate, overall CV, agility, strength, reflexes, balance, passing, accuracy, etc.
- **Categorical Parameters (Dimensions):** Nationalities, continents, clubs, name, body type, playing position, preferred foot, contract period, etc.
- **Important Columns and Their Description:**
  - **Name:** Name of football players (Categorical).
  - **Overall, Potential:** Player performance rating on a scale of 0 to 100 (Ratio).
  - **Skill Moves, International Ranking, Preferred Foot:** Player skill ratings on a scale of 1 to 5 (Ratio).
  - **Work Rate:** High, medium, or low (Category).
  - **Body Type:** Lean, normal, or stocky (Categorical).
  - **Player’s individual skills:** Crossing, finishing, volleys, dribbling, ball control, etc. (Ratio).

### Dataset 2 – Players Data

- **Description:** This dataset provides information on market and transfer values, including player attributes.
- **Important Columns:**
  - Player Id, Player Name, Club Id, Full Club Name, Current Club Id, Country Of Citizenship, Country Of Birth, Date Of Birth, Position, Market Value In GBP, Highest Market Value, Agent Name, Contract Expiration, Domestic Competition, Club Name, etc.

## Data Preprocessing

To ensure data accuracy and usability, we performed preprocessing tasks, including cleaning a column in the first dataset and using Python (with pandas) to convert values to the appropriate format. Additionally, the position column in the FIFA 2019 dataset required cleaning, which was done using Tableau.

## Dashboard Users

1. **Football Teams:**
   - Utilize visualizations for player performance analysis, scouting, injury prevention, and overall team quality enhancement.
   
2. **Fans:**
   - Compare favorite players, analyze team performances, and gain insights into various aspects of football.
   
3. **Journalists and Other Media:**
   - Write informative articles based on data parameters, contributing to awards and accolades for teams and players.
   
4. **Sports Analytics Companies:**
   - Use data to consult teams, provide advice on improvement strategies, and contribute to the overall understanding of the game.

## Questions and Plots

### Q1. Plot Top N Highest Valued Players
- Multi-Line Bar Chart
- Interactive Slider to select the top N players

### Q2. Number of Players per Country with Market Value Above X
- Bar Chart

### Q3. Distribution of Players and Their Market Value Based on Age
- Dot Plot with interactive controls for threshold

### Q4. Player Comparison Based on Certain Attributes
- Bar Chart or other visual with player names/photos on the x-axis

### Q5. Clubs with Highest Valued Players and Squad Value
- Bar Chart with interactive controls for top N clubs

### Q6. Top 10 Player Details
- Text Table with color hue highlighting

### Q7. Comparison of Overall Scores Based on Preferred Foot
- Bar Graph

### Q8. Greatest Number of Positions Played
- Bar Chart

### Q9. Statistics of Nations Participating in FIFA
- Symbol Map with interactive controls

### Q10. Age Distribution-wise Work Rate
- Multi-Line Chart

### Q11. Relation Between Potential vs Age
- Continues Line Chart

### Q12. Top N Player Details with Value, Nationality, Position, Release Clause
- Interactive Heat Map

## List of Interactive Controls

1. Slider Bar for Top N Values (Q1)
2. Slider Bar for Market Value Threshold (Q2)
3. Interactive Controls for Age Distribution Threshold (Q3)
4. Drop-downs for Player Comparison (Q4)
5. Slider Bar for Top N Clubs (Q5)
6. Slider Bar for Max 10 Values (Q6)
8. Drop-down for Positions Played (Q8)
9. Drop-down for Number of Records per Country (Q9)
10. Drop-down for Age Group Bins (Q10)
12. Top Player Slider (Q12)

Feel free to explore the dashboard and gain valuable insights into the world of football!
