# Credit_Risk_Analysis
  •	Precision = TruePositive / (TruePositive + FalsePositive)
  Oversampling & Combination Sampling have highest balanced accuracy score 65% but still low overall.
  The Precision scores of all sampling methods are close to 100%. That means the models predict mostly correctly of credits is at low risk. The Predicted True but Actually False (False Positive) is remarkably small.
  High precision indicates a low number of false positives.
  •	Recall = TruePositive / (TruePositive + FalseNegative)
  The Recall scores overall are around 60%. The models predict 60% of the credits is at low risk. The Actually True but Predicted False plays a big part in the denominator. That means the models give out considerable results that are false significantly.
  Low recall indicates a low number of false negatives.
  ## Analysis
  In this credit risk analysis, the precision is more important. The high recall (sensitivity) may result of rejection of loan applications and loss of revenue in general.
  Oversampling can cause overfishing. Undersampling can cause loss of important information. 
  All of the resampling methods should be employed in order to avoid bias.
