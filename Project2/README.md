# Exact Inference with Probabilistic Graphical Models

In this problem set, we will make exact inferences about probabilistic graphical models using the state-of-the-art graphical model packages in our most comfortable programming languages, and understand those exact algorithms. You can find tutorials in Python, R (slides and book) and Matlab. The function calls in different packages are different, but the point here is that we make graphical model our actionable machine learning tool in this course. 
We will work with the chest clinic graphical model (below). Please moralize, triangulate and construct a junction tree from this graphical model. Then use message-passing algorithm to find the joint probability of "tub=yes, lung=yes, bronc=yes", given evidence that "asia=yes, xray=yes". 
Problem 1: Draw the moral graph, triangulated graph and the junction tree. Explain why the "running intersection property" is satisfied in your junction tree.

Problem 2: Describe how the different terms on the right hand side of "p(V ) = p(a)p(t | a)p(s)p(l | s)p(b | s)p(e | t, l)p(d | e, b)p(x | e)" are distributed among the different juction tree clusters. Write out the messages using these terms and verify that the message passing algorithm indeed gives the cluster marginals.
[Optional] Problem 3: Find the joint probability with MCMC.

Format: ![Map](D:\pr)
