# Tanzania Water Wells

## Business Problem
-Stakeholder: Tanzanian Ministry of Water

- True business problem: Predict the functionality of wells by reducing false negatives and false positives, the main focus being on false negatives.
- Deliverables: Inference or Prediction?
    -Prediction
- Context:

False negative: Well functionality prediction says it is actully functional when it is not functional.

False positive: Well functionality prediction says it is not functional when it is functional.

We would prefer reducing false positives over false negatives

## Evalutation Metric
Which metric would make sense to primarily use as we evaluate our models?
- Accuracy - balances the two kinds of errors (but is impractical with imbalanced targets)
- Precision - helps reduce false positives
- Recall - helps reduce false negatives
- F1-Score - balances recall & precision (and is beter than accuracy with imbalaced targets)
- ROC-AUC - helps focus on better probability outputs (makes sure our predicted probabilities are better)

- We will primarily be focusing on recall and precision

## Data Understanding
- Terminology
    - Functional
    - Not functional
    - Needs repair

## Conclusions / Recommendations
- Focus on wells constructed in 1997 and prior
    - The wells built during this time period had more non-functional wells than functional wells
- Focus on features that better predicted our target variable (non-functioning wells)
    - Construction year
    - Source
    - Region
  
## Next Steps
- Better understanding of data
- Improving false positives to improve our prediction

# Additional Information
 * [Presentation](Presentation.pdf)
 * [Data](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/)