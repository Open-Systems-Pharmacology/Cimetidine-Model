The general concept of building a PBPK model has previously been described by e.g. Kuepfer et al. ([Kuepfer 2016](#5-References)). The relevant anthropometric (height, weight) and physiological information (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-References)). This information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

Variability of plasma proteins and CYP enzymes are integrated into PK-Sim® and described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-References)) or otherwise referenced for the specific process. The final model applies active uptake of cimetidine into the liver by OCT1, uptake into the kidney by OAT3 and secretion from the kidney into the urine by MATE1, as well
as an unspecific hepatic clearance and passive renal glomerular filtration. The transporters were integrated into the PBPK model using the ([PK-Sim Ontogeny Database Version 7.3](#5-References)) and is described in detail in [Hanke 2020](#5-References). In detail, expression of the relevant transporters is shown in the following table taken from [Hanke 2020](#5-References):

| Transporter | Reference concentration mean | Reference concentration GSD | Relative expression | Localization / direction                    |
| :---------- | ---------------------------- | --------------------------- | ------------------- | ------------------------------------------- |
| MATE1       | 0.13                         | 1.53                        | Kidney              | Apical / efflux                             |
| OAT3        | 0.09                         | 1.53                        | RT-PCR              | Basolateral / influx                        |
| OCT1        | 0.16                         | 1.50                        | Array               | Basolateral, in enterocytes apical / influx |

First, a base PBPK model was built using clinical data including single and multiple dose studies with intravenous and oral applications of cimetidine to find an appropriate structure to describe the pharmacokinetics in plasma. This PBPK model was developed using a typical European individual adjusted to the demography of the respective study population. The relative tissue-specific expressions of enzymes predominantly being involved in the metabolism of efavirenz were derived from RT-PCR data from [Nishimura 2003](#5-References) and are implemented in the model as described previously ([Meyer 2012](#5-References)).

Unknown parameters (see below) were identified using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility.

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#22-Data).

Details about the structural model and its parameters can be found in [Section 2.3](#23-Model-Parameters-and-Assumptions).

