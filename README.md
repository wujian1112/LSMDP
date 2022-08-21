# LSMDP
#The adjacency matrix of graphs is generated by the Matlab project of "generate_negtive_resolving_matrix_matlab.zip". 
Taking the adjacency matrix, random node features and graph resolving matrix as input, the main function of "compute_dim.py" computes the metric dimension of graphs. Where the generated adjacency matrix and resolving matrix are all as inputs.
# 1. 
#Note that the results may vary depending on the computing environment. Tables 1 and 3 are obtained through extensive calculations by this program. 
# The Dim7 in table1 and table3 can be obtained by the Matlab program "LP_algo.zip",taking as input the adjacency matrix of graphs. 
# According to Table1 and Table 3, the function of "comput_relative_ratio.py" gives the content of Table2 and Table4.
# Delete the repair module in the function of "compute_dim.py", one can get the results of Table5. The time columns of Table5 can be got through "compute_ave_time.py".
# The results of Dim6 in Table 1 and Table 3 can be obtained by the function of "main_repaire_only.py".
# Figure2 is generated by the function of "visual_graph.py".
# Figure3 is generated through the module of "converge_analysis.py"
# In addition, we explore the posibality of learning to solve the metric dimension of graphs. The results may not be very strict. Using different graph models, one may produce different results. Our first attempt is to learn the metric dimensions of a graph. The implementation of the code is one of our attempts. The output results may be different. Perhaps, one can improve it further.
# The code simply provides an implementation possibility. This work is partially motivated by the work of (R. Sato, M. Yamada, H. Kashima. Learning to Find Hard Instances of Graph Problems. arxiv, 2019. URL:https://arxiv.org/pdf/1902.09700v1.pdf). Particularly, according to the background of MDP, we design the specific reward function,data structure, and the repair policy to solve the MDP. Furthermore, we introduce the graph neural networks to solve the MDP.
# The experiments are all implemented in the environment of Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz 2.21GHz 16.0GB
