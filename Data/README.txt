# QUESTIONS from Javier
# what is the relationship between the gene length and probability of hit? 
# Probably nonlinear relationship? In TMP, we assume linear relationship.

# 1. Normilize by the length of the gene,
# 2. Do quantile normalization: like ranking by assigning continuous values. 
#    Also, Fisher-Jades normalization and test converting scores to normal quintiles.
# 3. look at the compositional data, log-type of transformation, simplex, book:
# https://www.jstor.org/stable/2345821, Aitchison
# 4. Beta congugates