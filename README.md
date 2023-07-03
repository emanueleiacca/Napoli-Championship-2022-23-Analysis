# Napoli-Championship-2022-23-Analysis
This project analyzes the performance of Napoli, the Italian football team, during the season. The analysis is based on web scraping data from the website fbref.com.

## Project Description
The main goal of this project is to analyze Napoli's performance throughout the season by comparing their actual goals scored and goals conceded with their expected goals (xG) based on statistical models. The analysis provides insights into the team's attacking and defensive performance, as well as the variations in performance during different periods of the season.Overall, the analyses provided insights into Napoli's gameplay, formation choices, shooting performance, and passing efficiency. It highlighted the importance of ball possession, showcased individual player performance, and identified key players and their contributions to the team.

## Technologies Used
The project is implemented using the following technologies:

R - a programming language and environment for statistical computing and graphics.
R packages: rvest, ggplot2, dplyr, cluster, FactoMineR, factoextra - used for web scraping, data manipulation, clustering algorithms, PCA analysis, and data visualization.

## How to Use
To use this project, follow these steps:

Clone the repository to your local machine.

Make sure you have R and the required packages installed.

Open the R script file (analysis.R) in your preferred R development environment.

Run the script to perform the web scraping and analysis.

The script will generate various graphs and provide insights into Napoli's performance.

## Results and Findings
The analysis reveals the following key findings:

Napoli had an overall overperformance in terms of goals scored compared to expected goals (xG).

The team's attacking performance was strong throughout the season, with a positive difference between goals scored and xG.

The defensive performance varied during different periods of the season, with better performance in the first half and a slight decline in the second half.

The performance before and after the World Cup break showed no significant drop in performance, contrary to popular belief.

The 0-4 loss against AC Milan had a noticeable impact on the team's performance, particularly in defense.

Ball Possession:The analysis showed that Napoli had the highest ball possession in Serie A.
There was a weak negative correlation between ball possession and the result obtained, indicating that higher ball possession did not guarantee more favorable results.

Formation:Napoli predominantly used the 4-3-3 formation throughout the season, with Zielinski as a midfielder.
The 4-2-3-1 formation was used when key players were unavailable, with Zielinski or Raspadori as a trequartista (TRQ).

Shot Analysis:The correlation analysis showed predictable results, with no significant findings.
A cluster analysis divided the players into three groups, with the third cluster consisting of top players like Kvaratskhelia and Osimhen.

PCA (Principal Component Analysis):PCA was used to analyze shooting statistics, and it provided a comprehensive overview of player performance.It revealed insights such as players seizing opportunities, subbed-in players performing well, and the overall distribution of player stats.

Passing Analysis:The completion rate of passes was analyzed, as it is a critical factor in Napoli's style of play.
Lobotka was identified as one of the key players due to his high completion rate.
A boxplot was used to visualize completion rates by player.

Passing Cluster Analysis:Cluster analysis was performed on passing statistics.
An optimal number of clusters (3) was determined using the elbow method.
Cluster assignments were made, and players were grouped based on their passing performance.
