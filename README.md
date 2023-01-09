# PyBer_Analysis
## Project Overview
Background

The CEO of a ride sharing company(Pyber) has asked us to create a summary Data frame of ride-sharing data by City Type. To do this, we'll use Pandas and matplotlib to create visual representation of total weekly fares by city type. This information will be used by the company to make informed decisions about how they might be able to increase performance and revanue. 

This new assignment consists of two technical analysis deliverables and a written report to present your results: 

- Deliverable 1: A ride-sharing summary DataFrame by city type
- Deliverable 2: A multiple-line chart of total fares for each city type
- Deliverable 3: A written report for the PyBer analysis (README.md)


## Resources
- Data Source: [city_data.csv](https://github.com/abrodyyy/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/abrodyyy/PyBer_Analysis/blob/main/Resources/ride_data.csv)
- Software: [Python 3.9.12](https://www.python.org/downloads/release/python-3912/), [Visual Studio Code, 1.70.2](https://code.visualstudio.com/updates/v1_70), [Jupyter Notebook 6.4.8](https://jupyter-notebook.readthedocs.io/_/downloads/en/v6.4.8/pdf/)


## Results
- The number of total rides is significantly higher in urban cities than suburban and rural areas, with rural cities having the least of the group.
- The number of total drivers available is also higher in urban cities than suburban and rural areas, with rural cities having the least of the group.
- Given the higher number of rides and drivers in Urban cities compared to the others, it's expected that the total fares in that area be significantly higher. While that is true witht the total fares in the areas, the total fare per ride is actually the lowest in the Urban areas. This might be able to be attributed to the shorter distance being traveled in an urban city vs suburban and rural. We would need additional data about the distance traveled to determine if there is a correlation present. 
- The average fare per driver in Rural areas is the highest, with suburban being second, and Urban being the lowest fares. This makes sense given that there area the least amount of drivers available in rural cities, and the most available in urban cities. 
- Overall, we can see that there is significantly higher supply and demand in urban cities for rides compared to suburban and rural cities. 


## Summary
- To increase profits in Urban and Rural areas, I would reccomend increasing the amount of drivers available, and possibly lowering the cost per ride if possible. We could even run a promotion for new riders allowing them a lower rate to gain new customers. 
- We know there is a high demand in urban areas, we may be able to increase prices during the busiest hours of the day, to offset any price drops we're offering in the outlying areas. 
- We can also add a price structure depending on the number of riders. For example rides for 4+ people would be charged an additional $2 per ride. 