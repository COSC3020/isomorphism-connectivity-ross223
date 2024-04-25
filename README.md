[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Assume that graph A has 4 nodes a, b, c, d with edges between (a, b), (b, c), and
(c, d). To be isomorphic to B, there must be a one-to-one and onto funtion such that
each node in A can be mapped to exactly one node in B. Therefore, if we take graph
B to have 4 nodes e, f, g, h with edges between (e, f), (f, g), and (g, h), a function
mapping a to e, b to f, c to g, and d to h results in a bijection, as each node in A
is mapped to exactly one node in B with no remaining nodes.

Therefore, graphs A and B are isomorphic by the definition, and since they are both 
not completely connected, this means that two graphs to not have to be completely 
connected to be isomorphic.
