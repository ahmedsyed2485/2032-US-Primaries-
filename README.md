# 2032 US Primaries
![US Primaries Pic](https://user-images.githubusercontent.com/63736593/96067835-342dd400-0e60-11eb-8a38-066d2d267c7f.jpg)

#### Predicting the type of Winners in the 2032 US Primaries
## Overview
My goal was to predict the US Primary winners in each county for the Republican and Democratic Party in 2032. Obviously we dont know who will be running 12 years from now, but by using the US Primary results in 2016, along with the predicted US demographics in 2030, we could atleast see which 2016 candidate would win in the future and create an idea of the type of future this county will have.

I used a Random Forest Regression Model to predict the winners in the 2032 US Primaries. Census.gov posted its prediction for how demographics will change in the next 10 years, so I created a dataset of demographics in 2032, I then created a model and trained it on the 2016 US demographics, 2016 US Primary Winners, and the 2032 US demographics. After that, I used my model and tested it to predict the winners in each US county in 2032. I hope you enjoy my results below!

## 2016 US Primaries Analysis Summary

• Hillary Clinton and Donald Trump led the US in total votes with Bernie Sanders and Ted Cruz trailing.

• Ted Cruz dominated the Republican party in Texas, while Hillary easily won the Democratic Party.

• White people, compared to Black and Latinos, are the only race with a positive correlation on Median Household Income.

• Marco Rubio generally won in the richest counties regardless of race, while John Kasich won in counties with the highest white population.

• Bernie Sanders generally won in poorer areas while Hillary Clinton won in all types of demographics.

#### Code and in-depth analysis
https://github.com/ahmedsyed2485/U.S-2016-Primaries/blob/master/Primaries%20.ipynb

## Results
### Republican Party
After applying our model to each county in 2032, our results showed that Donald Trump won even more counties than 2016. On the other hand, counties where Ted Cruz won in 2016 flipped to Donald Trump. Interestingly, John Kasich lost all counties he won in 2016 while Marco Rubio also lost a few counties and only has won 2 counties in 2032. This is interesting as you would think Donald Trump would lose votes with a surge in people of color, but actually Trump won even more counties and dominated the Republican Party.

#### 2016 Republican Candidates
![rep16_results](https://user-images.githubusercontent.com/63736593/96089142-03fc2a80-0e8c-11eb-8cb5-fa4fd111c413.png)

#### 2032 Republican Candidates
![rep32_results](https://user-images.githubusercontent.com/63736593/96089708-d9f73800-0e8c-11eb-94b7-8a863ae6f3ee.png)

#### Code and in-depth analysis
https://github.com/ahmedsyed2485/U.S-2016-Primaries/blob/master/Republican.ipynb

### Democratic Party
After applying our model to each county in 2032, our results showed that the Democratic Party slightly changed. Bernie Sanders lost a few votes to Hillary Clinton, but overall we can see that the Democratic Party remained consistent.

#### 2016 Democratic Candidates
![dem16_results](https://user-images.githubusercontent.com/63736593/96092938-20e72c80-0e91-11eb-88d4-760c89479d9f.png)

#### 2032 Democratic Candidates
![dem32_results](https://user-images.githubusercontent.com/63736593/96093216-7de2e280-0e91-11eb-9b5b-c0f821c5ec92.png)

#### Code and in-depth analysis
https://github.com/ahmedsyed2485/U.S-2016-Primaries/blob/master/Democrat.ipynb

## 2016 Candidate Policies
Hillary Clinton - https://www.ontheissues.org/Hillary_Clinton.htm

Donald Trump - https://www.ontheissues.org/donald_trump.htm

Bernie Sanders - https://berniesanders.com/issues/

Ted Cruz - https://www.ontheissues.org/senate/ted_cruz.htm

Marco Rubio - https://www.ontheissues.org/senate/marco_rubio.htm

## Resources
https://www.census.gov/content/dam/Census/library/publications/2020/demo/p25-1144.pdf
