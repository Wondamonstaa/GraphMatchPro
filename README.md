# GraphMatchPro
The following project focuses on developing a distributed program designed for parallel processing of large graphs, generated through the utilization of the Network Graph Simulation platform (NetGraphSim) involving AWS EC2 IaaS.

Originally designed and created by Mark Grechanik, Ph.D., UIC

The objective of this project is to develop a sophisticated program for the parallel distributed processing of extensive graphs. 
The primary goal is to extract comprehensive matching statistics comparing original graphs with their perturbed counterparts. 
To achieve this, the project involves a multi-step process.

1. Graph Analysis and Similarity Metrics:

The initial step involves computing either a YAML or CSV file that provides valuable insights into the distribution of nodes and edges within the generated graphs. 
These insights are based on a similarity metric calculated using a specialized formula.

2. Perturbed Graph Analysis:

Subsequently, the program will determine the likelihood that each node or edge in the graph has been modified, added, or removed in the perturbed version of the graph. 
This analysis considers the possibility that a modified node can be interpreted as a previously existing node being deleted and a new node being added with parameters resembling the deleted node. 
This determination relies on a finely-tuned graph matching algorithm designed uniquely for this purpose.

3. Comparison with Golden Set:

To assess the accuracy of the modifications detected, the program will compare the results with a reference set of changes established by NetGraphSim, a well-known tool for generating perturbed graphs. 
This step helps validate the precision of the algorithm.

4. Evaluation Metrics:

In the final phase, the project will produce an estimation of the algorithm's performance akin to precision and recall ratios. 
This evaluation will be based on rigorous experimentation and will provide valuable insights into the effectiveness of the developed algorithm.
