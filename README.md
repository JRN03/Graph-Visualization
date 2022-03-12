# Graph-Visualization 
Helps visualize large sets of data and relationships.
Easy to use. Supports manual input of data and links as well as json file uploads

#Uploads
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
