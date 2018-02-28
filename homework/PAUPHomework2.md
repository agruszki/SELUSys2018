## PAUP and Parsimony Lab

3. In your own words, what is a bootstrap analysis? Does it make sense to describe a bootstrap value as the probability that a grouping on a tree is correct?
	A bootstrap analysis determines how strongly a given data set supports a phylogenetic hypothesis by taking multiple subsamples of the data 
(withreplacement) and generating new trees. These subsamples are equal in size to the original matrix and any character state may be represented multiple 
times or not at all. How often the new trees from the subsamples show up determines how well your data supports the hypothesis. It does not make sense 
to describe a bootstrap value as a probability. A bootstrap value is the frequency at which a generated relationship or tree is generated from the 
subsamples. As such, a bootstrap value tells you more about the data than the “correctness” of a tree. 

4. What might be a situation in which you would want to use the jackknife instead of the bootstrap?
	The jackknife is similar to the bootstrap but samples without replacement. Therefore, each subsample will be smaller than the original. The 
percentage of the original matrix taken out depends on the jackknife strategy. This would be useful in looking for outliers or certain characters that 
are driving an analysis. Because there is no replacement, these characters are easier to identify. The jackknife is more useful when looking at 
morphological characters rather than molecular data.  


5. Transfer your trees to your desktop. Use FigTree or IcyTree to view them. Take a screenshot, and save it to the fig folder in the class repository. Below, complete the file path to where you have the file in the fig directory to embed the image of your screen shot. 

![/c/Users/Anna/Desktop/SELUSys2018b/fig/BootTreeImage.PNG]

![/c/Users/Anna/Desktop/SELUSys2018b/fig/JackTreeImage.PNG] 


## Add, commit, and push your homework by 5 pm on Friday.

