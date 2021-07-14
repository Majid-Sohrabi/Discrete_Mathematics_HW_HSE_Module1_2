# Discrete_Mathematics_HW_HSE_Module1_2

[Homework 1](Discrete_Math_HW1_CNF-DNF.ipynb) contains the following task:

  1) Find DNF & CNF for an arbitrary given formula.


[Homework 2](Discrete_Math_HW2_Ego_Network.ipynb) contains the following task:
  
  1) The [SNAP](https://snap.stanford.edu/data/egonets-Facebook.html) dataset called [facebook_combined.txt](facebook_combined.txt) includes a union of 10 ego networks from Facebook. An [ego network](http://www.analytictech.com/networks/egonet.htm) is a subgraph of the full friendship graph which includes a central node (ego) together with the vertices to which the ego is connected directly, and edges among them. Thus, each vertex in our dataset is either one of the 10 ego network centers, or is directly connected to (at least) one of them.

The task is as follows. Consider the following set of 11 vertices: 0, 107, 348, 414, 612, 686, 698, 1684, 1912, 3437, 3980. It is guaranteed that this set includes all 10 ego network centers, plus one extra vertex. The program should distinguish the added 11th vertex from the 10 ego network centers. As the answer, please provide the number of this additional vertex.

Notice: for testing, the nodes in the dataset can be renamed, in order to aviod hard-coding of the correct answer.
