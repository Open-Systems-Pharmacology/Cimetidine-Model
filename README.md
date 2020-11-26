## Cimetidine-Model
Whole-body PBPK model of cimetidine (OCT2/MATE and CYP3A4 DDI perpetrator drug) 

<a title="Cimetidine" href="https://commons.wikimedia.org/wiki/File:Cimetidine_Structural_Formula_V.1.svg"><img width="512" alt="Cimetidine Structural Formula V.1" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/25/Cimetidine_Structural_Formula_V.1.svg/512px-Cimetidine_Structural_Formula_V.1.svg.png"></a>



This repository contains:

- a PK-Sim snapshot (*.json) file of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](https://github.com/Open-Systems-Pharmacology/Cimetidine-Model/releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases).**

This cimetidine model is intended to be used as perpetrator drug in OCT2/MATE- and CYP3A4-mediated drug-drug interactions (DDI). 

The herein presented model was developed and published by Hanke et al. [[1](https://github.com/Open-Systems-Pharmacology/Cimetidine-Model#references)]. It comprises transport by OCT1, MATE1 and OAT3 as well as glomerular filtration. It has been developed using 27 clinical studies of intravenous or oral administration, covering a broad dosing range of 100 to 800 mg. 

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

### Reference
[1] Hanke N, Türk D, Selzer D, Ishiguro N, Ebner T, Wiebe S, Müller F, Stopfer P, Nock V, Lehr T. 
A Comprehensive Whole‑Body Physiologically Based Pharmacokinetic Drug–Drug–Gene Interaction Model of Metformin and Cimetidine in Healthy Adults and Renally Impaired Individuals. Clinical Pharmacokinetics 2020, [https://doi.org/10.1007/s40262-020-00896-w](https://link.springer.com/article/10.1007/s40262-020-00896-w) 
