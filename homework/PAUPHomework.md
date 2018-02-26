## PAUP and Parsimony Lab

1. From the iterative alignment section: Which aslignment (pasta_script1, pasta_script2, pasta_script3) do you think is the "best"? By what criteria did you arrive at this decision?
	Pasta_script1 was run on default settings. Pasta_script2 was run using a different tree estimator (RAxML) and pasta_script3 used this same 
tree estimator but changed the number of maximum subsets to four.  Once run, the output alignment quality was difficult to differentiate by eye and 
therefore difficult to determine which was “best”. Using FastSP, we can make pairwise comparisons using the calculated summary statistics.  
	I first compared pasta_script1 with pasta_script2. Pasta_script1 had 1,106 more homologies in its alignment than pasta_script2. The number of 
shared homologies between the two alignments was 44, 9011 and the number of correctly aligned columns was 401. 
	Next, I compared pasta_script1 with pasta_script2. Both alignments had the same number of homologies (486741) with the number of shared 
homologies as 486736. Mostly likely due to these similarities, the number of correctly aligned columns was 1093.
	Finally, I compared pasta_script2 with pasta_script3. Pasta_script3 had 1, 016 more homologies than pasta_script2. Together there were 44,9006 
shared homologies and 400 correctly aligned columns. 
	Both pasta_script1 and pasta_script2 had the same high number of homologies and acted similarly when compared to pasta_script2. I would argue 
that both alignments are “better” than pasta_script2. 
 

2. In tree searching, when would you expect the swap algorithm to matter strongly?
	Tree bisection and reconnection (TBR) takes branch off a tree and reconnects this branch to another location. Parsimony scores between the 
trees are then compared and the lowest score wins. TBR is a good place to start a heuristic search through tree space as it improves large topological sections. 
Subtree pruning and regrafting (SPR) follows a similar process but attempts to connect the pruned section to every possibility and scores as it goes. 
SPR is more thorough but takes the most time and memory to run. With large datasets, SPR may not be the most efficient method. Nearest Neighbor 
Interchange moves around neighboring taxa to find a tree with the best score. Poor parsimony scores are discarded, and the search continues until a 
satisfactory score is reached. This method is best for finishing a heuristic search as it deals with small changes. When choosing a swap algorithm, 
the amount of data/taxa as well as beginning parsimony score of the tree is important to consider. 

3. In your own words, what is a bootstrap analysis? Does it make sense to describe a bootstrap value as the probability that a grouping on a tree is correct?

4. What might be a situation in which you would want to use the jackknife instead of the bootstrap? 


5. Transfer your trees to your desktop. Use FigTree or IcyTree to view them. Take a screenshot, and save it to the fig folder in the class repository. Below, complete the file path to where you have the file in the fig directory to embed the image of your screen shot. 

![Embed your bootstrap tree here](../fig/your_bootstrap_tree_image) 

![Embed your jackknife tree here](../fig/your_jackknife_tree_image) 


## Add, commit, and push your homework by 5 pm on Friday.

