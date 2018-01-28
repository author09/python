# python

# contains python implementations of known algorithms as solutions to specific problems. (Codes written in jupyter notebook)


## Influencer Algorithm:

Objective: 
Use graphs to describe relationships(as Facebook or LinkdIn do), and then assuming that people in a friendship graph can influence their friends, find a small set of people(nodes) that can influence all the others. When implementing a marketing campaign to promote a new product, identifying and influencing this small set to influence the entire friendshipship graph.
 
Each node in a friendship graph is the name of a person, and that person has edges leading from his/her node to the nodes of all his/her friends. In this model, friendship is symmetric (goes both ways): if a is b's friend (there is an arrow from a to b), then b is a's friend (there is an arrow from b to a).
Assume that people in a friendship graph can influence their friends: specifically, assume in this example that if half or more of a person's friends like a song, then that person will decide (be influenced) to like the song too. For odd number of friends, take the ceiling of half of the number.

Use influencer_algorithm.ipynb to find the superset of the nodes that can influence all the other nodes in the friendship graph. Then go on to find the nodes that can be influenced by other subsets of nodes.(use influencer_eg.txt as an example input file)

## Gale-Shapley algorithm
### Stable marriage problem

Suppose that N men and N women want to match in a heterosexual marriage. Each produces a list of his/her preferences, ranking all members of the opposite gender in highest to lowest order of acceptability as a partner. The Gale-Shapley algorithm matches men and women in stable marriages.
Marriages are stable when we cannot find a man and woman, who prefer each other to their match. This scenario can be used to find stable matches in other contexts. For example, this algorithm is used when medical school graduates match with hospitals for their residencies: the students and institutions rank each other and then the algorithm is run, processing these rankings. In this case, the residents propose (act as the men in the description above) and the hospitals accept/reject the proposals (act as the women).

 

