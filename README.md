# Analysis of Football Events

This project delves into the performance of football teams, players, and events in Europe's top five leagues between 2015 and 2017. Through data analysis and visualization, we aim to uncover interesting insights about goalscorers, match outcomes, and key moments in football matches.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Objectives](#objectives)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)

## Introduction
Football, also known as soccer, is a global phenomenon with millions of fans. In this project, we explore detailed event data from top European leagues to analyze key moments, such as late winners, prolific goalscorers, and how goals were scored. This analysis provides insights into individual performances, team strategies, and the overall dynamics of the beautiful game.

## Data
The dataset contains events from football matches in Europe's top five leagues: the English Premier League, La Liga, Serie A, Bundesliga, and Ligue 1, covering the 2015 to 2017 seasons. Each event is characterized by its timestamp, the player involved, the type of event (goal, foul, etc.), and other key attributes.

## Objectives
1. **Identify the top goalscorers** across the leagues and analyze their performances.
2. **Analyze match outcomes** to determine which teams excel in clutch moments, focusing on late goals that decide matches.
3. **Break down how goals are scored**, such as by header, left foot, or right foot.
4. **Visualize key patterns and trends** in the data.

## Analysis
The analysis is split into several key sections:
1. **Top Goalscorers:** We identify and visualize the top 25 players by goal count.
2. **Late Winners:** We focus on goals scored after the 85th minute in non-draw matches to determine which teams consistently perform under pressure.
3. **Body Part Breakdown:** Goals are analyzed based on how they were scored—using the head, left foot, or right foot.
4. **Team Performance:** Teams with a fighting spirit, who frequently score late winners, are highlighted.
5. **Ronaldo vs Messi Rivalry:** A deep dive into the long-standing rivalry, comparing their performances in various event categories to distinguish their playing styles and contributions.


## Visualizations
The project includes several visualizations created using Matplotlib, Seaborn, and Plotly to provide clear, engaging insights:
- **Top Goalscorers Bubble Plot:** A visualization of the top 25 goalscorers, color-coded and sized by the number of goals.
- **Last-Minute Winners Plot:** A bubble plot highlighting teams that excel in scoring decisive late goals.
- **Goals by Body Part:** Bar plots showing the breakdown of goals by body part (header, left foot, right foot).

## Conclusion
This analysis reveals that legendary players like Cristiano Ronaldo and Lionel Messi dominate European football with their goal-scoring prowess. Teams such as Tottenham, Sevilla, and Rennes consistently perform well in high-pressure moments, while Serie A's top scorer, Higuain, far outpaced his peers. The analysis also provides insights into the tactical approaches of different teams and leagues.

## How to Run
To run the analysis:
1. Clone the repository:
   ```
   git clone https://github.com/yassergribi/Analysis-of-Football-Events.git
   ```
2. Install the necessary dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```
   jupyter notebook Analysis_of_Football_Events.ipynb
   ```
4. Run the cells in the notebook to reproduce the analysis and visualizations.

## Dependencies
The project requires the following Python libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
