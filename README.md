# READ-ME
Repository linked to the paper "Basic Meaning refinement for reliable Metaphor Identification"

# Summary

Among the different possible meanings of a polysemous word, some linguistic tasks require identifying the so-called basic meaning (BM). This is crucial, for example, when applying the Metaphor Identification Procedure (MIP). However, there is no unified operational definition of BM (different authors treat it differently, according to different linguistic perspectives), which makes both manual annotation and automated identification tasks difficult. 

In this work, we present an in-depth analysis of BM, addressing the challenge of defining and annotating it in a systematic, transparent, and replicable way in the field of computational metaphor. Drawing upon over 500 studies on metaphor annotation, we examine patterns of disagreement in BM annotation and the inherent complexities of the annotation process, using both quantitative and qualitative approaches. We introduce objective, reproducible metrics for identifying basic and non-basic meanings based on lexical and psycholinguistic features. Furthermore, we demonstrate the critical influence of BM on computational models that aim at automated metaphor detection, an aspect often overlooked in prior work. The datasets and scripts produced by this study are openly shared, offering a robust baseline for future research in basic meaning classification and metaphor identification.

# Contents
In this repository the user can find in `BM/data` our manually annotated datasets with added psycholinguistic and linguistic measures for *precision, concreteness, imageability, physicality* and *familiarity*. 

In `BM/scripts` the user can find the code to add psycholinguistic and linguistic features to their own data (this includes code for the augmentation of previous psycholinguistic norms for concreteness, imageability, physicality and familiarity using static language models). 
