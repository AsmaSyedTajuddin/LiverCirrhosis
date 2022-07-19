# LiverCirrhosis
Kaggle dataset

![Morbo-di-Parkinson-800x500](https://user-images.githubusercontent.com/100385953/179639131-021f8324-3a30-4d59-9b5e-f87df49512bc.jpg)


Liver cirrhosis is a widespread problem especially in North America due to high intake of alcohol. In this project, we will predict liver cirrhosis in a patient based on certain lifestyle and health conditions of a patient.

Cirrhosis is a late stage of scarring (fibrosis) of the liver caused by many forms of liver diseases and conditions, such as hepatitis and chronic alcoholism.

About Data 🗄

The data contains the information collected from the Mayo Clinic trial in primary biliary cirrhosis (PBC) of the liver conducted between 1974 and 1984. A description of the clinical background for the trial and the covariates recorded here is in Chapter 0, especially Section 0.2 of Fleming and Harrington, Counting Processes and Survival Analysis, Wiley, 1991. A more extended discussion can be found in Dickson, et al., Hepatology 10:1-7 (1989) and in Markus, et al., N Eng J of Med 320:1709-13 (1989).

A total of 424 PBC patients, referred to Mayo Clinic during that ten-year interval, met eligibility criteria for the randomized placebo-controlled trial of the drug D-penicillamine. The first 312 cases in the dataset participated in the randomized trial and contain largely complete data. The additional 112 cases did not participate in the clinical trial but consented to have basic measurements recorded and to be followed for survival. Six of those cases were lost to follow-up shortly after diagnosis, so the data here are on an additional 106 cases as well as the 312 randomized participants.

The dataset consists of following columns :

ID: unique identifier
N_Days: number of days between registration and the earlier of death, transplantation, or study analysis time in July 1986
Status: status of the patient C (censored), CL (censored due to liver tx), or D (death)
Drug: type of drug D-penicillamine or placebo
Age: age in [days]
Sex: M (male) or F (female)
Ascites: presence of ascites N (No) or Y (Yes)
Hepatomegaly: presence of hepatomegaly N (No) or Y (Yes)
Spiders: presence of spiders N (No) or Y (Yes)
Edema: presence of edema N (no edema and no diuretic therapy for edema), S (edema present without diuretics, or edema resolved by diuretics), or Y (edema despite diuretic therapy)
Bilirubin: serum bilirubin in [mg/dl]
Cholesterol: serum cholesterol in [mg/dl]
Albumin: albumin in [gm/dl]
Copper: urine copper in [ug/day]
Alk_Phos: alkaline phosphatase in [U/liter]
SGOT: SGOT in [U/ml]
Triglycerides: triglicerides in [mg/dl]
Platelets: platelets per cubic [ml/1000]
Prothrombin: prothrombin time in seconds [s]
Stage: histologic stage of disease (1, 2, 3, or 4)
