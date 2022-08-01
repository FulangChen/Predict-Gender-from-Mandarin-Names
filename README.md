# Predict-Gender-from-Mandarin-Names
 
* Investigated the phonotactic patterns that correlate with gender in given names for Mandarin Chinese.

* Found that for Mandarin, female names have a higher proportion of open syllables and high vowel nuclei, while male names have a higher proportion of back vowel nuclei, round vowel nuclei, obstruent onsets, and non-coronal onsets, conforming to cross-linguistic patterns.

* Predicted gender from Mandarin names using various Scikit-Learn classifiers, using character frequencies or FastText word embeddings and/or phonotactic features as features.

* Evaluated the models' performance using F1 and AUC scores, ROC curve and the confusion matrix.

* Achieved ~80% accuracy using just character frequencies or character embeddings as the feature, and ~60% accuracy using just the phonotactic features.

* Found that models' performance is not imporved when character frequencies or character embeddings and phonotactic features are used as features.
