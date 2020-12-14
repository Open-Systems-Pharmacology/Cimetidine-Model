### 2.3.1 Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2 Distribution

Cimetidine is reported to be actively taken up into the liver by OCT1 ([Umehara 2007](#5-References)), into the kidney by OAT3 ([Tahara 2005](#5-References)) and secreted from the kidney into the urine by MATE1 ([Ohta 2010](#5-References)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation method by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

A `Lipophilicity` of 1.66 was back-calculated from the blood-to-plasma ratio of 0.98 ([Somogyi 1983](#5-References), [Hanke 2020](#5-References)).



### 2.3.3 Metabolism, Elimination and Inhibition

Cimetidine is mainly excreted unchanged via the kidneys. Additionally, 25 to 40 % is hepatically metabolized via an unknown pathway. 

Cimetidine inhibits several enzymes such as CYP3A4 and CYP2D6 as well as transporters such as OCT2, OCT2 and MATE.

### 2.3.4 Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building process (see [Section 2.2](#22-Data)). 

The result of the final parameter identification is shown in the table below:

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| Specific intestinal permeability | 8.72E-7 | cm/min |
| CLhep | 0.16 | 1/min |
| kcat OCT1 | 8.66E+4 | 1/min |
| kcat OAT3 | 5.75E+07 | 1/min |
| kcat MATE1 | 32.37 | 1/min |

