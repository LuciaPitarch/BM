# READ-ME
Repository linked to the paper "Basic Meaning: The Achilles’s heel of metaphor identification" Submitted to ACL 2025.

# Summary

Basic Meaning (BM) is a fundamental concept in metaphor identification, serving as the reference point against which contextual meanings are compared. Despite its central role in the Metaphor Identification Procedure (MIP) and its extension, MIPVU, little attention has been given to systematically defining and identifying BM, which hinders transparency and reproducibility in both manual and computational metaphor annotation. In this work, we focus on BM itself, proposing psycholinguistically and lexically motivated measures to quantify BM in an objective and replicable manner.

The most Basic Meaning (BM) of a word is defined as more *concrete* in opposition to abstract, more *precise*, as opposed to vague, more *physical* or related to bodily action, and etymologically older than other meanings (e.g., the word chicken can be used in two different ways: `'a domestic fowl bred for flesh or eggs' or 'a person who lacks confidence'`. In this case the most basic meaning would be the first one.) 

# Contents
In this repository the user can find in `BM/data` our manually annotated datasets with added psycholinguistic and linguistic measures for *precision, concreteness, imageability, physicality* and *familiarity*. 

In `BM/scripts` the user can find the code to add psycholinguistic and linguistic features to their own data (this includes code for the augmentation of previous psycholinguistic norms for concreteness, imageability, physicality and familiarity using static language models). 
