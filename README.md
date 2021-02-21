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
Eq -> An *equivalent* is the amount of a substance that will react with a certain number of hydrogen ions

Attribute | Units | Meaning | Description | Relation to CKD
---- | ---- | ---- | ---- | ----
ag | years | age | Age of each patient participant. | CKD can present in individuals of any age
bp | mmHg | blood pressure | Blood pressure of each patient participant, appearing to be only the diastolic measurement. | Generally higher.
sg | DMLS | specific gravity | Ratio of densities of patient urine sample and water. | Always greater than 1 (because urine has dissolved salts/minerals). Closer to 1.000 in CKD patients, as kidneys lose ability to reabsorb water.
al | ??? | albumin | A protein produced in the liver helps with transport of hormones, medicines, etc. | Low levels of albumin in the blood.
su | ??? | sugar | Level of urine glucose. | No clear relationship between glycosuria and CKD. (*Potentially* elevated levels through CKD progression)
rbc | Normal/Abnormal | red blood cells | Level of RBCs in the urine. | ----
pc | Normal/Abnormal | pus cell | Level of pus cells in the urine. | ----
pcc | Present/Not Present | pus cell clumps | Presence of pus cell clumps in the urine. | Presence indicates signs of an infections, usually(?) as a UTI (indeed, can involve ureters, kidneys, upper urinary tract, in addition to bladder and urethra. No research found directly related to CKD.
ba | Present/Not Present | bacteria | Presence of bacteria in the urine. | ----
bgr | mgs/dl | blood glucose random | Random measurement of blood glucose levels. | Lower blood glucose levels in CKD patients.
bu | mgs/dl | blood urea | A waste product in blood resulting from the breakdown of proteins. | Higher in patients with CKD.
sc | mgs/dl | serum creatinine | Creatinine is a waste product in blood resulting from muscle activity. | Higher in patients with CKD.
sod | mEq/L | sodium | Urinary sodium levels. | Believed to be higher, but not enough evidence from studies (need reference).
pot | mEq/L | potassium | Urinary potassium levels. | Believed to be lower.
hemo | gms | hemoglobin | A protein in RBCs that carries oxygen from the lungs to body tissues, and carries carbon dioxide in reverse. | Lower in patients with CKD.
pcv | ??? | packed cell volume | ??? | ----
wbcc | cells/mm3| white blood cell count | Number of WBCs in a blood sample, usually measured in microliters or cubic-millimeters. | Elevated WBCC is a well-known predictor of CKD, except in elderly patients who may exhibit low WBC (due to being in an already diseased state).
rbcc | millions/mm3 | red blood cell count | Number of RBCs in a blood sample | Appear to be lower in CKD patients.
htn | Yes/No | hypertension | Higher than normal blood pressure. | Generally present in CKD patients.
dm | Yes/No | diabetes mellitus | A disease which causes insufficient production of insulin, a hormone that regulates blood sugar. | A risk factor for KD; can injure the kidney blood vessels. The converse may also be true: Kidney failure can cause diabetes.
cad | Yes/No | coronary artery disease | A qualitative measure of whether a patient presented with coronary artery disease (major blood vessels in heart become damaged). | Appears to be an independent condition from CKD, but are risk factors of eachother. 
appet | Good/Poor | Appetite | A qualitative measure of the patient's appetite. | CKD patients often experience poor appetite (need reference).
pe | Yes/No | pedal edema | Swelling of the foot, ankle, or lower leg resulting from excess fluid build up. | Generally present in patients exhibiting CKD (need reference).
ane | Yes/No | anemia | A condition where a person's blood has below-normal levels of RBCs or hemoglobin. | A common symptom in CKD patients.
class | Yes/No | class | A patient exhibits CKD or not. | 

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
https://www.albertahealthservices.ca/assets/info/nutrition/if-nfs-low-blood-sugar-and-kidney-disease.pdf
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2689888/
https://www.kidney.org/atoz/content/understanding-your-lab-values
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6422977/
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4919657/
http://www.bcrenal.ca/resource-gallery/Documents/Management%20of%20Poor%20Appetite%20in%20Patients%20with%20Chronic%20Kidney%20Disease.pdf
https://pubmed.ncbi.nlm.nih.gov/24527682/
https://www.acc.org/latest-in-cardiology/ten-points-to-remember/2019/09/30/15/47/chronic-kidney-disease-and-coronary-artery-disease
https://www.niddk.nih.gov/health-information/kidney-disease/anemia
https://www.jahjournal.org/article.asp?issn=1658-5127;year=2019;volume=10;issue=2;spage=61;epage=66;aulast=Shastry
https://rarediseases.org/rare-diseases/renal-glycosuria/
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5180243/


Inconclusive studies about UNa levels and CKD:
https://bmcnephrol.biomedcentral.com/articles/10.1186/s12882-016-0338-z
https://www.sciencedirect.com/science/article/pii/S0085253815303203
