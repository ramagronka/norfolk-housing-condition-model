# Norfolk Housing Condition Prediction Model

Predicting the physical condition of residential properties across Norfolk, VA 
using machine learning — and uncovering the lasting footprint of redlining.

## The Finding
Civic League (neighborhood) is the strongest predictor of property condition — 
outweighing physical characteristics and maintenance history. Geography matters 
more than the building itself, a pattern consistent with historical redlining.

## Models & Results
| Model | Accuracy |
|---|---|
| Gradient Boosting | 82.05% |
| Random Forest | 76.76% |
| SVM | 52.77% |

Gradient Boosting selected as best performer, with strong F1 scores across 
At Risk (0.84), Average (0.86), and Good (0.85) classes.

## Data Sources
- Norfolk Open Data Portal: Permits, Violations, Property Information
- RED2 dataset (locally held; data publicly available, used with permission)

## Stack
Python · scikit-learn · XGBoost · pandas · Jupyter
