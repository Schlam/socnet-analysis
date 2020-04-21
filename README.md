## Analyzing social networks to predict viral activity

![cambridge](/images/cambridge_connected.png)

Given a collection of airbnb listings, and the reviewers who have reportedly stayed there, we can construct a graph where each listing is a node. Using the list of distinct ```reviewer_id```'s for each room, any two listings that share a reviewer between within a certain timeframe are then connected on the graph.

This can be used to create a quick visual, or as part of a larger analysis.
