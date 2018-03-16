## Model Comparison Homework

1. In our initial model comparisons, we compared K80, F81 and JC. K80 was the best, but ultimately, that branch of the nested diagram did not produce the best model. What does this tell you about the strengths and weaknesses of hierachical model testing?

When doing a model comparison, it is possible to reach a local optima that is not as good as the global 
optima. Another branch may be worse at first but ultimately better. When trying to find the best model, you should do 
a thorough search. 

2. Fill in the model table:

| Model | nst | basefr | Invariant sites? | Gamma Distributed rate heterogeneity | Score | LR |
|-------|-------|----|------|-------| -------|-----|
| SYM| nst=6 | basefr=eq| no |no|L=-6424.202| 2\*(lnL1-lnL2) =559.328 | 
| K80+gamma| nst=2 | basefr=eq |no|yes | L=-5971.83486 | 2\*(lnL1-lnL2) = 904.734|
|K80+I+gamma| nst=2 | basefr=eq  | yes | gamma=yes | L=-5971.83486 | 2\*(lnL1-lnL2) = 0 |

2b. Which model was ultimately preferred out of your set of candidate models?

K80 had the best LR score of 904.743 

3. In the RAxML call, change the name of the run, and the random number seed. Add the -N flag, and a number of your choosing, to get multiple replicates. Do you get the same score every time?

4. Use the treecompare script to compare if you got the same topology for each tree. 
