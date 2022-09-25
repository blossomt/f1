# lines of inquiry
factors influencing wins
- constructor vs driver
- financing
    - https://www.essentiallysports.com/f1-news-what-are-the-budgets-for-f1-teams-including-mercedes-red-bull-ferrari/ 
    - https://www.researchgate.net/figure/Team-Budget-Data-and-Prize-Money-Distribution_tbl1_277473373
    - an analysis but no data https://f1metrics.wordpress.com/2015/05/01/how-money-predicts-success-in-formula-1/ 
    - 2021 $145m, 2022 $140m, 2023 $135m
    - stored in `./data/budgets.csv`
- weather variations
- pit stop timings


# data notes
- constructor results vs standings: results are race results and points, standings are cumulative points and fluctuating rank position for the year (?)
- results: timing is actual time for 1st place and gap time for rest
- F1 API available from 2018

# plot
- status codes over years - +1 Lap is just how results are recorded. lapped cars dont drive the remaining laps. then seems like timing not recorded 
- visualize weather data and outliers - help how to use year+round as axis for scatter plot in powerbi?

Score tracks based on #loops, gear shifts delta, #pit stops - limit years 
- Difficulty of track: number of loops, delta in gear shift, 
- Safety of track: # accidents, accidents in dry VS wet weather 
- Who controls when you go to a pit stop? How does location of pit stop change?
- Number of visits to pit stop VS final race timing? 

Constructor company - budget, score (per race VS standing), overall ranking
- Number of construction faults on races
- Time taken at pit stops for each type of “repair”. What is the pit stop purpose? 
  Refuel, tyre change, fix, change bumper 
- Tyre quality - how many laps can the tyre work for before replacement
- Car turn off is it more due to construction vs weather?

what impacts pit stops?
weather
driver decides
safety car - can't go faster than it. good time for drivers to do pit stop
less pit stops -> faster timings. check what tyre changes the winners make

just got license, 
- which company to go to. see budget.
- which race to go to - f1 sites look for rural and unpredictable weather. and less gear shifts. 
- weather
- tyre strategy - raining dont need to change tyres, but will prob want to change as they absorb water.

circuits
- downforce level https://sportsdud.com/f1-list-of-power-tracks/
- interactive map and geojson https://github.com/bacinger/f1-circuits

things to try
- play axis for bar chart
- other analysis on nunmber of gear shifts
- has budget affected performance?