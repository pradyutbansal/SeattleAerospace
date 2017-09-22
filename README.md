# SeattleAerospace
Visualisation of Seattles Aerospace Industry

I tried to depict the flow between each of the activity levels. This indicated the connection between the different stages of activity. The size of the node is proportional to its degree and since all the edges are directed, the color indicates the point of origin.

I was unable to get the scales in place, but the top row is for activity 1.1 and the bottom most one is for 4.2 . 

I thought about a variety of different layouts, but decided on the one I tried to implement. I considered doing a heat map to see the relationship between activity and object. A treemap to indicate how the market was divided, but I didnt have any information about their market caps. Given the nodes and edges, I instinctively started by creating a graph and running some statistics on them. However they didnt seem stastically significant and so I didnt use them.

I used this as a means of learning d3, was able to pull this together in a couple of hours. 

I would like to add some more functionality to this, namely:

- make the axes clear
- click on an edge to highlight its connections
- hover on a node to get more information about it.


I was able to figure out what activity was, but still have no idea what the edge label and node object represented.
