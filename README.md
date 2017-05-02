# Investigating exceptional cases among Austin's restaurant health inspections

I scrape the health inspection scores for restaurants in Austin, TX and search for cases
where a restaurant's score change unusually much in a short period of time. Cases of a very 
quick score increase lead us to collusion between the restaurant and the health inspector; or 
to restaurants that achieved impressive improvements thanks to the health inspection system. 
Cases of a very quick score decrease can lead us to cases of health inspector malpractice, or 
to restaurants that have highly inconsistent food-handling practices.

For every pair of consecutive health inspections of a given restaurant, I calculate the change in score
and the number of days that passed between the two inspections. This metric is called 'ratio.'

I create a scatter plot of zip code vs ratio to look at the typical distrubution of ratio values for different parts of the city. This allows us to identify the ratio values that are atypically high or low.

I also create a scatterplot of 200 restaurants with the highest ratio values and plot them on a zip code vs date plane.
This allows us to spot time-related trends. If health inspections are well-regulated to give uniform results across regions and for new and old inspectors, then there should be no discernible clusters.



