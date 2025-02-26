# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

With this formal definition, we can argue with it to prove that these two graphs are isomorphic. Within each graph, they have the same number of nodes, no matter if it is A or B. They are also completely connected, hence for every vertex there is an edge going to another vertex. Each graph contains this. If we wanted to map them in another way, we still have the same number of nodes, so the same number of vertices crossing over. For example, if we have two nodes from graph A and try to map those to all the nodes in graph B if graph B had 10 nodes, this would not be a bijection. The reason for this is because they do not have a one-to-one mapping, resulting in these two graphs not being isomorphic. Using a translator function f, if two graphs are isomorphic, we can look at two vertices attached by an edge and use this function to translate this connection to the other graph. So, if we have two vertices that are connected, (u, v), then by using f, (f(u), f(v)), we can see if this mapping is correct and if the structure of the graphs are the same. When checking for mapping, you must check the degree, and since this is a connected graph, all degrees are the same. So, choose a node and find its path (the nodes that are connected through an edge). Then, try mapping this node to another node in the second graph, checking if the second graph as the same edge structure. Names do not matter, however how the edges are connected does. Since this is a connected graph, all nodes have only one edge connecting them to another node so mapping will work as long as the node numbers are the same. If, however, they are not isomorphic, the edges will not pair up. To try all of these possible connections, you can use an approach, that I have practiced more in augmenting paths, where if a mapping does not work, try a different path. Since these graphs (A and B) are completely connected and have the same amount of nodes, the paths will be found and these graphs will be isomorphic. To clarify, each pair of nodes need to be isomorphic to the other graph, if one pair is not isomorphic, the whole graph is not isomorphic with the other graph, this however is not the case for A and B since they are completely connected and have the same amount of nodes. So, given a node in graph A, we first look at the nodes connected, and see the degree. Then find a corresponding node in graph B (one with the same degree), we can track the nodes  connected and see if the paths match (the path on A = the path on B). Since the graphs are fully connected and have the same amount of nodes, finding a node is easy since all nodes will have the same degree. 

I used the class slides and video on graphing. I also got help from the TA in lab and office hours.

I submitted this work Fall 2024

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
