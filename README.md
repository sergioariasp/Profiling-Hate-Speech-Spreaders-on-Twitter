# Profiling Hate Speech Spreaders on Twitter

This repository contains the code of the study "Profiling Hate Speech Spreaders on Twitter". The following files/folders can be found:

- **Deep Learning**: Contains 2 notebooks for English tweets (one with the use of profanity-check module https://pypi.org/project/profanity-check/ and other without it) and 1 for Spanish tweets with the implementation of BERT for them.
- **Machine Learning**: Contains 2 notebooks for English tweets (one with the use of profanity-check module https://pypi.org/project/profanity-check/ and other without it) and 1 for Spanish tweets with the implementation of traditional Machine Learning algorithms with hyperparameter optimization.
- **Error Analysis**: Folder with an Excel file containing the 40 users used as test set with the true label and the classification made by BERT, the best of the approaches analysed. All the False Positives and False Negatives users are provided in the original xml files.

The dataset used for this work is the following: https://zenodo.org/record/4603578#.YR06Y4gzZPY
