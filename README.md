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
Given that A and B both have the same number of nodes, and fully connected, it can be concluded that $LengthOfV_A = LengthOfV_B$ and that $LengthOfE_A = LengthOfE_B$  
Knowing this, we can create a bijection function $f$. If we label nodes from $V_A$ as $y_1, y_2, ... y_n$, and those from $V_B$ as $w_1, w_2, ... w_n$, we can show that the function is bijective by having $f(y_k) = w_k$, ensuring that each node from one graph maps to a node on the other. This also ensures that the function will be one-to-one and onto, since there is an equal number of nodes in each graph, and each node in one graph will map to only on other.  
Using the knowledge that A and B are both fully connected graphs, and that the bijection is one-to-one and onto, it can be concluded that $\forall u,v$ in either graph, $\exists$ an edge $(u,v)$ such that it is an element of that graph's set of edges. Given that the bijection $f$ is one-to-one and onto, it can also be concluded that $\forallu,v$ in either graph, $\exists$ two corresponding nodes $f(u),f(v)$ on the other graph. Since the other graph is also fully connected, it must be true that $\exists$ and edge $(f(u), f(v)$ such that it is an element of the other graph's set of edges. This falls in line with the definition of what it means for graphs to be isomorphic.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

Got some help from Aiden Newberry with figuring out a good way to word what I was thinking. 
