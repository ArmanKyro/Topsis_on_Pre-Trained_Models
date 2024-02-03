# Project Title: Applying TOPSIS on Pre-trained Text Classification Models

## Overview
This repository showcases the application of the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) on pre-trained text classification models. TOPSIS is a multi-criteria decision-making method used to evaluate the performance of alternative solutions based on predefined criteria.

## Dataset
The input tabular data consists of the performance metrics of various pre-trained text classification models. The metrics include Accuracy, F1 Score, Precision, and Loss.

| Model                                                  | Accuracy | F1    | Precision | Loss  |
|--------------------------------------------------------|----------|-------|-----------|-------|
| distilroberta-finetuned-financial-text-classification  | 0.890    | 0.883 | 0.876     | 0.446 |
| text-complexity-classification                         | 0.991    | 0.982 | 0.981     | 0.554 |
| deberta-v3-base-finetuned-finance-text-classification   | 0.891    | 0.891 | 0.892     | 0.345 |
| autotrain-security-text-classification-albert-688320769 | 0.882    | 0.897 | 0.918     | 0.304 |
| comments-text-classification-model                      | 0.619    | 0.564 | 0.590     | 1.080 |

## Output
After applying TOPSIS, the resulting data includes additional columns - Topsis Score and Rank.

| Model                                                  | Accuracy | F1    | Precision | Loss  | Topsis Score | Rank |
|--------------------------------------------------------|----------|-------|-----------|-------|--------------|------|
| distilroberta-finetuned-financial-text-classification  | 0.89     | 0.883 | 0.876     | 0.446 | 0.7938       | 3.0  |
| text-complexity-classification                         | 0.991    | 0.982 | 0.981     | 0.554 | 0.7414       | 4.0  |
| deberta-v3-base-finetuned-finance-text-classification   | 0.891    | 0.891 | 0.892     | 0.345 | 0.8706       | 2.0  |
| autotrain-security-text-classification-albert-688320769 | 0.882    | 0.897 | 0.918     | 0.304 | 0.8888       | 1.0  |
| comments-text-classification-model                      | 0.619    | 0.564 | 0.590     | 1.080 | 0.0          | 5.0  |

## Contributors
- Armanjeet Singh Bhullar

