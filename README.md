# python
########################################################################################
#contains python implementations of known algorithms as solutions to specific problems. (Codes written in jupyter notebook)#
########################################################################################

Influencer Algorithm:

Objective: 
Use graphs to describe relationships(as Facebook or LinkdIn do), and then assuming that people in a friendship graph can influence their friends, find a small set of people(nodes) that can influence all the others. When implementing a marketing campaign to promote a new product, identifying and influencing this small set to influence the entire friendshipship graph.
 
Each node in a friendshiop graph is the name of a person, and that person has edges leading from his/her node to the nodes of all his/her friends. In this model, friendship is symmetric (goes both ways): if a is b's friend (there is an arrow from a to b), then b is a's friend (there is an arrow from b to a).
Assume that people in a friendship graph can influence their friends: specifically, assume in this example that if half or more of a person's friends like a song, then that person will decide (be influenced) to like the song too. For odd number of friends, take the ceiling of half of the number.

Use influencer_algorithm.ipynb to find the superset of the nodes that can influence all the other nodes in the friendship graph. Then go on to find the nodes that can be influenced by other subsets of nodes.(use influencer_eg.txt as an example input file)

