NBA Game Outcome Prediction via Four Factors

I wanted to know what actually wins basketball games.
I took a dataset of over 13,000 regular season NBA games and compared a Random Forest classifier against a Logistic Regression model to find out which factors matter most. Both models pointed to the same conclusion: defensive metrics outweigh offensive ones, with effective field goal percentage and turnovers being the biggest drivers of winning. Logistic Regression ended up being the stronger model, hitting 96.1% accuracy.
The project is rooted in Dean Oliver's Four Factors framework, which breaks winning down into four key areas: shooting efficiency, turnovers, rebounding, and free throw rate. The results back up that defense, and specifically how well you limit the opponent's shooting, matters more than what you do on offense.

Results

Logistic Regression: 96.1% test accuracy
Random Forest: 89.2% test accuracy
13,186 game records analyzed
Defensive eFG% identified as the single most predictive variable across both models

Tools
Python, scikit-learn, pandas, seaborn, matplotlib, 5-Fold Cross-Validation
