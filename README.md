# MBR decoding with learned risk functions

## Instructions

1. Run `gather_data` to download the dataset of German-English sentence pairs.
2. Run `sample_candidates` to generate the translation hypotheses that will be used to train the reranker and for evaluation.
3. Run `compute_candidate_scores` to compute the BLEURT scores for the training hypotheses that the reranker will regress on.
4. Run `train` to train the model.
5. Run `inference` to evaluate the model.

We note that the configurations in some of the files may need to be changed (for example, file paths, etc.).