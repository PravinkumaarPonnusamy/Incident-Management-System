# Incident-Management-System
# Requirement
Predicting Number of days taken to close a particular incident.
Predicting Wheather the incident will Meet the SLA or Not.

# PROJECT OBJECTIVE
To leverage the existing data about the incidents, their processing, and related data changes and to
use the knowledge extracted from these records to build the predictive model for time consumed to
resolve incidents and features that help to reduce the time using machine learning algorithms which
can assist the operators for better and faster resolution during the incident management process.

# Conclusion 1:
Out of all the models we tried XGBoost using features selected after VIF (i.e. causing no/less
multicollinearity), the model did a good job in predicting the time taken to close the incidents
in days. With almost 82% accuracy for train and 78% accuracy for test with a minimal error of
~ 10 days.

# Conclusion 2:
Out of all the classification models we performed we found out Gradient Boosting Classifier after
Hyper Parameter Tuning had the best performance in predicting whether incident will make sla or not
with an accuracy of 86.13% and precision/recall of almost 85% .
