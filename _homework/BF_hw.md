---
title: Stepping Stone Homework
teaching: 180
exercises: 0
questions:
- "How can we compute a partitioned topology on LONI?"
---

## DivTime HW1
1. Which partition schemes do you think are most likely, biologically?
Partitioning by codon is probably the most likley biologically. We know that substitution rates can vary by codon and can especially vary in the third 

codon position. The third codon position tends to change more frequently as it has few downstream effects. Partitioning by gene is also important to 

consider as genes can evolve at different rates. For example, there are higher rates of substitution in mtDNA genes than in nuclear genes. The least 

likely model is a uniform or concatenated scheme. 



2. Use Stepping stone and path sampling to determine which is the best partitioning scheme. Below, paste the marginal likelihood values and explain which partitioning scheme you think is best justified for these data.
Stepping Stone
ML Uniform (M0) = -21400.91 
ML Gene (M1)= -21398.76
ML Codon (M2) = -20530.51

Stepping Stone Bayes factors

BF (M0, M1) K= -2.15 (M1 preferred)
BF (M1, M2) K= -868.25 (M2 preferred)
Preferred model: Partition by codon  


Path Sampling 
ML Uniform (M0) = -21400.63
ML Gene (M1) = -21399.13
ML Codon (M2) = -20530.11

Path Sampling Bayes factors

BF (M0, M1) K= -1.5
BF (M1, M2) K= -869.02
Preferred model: Partition by codon
## Submit the homework by the course finals time
