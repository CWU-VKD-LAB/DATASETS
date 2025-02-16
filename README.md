# DATASETS

To stop duplicating datasets across projects this DATASETS projects will be a repository to house all project datasets including data information.

## Labeled Datasets

Every dataset in this repository is labeled with a column called `class`, case-insensitive, that contains the class name for each case. This column can be in the form of a string, integer, or boolean and is located anywhere in the dataset.

| Dataset Name | Classes | Attributes | Total Cases | Distribution |
|--------------|---------|------------|-------------|--------------|
| Wine | 3 (4-8) | 11 | 178 | 6: 59, 7: 71, 8: 48 |
| Wheat Seeds | 3 (Zero-Two) | 7 | 210 | Zero: 70, One: 70, Two: 70 |
| MNIST Letters | 26 (A-Z) | 16 | 731 | ~28 cases per class |
| Musk | 2 (Zero-One) | 166 | 476 | Zero: 207, One: 269 |
| Heart Disease | 2 (Positive/Negative) | 13 | 303 | Positive: 137, Negative: 166 |
| Fisher Iris | 3 | 4 | 150 | Setosa: 50, Versicolor: 50, Virginica: 50 |
| Fisher Iris No Setosa | 2 | 4 | 100 | Versicolor: 50, Virginica: 50 |
| Diabetes | 2 (Positive/Negative) | 8 | 768 | Positive: 268, Negative: 500 |
| Breast Cancer Wisconsin | 2 (Malignant/Benign) | 30 | 569 | Malignant: 212, Benign: 357 |
| Breast Cancer Wisconsin Diagnostic | 2 (Malignant/Benign) | 9 | 699 | Malignant: 241, Benign: 458 |

## License

The datasets are sourced from the UCI Machine Learning Repository and Kaggle and are available under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

This project is freely avalable for both personal and commerical use under the [MIT License](LICENSE).
