# Purpose of this project
Predict the AFL final 2021 using the available data. At the time of this project, only 7 rounds were available for 2021 season.
# Method
Dominance matrix  
The theory of this method can be found in the file "Dominance Matrix article_Annotated by Milo Joronen.pdf". It has been annotated by me to foster deeper understanding.
# Tool
Excel  
The excel file "AFL results prediction" contains the results of matches that were turned into matrixes for dominance matrix calculations. The calculation are shown in the formulas within its relevant cells.  
There are 3 tabs in the file.  
- Tab "2019 results" are the main tab with 2019 results that were used to test multiple predictive performing matrices to shortlist the best.  
- Tab "2019 results away team bonus +" is similar to tab "2019 results" but here we take away 5 points from the home team and give 10 points for the away team. This is based on the assumption that the home team has the advantage of the crowd soaring for them and therefore increases their spirit and thus their performance. On the other hand, the away team doesn’t have such advantage so if the away team wins, they should deserve some credit.  
- Tab "2021 new results" is the tab that ultilises dominance matrix models built in "2019 results" tab to predict the results of 2021 AFL final.
# Report
  The file "MiloJoronen_DominanceMatrice.pdf" contains thorough explaination of the project methodology, results and limitations.
