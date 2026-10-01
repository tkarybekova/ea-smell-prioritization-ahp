# EA Smell Instance Prioritization using AHP

This repository contains the decision-support artifact and supporting materials developed for the Master's thesis:

**Using Multi-Criteria Decision-Making Methods for Quantifying Enterprise Architecture Debt: Applying the Analytic Hierarchy Process to Prioritize Enterprise Architecture Smells**

The study develops an Analytic Hierarchy Process (AHP)-based decision-support approach for prioritizing Enterprise Architecture (EA) smell instances for remediation. The artifact supports structured assessment of identified EA-smell instances and produces relative remediation priorities.

## Repository Contents

### 01-data
Contains the EA Smell Catalogue data used for screening, classification, and selection of the EA smells included in the demonstration. The data were obtained from the [EA Smell Catalogue maintained by RWTH Aachen University](https://swc-public.pages.rwth-aachen.de/smells/ea-smells/), based on the catalogue developed by Salentin and Hacks.

The Excel workbook contains the extracted catalogue entries together with the inclusion and exclusion decisions and the analytical classification used in this study.

### 02-demonstration-scenario
Contains the ArchiMate model of the constructed ERP–CRM–BI scenario used to demonstrate the artifact and instantiate the selected EA smells.

### 03-ahp-artifact
Contains the final Excel-based AHP decision-support artifact for assessing and prioritizing EA-smell instances.

### 04-sensitivity-analysis
Contains the SuperDecisions model and outputs used to conduct the sensitivity analysis, together with the Excel workbook used to reproduce the sensitivity-analysis graphs for presentation in the thesis.

### 05-evaluation
Contains the adapted Portfolio Theory implementation used as a comparison approach during the evaluation.

The participant evaluation was conducted using earlier versions of the AHP-based artifact and Portfolio Theory-based representation. Subsequent methodological review resulted in refinements to the final versions reported in the thesis and provided in this repository.

## Participant Evaluation Video

The video material presented to participants during the evaluation is available here:

**[Participant Evaluation Video](https://www.youtube.com/watch?v=_pKarTQEGRU)**

The video is retained as documentation of the material presented during the participant evaluation and therefore reflects the versions available at that stage of the research.

## Software

The repository materials were developed using:

- **Microsoft Excel** — implementation of the AHP-based decision-support artifact and adapted Portfolio Theory-based comparator, organization of the EA Smell Catalogue data, and presentation of sensitivity-analysis results
- **SuperDecisions 3.2.0** — independent verification of the AHP calculations and sensitivity analysis
- **Archi 5.8.0** — creation of the ArchiMate model of the constructed ERP–CRM–BI demonstration scenario

## Author

**Tolkounai Karybekova**  
Master's Degree Project in Strategic Information Systems  
Stockholm University, Department of Computer and Systems Sciences (DSV), 2026
