# CKD_ML_Classification
This project is an application of ML binary classification where we attempt to create a model to detect the presence of CKD in patients given some medical data/metrics.

## Problem Description
## Project Goals

## Project Summary
### Summary: EDA
### Summary: Data Cleaning
### Summary: Feature Engineering
### Summary: Model Creation

## Hardware and Software Used
## Data Collection Methodology

## Definitions of Dataset Attributes

DMLS -> Dimensionless

Attribute | Units | Meaning | Description | Relation to CKD
---- | ---- | ---- | ---- | ----
ag | years | age | Age of each patient participant. | CKD can present in individuals of any age
bp | mmHg | blood pressure | Blood pressure of each patient participant. | Generally higher.
sg | DMLS | specific gravity | Ratio of densities of patient urine sample and water. | Always greater than 1.0 (because urine has dissolved salts/minerals). Lower in CKD patients, as kidneys lose ability to reabsorb water.
al | ??? | albumin | A protein produced in the liver helps with transport of hormones, medicines, etc. | Low levels of albumin in the blood.
su | ??? | sugar | ??? | ----
rbc | ??? | red blood cells | ??? | ----
pc | ??? | pus cell | ??? | ----
pcc | ??? | pus cell clumps | ??? | ----
ba | ??? | bacteria | ??? | ----
bgr | mgs/dl | blood glucose random | ??? | ----
bu | mgs/dl | blood urea | ??? | ----
sc | mgs/dl | serum creatinine | ??? | ----
sod | mEq/L | sodium | ??? | ----
pot | mEq/L | potassium | ??? | ----
hemo | gms | hemoglobin | ??? | ----
pcr | ??? | packed cell volume | ??? | ----
wbcc | cells/mm3| white blood cell count | Number of WBCs in a blood sample, usually measured in microliters or cubic-millimeters. | Elevated WBCC is a well-known predictor of CKD, except in elderly patients who may exhibit low WBC (due to being in an already diseased state).
rbcc | millions/cmm | red blood cell count | ??? | ----
htn | Yes/No | hypertension | Higher than normal blood pressure. | Generally present in CKD patients.
dm | Yes/No | diabetes mellitus | A disease which causes insufficient production of insulin, a hormone that regulates blood sugar. | A risk factor for KD; can injure the kidney blood vessels. The converse may also be true: Kidney failure can cause diabetes.
cad | Yes/No | coronary artery disease | ??? | ----
appet | Good/Poor | Appetite | A qualitative measure of the patient's appetite. | ----
pe | Yes/No | pedal edema | Swelling of the foot, ankle, or lower leg resulting from excess fluid build up. | Generally present in patients exhibiting CKD (need reference).
ane | Yes/No | anemia | A condition where a person's blood has below-normal levels of RBCs or hemoglobin. | A common symptom in CKD patients.
class | Yes/No | class | A patient exhibits CKD or not. | ----

## Exploratory Data Analysis
## Data Cleaning
## Feature Engineering

## Model Creation
### Selection
### Training
### Evaluation
### Improvement

## Conclusion
## Future Steps
## Authors
## License
## Acknowledgements

## References
https://pubmed.ncbi.nlm.nih.gov/28699033/
https://ada.com/white-blood-cell-count/
https://www.mayoclinic.org/diseases-conditions/edema/symptoms-causes/syc-20366493
https://www.niddk.nih.gov/health-information/kidney-disease/anemia
https://www.niddk.nih.gov/health-information/kidney-disease/high-blood-pressure
https://www.kidney.org/atoz/content/diabetes
https://www.sciencedaily.com/releases/2016/08/160815215920
https://www.rnceus.com/ua/uasg
https://medlineplus.gov/ency/article/003608.htm

