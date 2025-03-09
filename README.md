# Union Find Visualizer

## How to use?

- Download the index.html file
- Make sure you have a web browser (Firefox, Microsoft Edge, Google Chrome, or something else)
- Make sure javascript is enabled
- Open the html file with your preferred browser
- Enjoy!

## Features:

- Create a new graph with 'N' nodes
- Union two nodes
- Find the root of a node
- Check if two nodes are connected

## Implementation:

- Quick union approach, with optimized union (Union by rank (tree height) )
- Optimized find with path compression

## Time complexity:

|  Union-find Constructor |  	Find  |  Union | Connected  |
|---|---|---|---|
|  `O(N)` 	 |  `O(α(N))` | `O(α(N))`   | `O(α(N))`  |

Note: `N` is the number of vertices in the graph. `α` refers to the Inverse Ackermann function. In practice, we assume it's a constant. In other words, `O(α(N))` is regarded as `O(1)` on average. 
 	 	
Source: [Leetcode](https://leetcode.com/explore/learn/card/graph/618/disjoint-set/3843/)
