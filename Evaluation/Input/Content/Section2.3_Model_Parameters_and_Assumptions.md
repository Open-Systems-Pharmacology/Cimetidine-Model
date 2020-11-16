### 2.3.1 Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2 Distribution

Cimetidine is reported to be actively taken up into the liver by OCT1 ([Umehara 2007](#5-References)), into the kidney by OAT3 ([Tahara 2005](#5-References)) and secreted from the kidney into the urine by MATE1 ([Ohta 2010](#5-References)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation method by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3 Metabolism, Elimination and Inhibition

Cimetidine is mainly excreted unchanged via the kidneys. Additionally, 25 to 40 % is hepatically metabolized via an unknown pathway. 

Cimetidine inhibits several enzymes such as CYP3A4 and CYP2D6 as well as transporters such as OCT2, OCT2 and MATE.

### 2.3.4 Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building process. For some of the parameters, factors were optimized to maintain their ratio, e.g. a factor for the kcat clearances values for CYP2B6, CYP3A4, CYP3A5, CYP1A2 and CYP2A6 was optimized to keep the ratio constant.

The is result of the final parameter identification is shown in the table below:

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| Lipophilicity             | 3.437       |        |
| Specific intestinal permeability | 2.972E-5    | cm/min |
| Solubility at reference pH | 39.922   | mg/l |
| fraction unbound | 5.955E-3 |  |
| kcat CYP2B6 | 1.601 (factor: 0.31833 of literature reference) | 1/min |
| kcat CYP3A4 | 0.051 (factor: 0.31833 of literature reference) | 1/min |
| kcat CYP3A5 | 0.191 (factor: 0.31833 of literature reference) | 1/min |
| kcat CYP1A2 | 0.191 (factor: 0.31833 of literature reference) | 1/min |
| kcat CYP2A6 | 0.318 (factor: 0.31833 of literature reference) | 1/min |
| EC50 CYP3A4 | 0.071 (factor: 0.009711of literature reference) | µmol/l |
| EC50 CYP2B6 | 0.012 (factor: 0.009711of literature reference) | µmol/l |
| Dissolution time (50% dissolved) | 60 | min  |
| Dissolution shape | 0.272 |   |

