# Title: 🍽️ Restaurant-tips-analysis
![image](https://github.com/user-attachments/assets/ebff8e00-25ee-4143-9714-97566b5eb796)
This project performs an in-depth analysis of a restaurant tips dataset. The goal is to understand various factors influencing the tips received by staff, identify patterns, and draw insights that could help optimize service and tip generation.
# Data Description
The dataset consists of information from 244 restaurant bills, collected in the US in 1987. It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.
## Source of the data
Source: https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv
## Description of the dataset
The dataset typically includes information such as:
- total_bill: The total cost of the meal.
- tip: The amount of tip given.
- sex: Gender of the person who paid the bill (e.g., Male, Female).
- smoker: Whether there was a smoker in the party (e.g., Yes, No).
- day: Day of the week (e.g., Thu, Fri, Sat, Sun).
- time: Time of day (e.g., Lunch, Dinner).
- size: Size of the party.
## How to access or download the data
This dataset is often available as part of popular data science libraries like Seaborn in Python. If not directly included in the repository, you can typically load it directly within a Python environment using:
- import pandas as pd
- import matplotlib.pyplot as plt
- df = pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
# Main Goals
The primary goals of this project are to:
- Identify correlations between different features (e.g., day of the week, gender, smoking status) and the tip amount.
- Visualize key trends and patterns to gain insights into tipping behavior.
# Results
- The data indicates that the tipping behavior of smokers and non-smokers is very similar, both in terms of average tip amounts and the distribution of tips. Other factors, apart from smoking habits, appear to influence the tip amount more significantly.
- Males tend to tip slightly more than females. Males have higher average and median tip values compared to females. Males are also capable of tipping significantly larger maximum amounts than females. However, it's important to note that the difference in average and median values is relatively small (around $0.25). This suggests that while males may tip a bit more statistically, this difference might not be substantial in the practical context of general tipping behavior, where both genders tend to tip relatively small amounts.
- There are differences in tipping behavior on weekend days. Sundays tend to yield higher average and median tips. However, Saturdays do not necessarily bring in more tips on average, although they might have exceptionally large tips not observed on Sundays. This suggests that "weekend" does not uniformly equate to "more tips"; Sundays appear to be the more profitable day in terms of average tips.
- Tips during dinner times tend to be slightly higher than the overall average tip, but this difference is quite modest.
