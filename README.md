# 509-text-classification

Use machine learning models to reclassify text.

Issue:
Inadequate reporting:
  17.03% (1,054) of events were classified as “other” and “other/miscellaneous”
  It makes it harder to detect safety trends and prevent preventable events
  Incidents may go unnoticed if they are categorized wrong

Overwhelming Category events:
  Original data contains 40 event type with the removal of “other” and “other/miscellaneous” 
  Some events categories are repetitive (medication related and medication related issues) 

Deliverable:
  Reclassification “Other” & “Other/miscellaneous” Event Type
  Cleaning the dataset involves reviewing incident reports and ensuring that they are properly categorized and free of errors

Purpose:
  Be able to analyze past data and detect trends to help prevent preventable events from happening
  Maintain a healthy reporting system to ensure that all incidents are properly recorded and analyzed
  Organization can then identify potential hazards and take proactive measures to prevent future incidents from happening
  Reduce incident rates, improving overall safety performance, and enhancing organizational reputation.

Steps:
1. EDA report
2. Data preprocessing
3. Text processing
4. Train-Test split
5. Feature extraction
6. Model training and evaluation
