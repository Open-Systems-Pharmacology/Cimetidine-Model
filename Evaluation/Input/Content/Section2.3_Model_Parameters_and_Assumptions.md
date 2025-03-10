### 2.3.1 Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2 Distribution

Cimetidine is reported to be actively taken up into the liver by OCT1 ([Umehara 2007](#5-references)), into the kidney by OAT3 ([Tahara 2005](#5-references)) and secreted from the kidney into the urine by MATE1 ([Ohta 2010](#5-references)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation method by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

A `Lipophilicity` of 1.66 was back-calculated from the blood-to-plasma ratio of 0.98 ([Somogyi 1983](#5-references), [Hanke 2020](#5-references)).



### 2.3.3 Metabolism, Elimination and Inhibition

Cimetidine is mainly excreted unchanged via the kidneys. Additionally, 25 to 40 % is hepatically metabolized via an unknown pathway. 

Cimetidine inhibits several enzymes such as CYP3A4 and CYP2D6 as well as transporters such as OCT2, OCT2 and MATE.

### 2.3.4 Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building process (see [Section 2.2](#22-data)). 

Specific intestinal permeability, unspecific hepatic clearance (CLhep) and Kcat values for OCT1, OAT3 and MATE1 were reestimated in PK-Sim Version 10, and, therefore, do not correspond to the original values published by [Hanke 2020](#5-references). The result of the final parameter identification is shown in the table below:

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| Specific intestinal permeability| 5.26E-06 | cm/min |
| CLhep| 0.12| 1/min |
| kcat OCT1| 14098.32 | 1/min |
| kcat OAT3| 2522831.10 | 1/min |
| kcat MATE1| 159.47 | 1/min |

As a result of updating the cimetidine PBPK model to PK-Sim V10, the interaction parameter CYP3A4 K<sub>i</sub> was fitted in a second step to improve the performance in CYP3A4 interactions. In detail, CYP3A4 K<sub>i</sub> was adjusted such that the error of the simulated AUC ratios of cimetidine with several CYP3A4 substrates vs. corresponding observed AUC ratios of the clinical studies (see [Section 2.2.2.3](#2223-model-update-due-to-pk-sim-v10-conversion)) was minimized.

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| CYP3A4 K<sub>i</sub>| 30.51266 | µmol/l |
