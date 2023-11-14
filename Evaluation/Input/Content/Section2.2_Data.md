### 2.2.1 In vitro / physico-chemical Data

A literature search was performed to collect available information on physiochemical properties of cimetidine. The obtained information from literature is summarized in the table below. 

| **Parameter**   | **Unit** | **Value**       | Source                                                       | **Description**                                 |
| :-------------- | -------- | --------------- | ------------------------------------------------------------ | ----------------------------------------------- |
| MW              | g/mol    | 252.34    | [Wishart 2006](#5-references) | Molecular weight                                |
| pK<sub>a</sub>1 | 6.93  | (base)          | [Avdeef 2001](#5-references)                       | Acid dissociation constant                      |
| pK<sub>a</sub>2 | 13.38  | (acid)          | [Wishart 2006](#5-references)                    | Acid dissociation constant                      |
| Solubility (pH) | mg/L     | 24.00 (6.8) | [Avdeef 2001](#5-references) | Water solubility                               |
| logP            |          | 0.48 | [Avdeef 2001](#5-references) | Partition coefficient between octanol and water |
| f<sub>u</sub> |   %      | 78.00 | [Taylor 1978](#5-references) | Fraction unbound in plasma                      |
| B/P ratio              |         | 0.98 | [Somogyi 1983](#5-references) | Blood to plasma ratio        |
| OCT1 K<sub>m</sub> | μmol/l | 2600 | [Umehara 2007](#5-references) | Michaelis-Menten constant |
| OAT3 K<sub>m</sub> | µmol/l | 149     | [Tahara 2005](#5-references) | Michaelis-Menten constant |
| MATE1 K<sub>m</sub> | µmol/l | 8.0 | [Ohta 2005](#5-references) | Michaelis-Menten constant |
| OCT1 K<sub>i</sub> | µmol/l | 104     | [Ito 2012](#5-references) | Inhibition constant for competitive inhibition |
| OCT2 K<sub>i</sub> | µmol/l | 124 | [Ito 2012](#5-references) | Inhibition constant for competitive inhibition |
| MATE1 K<sub>i</sub> | µmol/l | 3.8     | [Ito 2012](#5-references) | Inhibition constant for competitive inhibition |
| CYP3A4 K<sub>i</sub> (refitted in PK-Sim V10) | µmol/l | 268 (30.51266) | [Wrighton 1994](#5-references) | Inhibition constant for competitive inhibition |


### 2.2.2 Clinical Data

A literature search was performed to collect available clinical data on efavirenz in healthy adults.

#### 2.2.2.1 Model Building

The following studies were used for model building:

| Publication                       | Arm / Treatment / Information used for model building        |
| :-------------------------------- | :----------------------------------------------------------- |
| [Bodemar 1981](#5-references)     | Peptic ulcer patients receiving a single intravenous dose of 200 mg and oral doses of 200, 400 and 800 mg |
| [Morgan 1983](#5-references)      | Peptic ulcer patients receiving a single intravenous dose of 200 mg (5 min infusion) |
| [Bodemar 1979](#5-references)     | Healthy subjects receiving single oral doses of 200 and 400mg (tablet) |
| [Walkenstein 1978](#5-references) | Healthy subjects receiving a single oral dose of 300mg (solution) |
| [D'Angio 1986](#5-references)     | Healthy subjects receiving a single oral dose of 300mg (tablet) |



#### 2.2.2.2 Model verification

The following studies were used for model verification:

| Publication                       | Arm / Treatment / Information used for model verification    |
| :-------------------------------- | :----------------------------------------------------------- |
| [Grahnen 1979](#5-references)     | Healthy subjects receiving a single intravenous dose of 100 mg and a single oral dose of 400 mg (tablet) |
| [Larsson 1982](#5-references)     | Peptic ulcer patients receiving a single intravenous dose of 200 mg |
| [Mihaly  1984](#5-references)     | Peptic ulcer patients receiving a single intravenous and a single oral dose of 200 mg |
| [Morgan 1983](#5-references)      | Peptic ulcer patients receiving a single intravenous dose of 200 mg (30 min infusion) |
| [Lebert 1981](#5-references)      | Healthy subjects receiving a single intravenous dose of 300 mg (2 min infusion) |
| [Walkenstein 1978](#5-references) | Healthy subjects receiving a single intravenous dose of 300 mg (2 min infusion) and a single oral dose of 300 mg (tablet) |
| [Kanto 1981](#5-references)       | Healthy subjects receiving a single oral dose of 200 mg      |
| [Burland 1975](#5-references)     | Healthy subjects receiving single oral doses of 200 mg solution and capsule |
| [Bodemar 1979](#5-references)     | Peptic ulcer patients receiving a single oral dose of 200 mg (tablet) |
| [Bodemar 1981](#5-references)     | Peptic ulcer patients receiving single oral doses of 800 mg and multiple oral doses of 200 and 400 mg |
| [Barbhaiya 1995](#5-references)   | Healthy subjects receiving multiple oral doses of 300 mg (tablet) |
| [Somogyi 1981](#5-references)     | Healthy subjects receiving a single oral dose of 400 mg (tablet) |
| [Tiseo 1998](#5-references)       | Healthy subjects receiving multiple oral doses of 800 mg (tablet) |

#### 2.2.2.3 Model update due to PK-Sim V10 conversion

As a consequence of updating the cimetidine PBPK model to PK-Sim version 10, the K<sub>i</sub> needed to be readjusted. For this purpose, AUC ratios of the following clinical DDI studies were used to inform K<sub>i</sub> in an additional parameter identification:

| Publication                      | Interaction of cimetidine with:                              |
| :------------------------------------- | :------------------------------|
| [Kienlen 1993](#5-references)    | Alfentanil |
| [Abernethy 1983](#5-references)  | Alprazolam and triazolam |
| [Elliott 1984](#5-references)    | Midazolam |
| [Fee 1987](#5-references)        | Midazolam |
| [Greenblatt 1986](#5-references) | Intravenous and oral midazolam |
| [Martinez 1999](#5-references)   | Midazolam |
| [Salonen 1986](#5-references)    | Midazolam |
| [Pourbaix 1985](#5-references)   | Triazolam. NOTE: The interaction of cimetidine with alprazolam of this publication was not used for parameterization due to very long simulation duration! |
| [Cox 1986](#5-references)        | Triazolam |
| [Friedman 1988](#5-references)   | Triazolam |
