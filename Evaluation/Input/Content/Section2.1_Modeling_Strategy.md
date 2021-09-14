The general concept of building a PBPK model has previously been described by e.g. Kuepfer et al. ([Kuepfer 2016](#5-References)). The relevant anthropometric (height, weight) and physiological information (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-References)). This information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

Variability of plasma proteins and CYP enzymes are integrated into PK-Sim® and described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-References)) or otherwise referenced for the specific process. The final model applies active uptake of cimetidine into the liver by OCT1, uptake into the kidney by OAT3 and secretion from the kidney into the urine by MATE1, as well
as an unspecific hepatic clearance and passive renal glomerular filtration. The transporters were integrated into the PBPK model using the ([PK-Sim Ontogeny Database Version 7.3](#5-References)) and is described in detail in [Hanke 2020](#5-References).

First, a base PBPK model was built using clinical data including single and multiple dose studies with intravenous and oral applications of cimetidine to find an appropriate structure to describe the pharmacokinetics in plasma. This PBPK model was developed using a typical European individual adjusted to the demography of the respective study population. 

Oral administration of cimetidine in the fasted state frequently produces two plasma concentrations peaks. These double peaks are probably caused by the phasic gastrointestinal motility that controls gastric emptying in the fasted state. To describe the very different shapes of the observed mean cimetidine plasma profiles, split dose administration protocols for all studies of cimetidine administered orally in the fasted state were optimized in a NONMEM analysis (see [Hanke 2020](#5-References)). The resulting split dose administration protocols were then implemented and used for the PBPK modeling of the respective cimetidine studies.

Unknown parameters (see below) were identified using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility.

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#22-Data).

Details about the structural model and its parameters can be found in [Section 2.3](#23-Model-Parameters-and-Assumptions).
