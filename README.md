This repository is my solution to the 2019 Women's NCAA Kaggle Competition. I won a Solo Silver Medal.

My Kaggle profile: https://www.kaggle.com/kaito510/competitions

I assumed that all 1st, 2nd and 3rd seed teams will win their first round match because my probabilities are clipped from 0.025 to 0.975 and teams seeded from 1 to 3 has won their first round match 299 out of the last 300 historical matches (i.e. much greater than 0.975 of the time). This is the only set of overrides I made.

# How to use this respository:

Data folder named as "womens-machine-learning-competition-2019" is available for Kagglers with link below:
https://www.kaggle.com/c/womens-machine-learning-competition-2019/data

"results.metrics.df.rds" can be created by running the four process files in order from "1." to "4."

"gradientBoost50.025.csv" (the competition submission file) can be created by running "8. Stage2 submission.Rmd"

# Glossary of metrics:

Seeding: Each team is seeded from 1 to 16 (generally from strongest to weakest) by the NCAA.

Home Advantage: Teams seeded from 1 to 4 play their first two rounds at home and thus have home advantage for those matches.

Form: For example, if an 8th seed reaches the third round, it means it “took” a 1st seed’s spot (i.e. are in fantastic form) quite likely by beating the 1st seed during the second round.

Adjusted Win Percentage: This essentially “weighs-out” the win percentage by adding more weight to away-wins and home-losses, vice-versa. Reference: https://twitter.com/marchmadness/status/1067063960753573889

Net Efficiency: This essentially measures how efficiently a team converts possession into points relative to how much they have allowed their oppositions to efficiently convert possession into points. Reference: https://twitter.com/marchmadness/status/1067063960753573889
