# ktoh
Heterogenous Boolean Networks
Each file represents a heterogeneous Boolean network with two totalistic rules such that a 
fraction 𝜃 of the nodes obey one totalistic rule and the remaining nodes obey a second totalistic 
rule. In each network self-input for each node is assumed and 𝑘 represents the number of other 
nodes in each neighborhood that are randomly selected from all other nodes in the network. All 
nodes are updated at each time step using one of two totalistic rules that are assigned initially and 
do not change during the evolution of the network. These two totalistic rules are chosen from 
sixty-four selected totalistic rules that turn a node ON or OFF when 0, 1, 2, 3, 𝑘, or 𝑘 + 1 nodes 
in its neighborhood are ON and turn OFF otherwise. Each file is labeled with the two rules that 
are used in the heterogeneous Boolean network where each number in the rule means that a node 
turns ON when that many nodes in the network are ON and OFF otherwise. For example, rule 
023k+1 is the rule in which a node turns ON when 0, 2, 3, or k+1 nodes in its neighborhood are 
ON and OFF otherwise. All code used is included in the file. 
You can read the thesis paper for which these bifurcation diagrams were created here: 
