# Best neighborhoods to setup an office in Toronto

## 1. Introduction
Problem: A contractor is trying to start their own business in Toronto, which neighbourhood would be best suited to setup 
their office? Venues that should be nearby:
1. Coffeeshop for getting coffee quickly
2. Public transport to easily come to the office
3. Restaurants to have lunch and diner meetings

Audience: Contractors who wish to open an office in Toronto.

## 2. Data
The sources that will be used:
- information about the postal codes and neighbourhoods in Toronto: [link](https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)
- information about all the venues in the different neighbourhoods will be retrieved from FourSquare

I will combine both sources into one dataset and then cluster all the neighbourhood based on the venues present.
After that I will select the top neighboorhood that have the most coffeeshops, public transport availability and 
restaurants.

## 3. Methodology
For exploratory data analysis I first explored the different neighborhoods in Toronto. After loading the venues 
information from FourSquare I explored that information also.

For clustering the neighborhoods based on the top 10 most common venues I used K-mean clustering method. I chose this 
algorithm because it is a simple and very powerful algorithm.

## 4. Results
Based on the results we can state that cluster 3 has the most suitable venues for an office. Venues like coffeeshops 
and restaurants.

## 5. Discussion
The distribution among the clusters varies a lot. Cluster 3 is very big and clusters like 2, 4 and 5 only contain 1 
or 2 neighborhoods. This is an interesting fact that is worth diving into in future research.

## 6. Conclusion
We can conclude that there are specific neighborhoods that are more suitable for setting up an office than others. 
Luckily there is a large amount of suitable neighborhoods in Toronto, so there is a lot to choose from.





