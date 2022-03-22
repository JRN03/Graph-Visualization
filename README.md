# Graph-Visualization 
Helps visualize large sets of data and relationships.
Easy to use. Supports manual input of data and links as well as json file uploads
Created using D3.js libraries for the visual graph, otherwise, the rest of the visuals and functionality are coded from scratch.

# Improvements
In the future, I plan to get rid of the "tick" and repositioning of nodes whenever the graph rerenders. 
Will add a feature to change colors of the nodes, as well as a depth first visualization.
I also plan to implement a dijkstra algorithm visualization to show the shortest path from one node to another.

# Uploads
Json files should be in the following format:
```
  {
    "nodes": [
        {"id":"Arceus"},
        {"id":"Salamence"},
        {"id":"Dragonite"},
        {"id":"Dialga"},
        {"id":"Alakazam"},
        {"id":"Rayquaza"},
        {"id":"Magmar"},
        {"id":"Garchomp"},
        {"id":"Zapdos"},
        {"id":"Moltres"},
        {"id":"Articuno"},
        {"id":"Luxray"},
        {"id":"Piplup"},
        {"id":"Charizard"},
        {"id":"Infernape"},
        {"id":"Tyranitar"}
    ],
    "links": [
        {"source":"0","target":"1"},
        {"source":"0","target":"3"},
        {"source":"4","target":"8"},
        {"source":"2","target":"7"},
        {"source":"5","target":"2"},
        {"source":"0","target":"8"},
        {"source":"3","target":"9"},
        {"source":"10","target":"1"}
    ]
  }
