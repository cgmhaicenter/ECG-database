
## Overview
Acquisition of ECG data by MUSE system
The MUSE Cardiology Information System was developed by GE to manage and simplify the processing flow of information related to ECG examination, so that data transmission, distribution and analysis can be carried out faster. The MUSE system helps physicians streamline the workflow while inspecting patients’ ECG information. This helps to support medical decision-making and follow-up care interventions. Manage knowledge for better results. In addition to being a database management system, the MUSE Heart Examination System can also be seamlessly connected with static ECG, exercise ECG or Holter equipment. The MUSE system of Chang Gung Memorial Hospital is also connected to the hospital's information system (Hospital Information System, HIS), Electronic Health Record (Electronic Health Record) and two-way communication between ECG equipment. In this case, the electrocardiogram information of the MUSE system in the six major districts of Chang Gung Memorial Hospital (Keelung, Linkou, Taipei, Taoyuan, Yunlin Chiayi, and Kaohsiung) was obtained. From 2007 to 2019, all the electronic electrocardiogram examination data were up to 5.1 million examinations. The data can be effectively used in the modeling and verification of artificial intelligence models at different stages, and further connected with the Chang Gung Medical Research Database.
## Patient cohort 
The database comprises 5.14 million 12-lead ECG samples from 1.77 million patients. Data were de-identified to protect patient privacy. ECGs (10 sec epoch) are acquired at a sampling rate of 250 Hz or 500 Hz using a Marquette ECG machine (GE Healthcare) and stored using the MUSE data management system. All data were resampled to 500 Hz by linear interpolation. 
Example of a 10 second epoch of conventional 12 leads (i, ii, iii, avr, avl, avf, v1, v2, v3, v4, v5, v6). 

 
The ECG data will be quality checked and linked to original cardiologist reports and their clinical information (such as diagnoses and medication). We identified 367,946 patients with at least one digital 12-lead ECG and at least one echocardiogram obtained within 14 days of the index ECG. 
## Linked data: clinical information, MACE, and mortality 
We linked the ECG data to the Chang Gung Research Database to obtain patient characteristics and clinical information. Since the long-term outcome is needed to examine the predictive power of AI algorithms, we plan to link the data to the National Health Insurance Database to obtain medical outcomes such as the major adverse cardiac events (MACE; ICD9 codes: (acute coronary syndrome/ myocardial infarction: ICD-9 410–410.9, 36.0–36.03, 36.05–36.09, 36.1–36.99, and V45.81; heart failure: ICD-9 428.0–428.10; stroke: ICD-9 430–432, and 433–437;  dysrhythmia: ICD-9 426.0, 426.12–426.13, 426.51–426.52, 426.54, 427.1, 427.4, 427.41–427.42, and 427.5). Survival status and cause of death from 2001 to 2018 were ascertained by using the National Death Registry in Taiwan, which records the causes of death for all deceased citizens. The linkage between the death registry and ECG examinations was by de-identified personal identification. The accuracy of the coding has been validated in previous studies. Causes of death were death from any cause and cardiovascular-related cause-specific death categories, that is, heart diseases (ICD-9 codes: 390-392, 393-398, 410-414, 420-429; ICD-10 codes: I01-I02.0, I05-I09, I20-I25, I27, I30-I52), hypertension (ICD-9 codes: 401-405; ICD-10 codes: I10-I15), Cerebrovascular disease (ICD-9 codes: 401-405; ICD-10 codes: I60-I69), and Atherosclerosis (ICD-9 codes: 440; ICD-10 codes: I70).
 
Days between ECG-ECHO 
 
Average 3.35 ± 3.88 day

Requesting Datasets
To request a dataset, please contact the Center of Artificial Intelligence in Medicine at cgmhailab@gmail.com




