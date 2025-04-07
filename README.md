# INSIGHTS
## Class Imbalance Resolved Before Modeling
You balanced the dataset using resampling: each stage (I–IV) had equal instances.
This helps reduce bias toward majority classes and improves fairness in evaluation.

## Logistic Regression Shows Underfitting
Training Accuracy: 0.2648
Testing Accuracy: 0.2455

## Random Forest Overfits the Training Data
Training Accuracy: 1.0
Testing Accuracy: 0.2528

## Classification Reports Reveal Low Performance Across All Models
Precision, Recall, and F1-scores for all stages are around 0.24–0.27.
All models struggle equally to separate between cancer stages.

## Confusion Matrix Indicates Heavy Misclassification
High confusion across all classes, e.g., many Stage I cases misclassified as Stage II and III, and vice versa.

## Model Generalization Is Weak Overall
Despite trying different models, test accuracy stays around 25%, close to random guessing for 4 classes (25%).

