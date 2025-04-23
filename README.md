# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

$A = (V_A , E_A)$, where $V_A$ and $E_A$ are the sets of all nodes and edges in graph A, respectively. $B = (V_B , E_B)$, where $V_B$ and $E_B$ are the sets of all nodes and edges in graph B, respectively.  
Given that A and B are both fully connected, and have the same number of nodes, it can be concluded that $LengthOfV_A = LengthOfV_B$ and that $LengthOfE_A = LengthOfE_B$  
Additionally, since they are both fully connected, any node on A or B will have a number of edges equal to the length of the set of every node in its respective graph.  
This means that for any edge between node you select in either graph, you can find an edge in the other graph such that the edge exists within that graph's set of edges.  
More specifically, you can find any edge $(u,v) \in E_A$ such that another edge $(f(u), f(v)) \in E_B$ Alternatively, you can also find any edge $(u,v) \in E_B$ such that another edge $(f(u), f(v)) \in E_A$
