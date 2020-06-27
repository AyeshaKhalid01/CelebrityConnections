# CelebrityConnections
Using IMDB data this program shows how celebrities are related.
#### Disclaimer
The large data will take a minute to load due to its size.

### Problem
In this problem, we’re interested in finding the shortest path between any two actors by choosing a sequence of movies that connects them. 

## Methods
#### Breadth First Search
Implemented in degrees.py by using a Queue data structure. Best approach when looking for the shortest path.

#### Depth First Search
Implemented in DFS.py by using a Stack data structure. This approach finds the target however it does not always find the shortest path.

#### Example 
```$ python degrees.py large
Loading data...
Data loaded.
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
```
