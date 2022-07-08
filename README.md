\\\\ BREADTH FIRST SEARCH ALGORITHM ////
- completed specific functions as part of CS50AI course
- Used breadth first search algo to find the shortest path between two states
- Shortest path returns the shortest path linking two actors together
- Actors = state
- Movies = actions
- Data recieved via IMDB

***** I was supposed to implement the shortest_path() function
I did so using BFS and then optimized it by allowing it to pick up whether the goal state is present within the frontier,
as opposed to only checking node that was removed from the frontier.
I implemented find_path() function to help me do this.
Other functions are credited to CS50
