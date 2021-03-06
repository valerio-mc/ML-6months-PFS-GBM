# Machine learning-based prediction of early recurrence in glioblastoma patients: a glance towards precision medicine

**ABSTRACT**

**Background**<br>
Ability to thrive and time-to-recurrence following treatment are important parameters to assess in patients with glioblastoma multiforme (GBM), given its dismal prognosis. Though there is an ongoing debate whether it can be considered an appropriate surrogate endpoint for overall survival in clinical trials, progression-free survival (PFS) is routinely used for clinical decision-making.

**Objective**<br>
The aim of the present study is to investigate whether machine learning (ML)-based models can reliably stratify newly diagnosed GBM patients into prognostic subclasses on PFS basis, identifying those at higher risk for an early recurrence (≤ 6 months).

**Methods**<br>
A cohort of 474 patients undergoing surgery for a histopathologically confirmed GBM were collected from a multicentric database and split into a training and hold-out test set in an 80:20 ratio. Relevant pre-, intra- and immediately post-operative variables were selected by a recursive features selection algorithm (BORUTA) and used to build a ML-based model. 

**Results**<br>
A Random Forest Classifier was trained to predict PFS as a categorical variable; on the testing set, it achieved high consistency with an area under the curve (AUC) of 0.81 (95% CI: 0.77; 0.83). By leveraging the predictive value resulting from the combination of independent variables, the Random Forest Classifier outperformed conventional statistics in successfully identifying those patients more likely to experience an early recurrence. 

**Conclusions**<br>
A robust ML-based prediction model that identifies patients at high risk for early recurrence was successfully trained and internally validated. Considerable effort remains to integrate these predictions in a patient-centered care context.


<p align="center">
  <img width="1400" height="800" src="https://github.com/valerio-mc/ML-6months-PFS-GBM/blob/master/workflow.png">
</p>
