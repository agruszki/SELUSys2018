1. From section "What is parsimony doing anyway?": How is the parsimony score impacted if you set a different number of characters to the custom 
model? For this answer, give the ctype command that you used to set up the model, and the number of parsimony steps in the best tree uncovered.

The parsimony score tends to decrease as the number of characters is increased. The ctype commands and scores can be seen below. Note that when the 
characters were set to 5, the walltime limit timed out before finishing but every “best tree” up until that point showed a score of 53. 

No Ctype command  (score=67)
Ctype my_ctype:1  (score=66)
Ctype my_ctype:1-2(score=65)
Ctype my_ctype:1-5 (all scores=53 but did not finish)

2.From section "Transitions and Transversions". Try the same analysis, except with a 3-1 weighting on transitions to transversions. For this 
answer, paste below your transition matrix and provide the parsimony score. Also note if there were any major differences in the consensus tree built 
from the 2-1 transition-transversion model and the consensus tree built from 3-1 transition-transversion model.

A difference in parsimony scores was best seen when the number of characters was set to “all”. There were no differences in consensus trees. 
usertype 2_1 stepmatrix=4               
                a  c  g  t
        [a]     .  2  1  2
        [c]     2  .  2  1
        [g]     1  2  .  2
        [t]     2  1  2  . Parsimony score=1529


usertype 3_1 stepmatrix=4            
                a  c  g  t
        [a]     .  3  1  3
        [c]     3  .  3  1
        [g]     1  3  .  3
        [t]     3  1  3  . Parsimony score=1905


3.So far, we looked at models that vary in two parameters, base frequencies and transition/transversion bias. Which parameter made a bigger 
difference? Does this make sense to you? Why or why not?

Changing the base frequencies makes a bigger difference. Observed substitution is influenced by both opportunity and actual substitution rate. The 
starting states will have a large effect on how often a base change happens regardless of the rate.
 
Commit and push to your copy of the repository by Friday at 5 pm.

