# 🛑 Food Allergy & Dietary Restriction Alert System using Image Classification

A 4-week ISS research project that leverages CNN-based image classification to identify food items from photos and infer potential allergenic or restricted ingredients based on pre-defined mappings.

## 🔍 Motivation

In a world where food allergies and dietary restrictions are becoming increasingly important, this project aims to use AI to recognize food items in images and automatically alert users if they may contain ingredients that are harmful or unwanted. This includes common allergens as well as ingredients avoided for ethical (e.g. vegetarianism) or religious (e.g. halal/kosher) reasons.

## 🎯 Objectives

- Classify food items from images using CNN-based models (single-label classification)
- Infer potential allergens or restricted ingredients based on the predicted food class
- Alert users when food items may contain ingredients they wish to avoid (e.g., peanut, pork, shellfish)
- Support dietary profiles including allergies, vegetarianism, and religious food restrictions
- Visualize model attention using Grad-CAM or similar techniques
- Use Food-101 dataset and predefined ingredient mappings for evaluation


## 🗓️ Timeline (4 weeks)
| Week | Tasks |
|------|-------|
| 1 | Topic confirmation, dataset selection (Food-101), related papers review |
| 2 | Model setup (CNN / Transfer Learning), data preprocessing |
| 3 | Training, evaluation, visualization |
| 4 | Paper writing (Overleaf), GitHub final polish |

## 🗄️ Structure
```
FoodAI-Classifier/
├── data/
├── models/
├── notebooks/
├── paper/
└── README.md
```
## 📁 Dataset
- [Food-101 dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)
- Additional tagging for common allergens (manual/assisted)

## 🧠 Models
- (need advice)

## 📊 Metrics
- Accuracy, Precision, Recall, F1-Score
- Class-wise evaluation (e.g., ‘peanut’, ‘egg’, ‘milk’)

## 📄 Tools
- Python, PyTorch, scikit-learn for research and experiment
- Jupyter Notebook, Matplotlib for visualisation
- Overleaf (LaTeX) for research paper

## Author
- Doyeop Kim
- BSc Computer Science, University of Exeter, United Kingdom
- ISS Research Internship, Sungkyunkwan University, Republic of Korea
- August 2025

## Acknowledgements
This project is supported by the ISS Research Internship Programme at Sungkyunkwan University under the guidance of Prof. Khan Muhammad and TA Shehzad Ali.

