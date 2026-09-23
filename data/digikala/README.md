## Source
The original dataset was obtained from Kaggle:
[DigiKala Comments and Products](https://www.kaggle.com/datasets/radeai/digikala-comments-and-products)

## Processing and Modifications
The original dataset was preprocessed for the purposes of this study. Modifications include:
- Removal of samples with missing text or labels
- Filtering to include only binary sentiment labels (0 = Negative, 1 = Positive)
- Random sampling to reduce class imbalance
- Conversion to a unified tabular format for cross-domain evaluation

Users who wish to reproduce the results reported in the paper should use the processed version provided in this repository.
