# MIRAGE Guideline Builder

## Objects

### Glycomics Experiment

Here, the first decision is made between interaction and structure analysis data

- Interaction_Analysis_Data
  - Type: Interaction_Analysis
  - Description: tba
- Structure_Analysis_Data
  - Type: Structure_Analysis
- Sample_Prep_Guidelines
  - Type: Sample_Preparation

### Sample_Preparation

Sample Preparation Guidelines apply for all MIRAGE Guidelines.

- Sample_Preparation_Data
  - Type: string
  - Description: MIRAGE Sample Preparations Guidelines

### Interaction_Analysis

- Interaction_Analysis
  - Type: string
  - Description: tba

### Structure_Analysis

- Glycan_unbound
  - Type: Techniques_Glycan
  - Description: Decision on the type of glycan. If unbound glycans, follow this route.
- Glycoconjugates
  - Type: Types_Glycoconjugates
  - Description: Decision on the type of glycoconjugates. If glycans bound to pepetides, lipds etc., the follow this route.

### Types_Glycoconjugates

- Glycoproteins
  - Type: Glycoproteins
  - Term: schema
  - Description: tba
- Glycolipids
  - Type: Glycolipids
  - Term: schema
  - Description: tba

### Glycoproteins

- Glcoproteins
  - Type: Techniques_Glycoproteins
  - Term: schema
  - Description: tba

### Glycolipids

- Glcoproteins
  - Type: string
  - Term: schema
  - Description: tba

### Techniques_Glycoproteins

- MassSpec
  - Type: MassSpectrometry
- LC
  - Type: string
- NMR
  - Type: string
- CE
  - Type: string

### MassSpectrometry

- General_Features
  - Type: string
  - Description: Text File
- DataProcessing_and_Identification
  - Type: string
  - Description: Text File
- IonSources
  - Type: Ion_Sources
  - Description: Decision which ion source has been applied
- Detectors
  - Type: string
  - Description: Text file
- Ion_Sources
  - Type: Ion_Sources
  - Description: Selection of the ion source applied in the analysis
- Ion_Transfer_Optics
  - Type: string
  - Description: Selection of the optics used in the analysis
- Data_Processing
  - Type: Data_Processing
  - Description: Selection of the way of data processing in dependece of the glycan type

### Ion_Sources

- ESI
  - Type: string
  - Description: Text file
- MALDI
  - Type: string
  - Description: Text file

### Ion_Transfer_Optics

- Coll_Cell
  - Type: string
  - Description: Text file
- TOF
  - Type: string
  - Description: Text file  
- Ion_Trap
  - Type: string
  - Description: Text file
- Ion_Mobility
  - Type: string
  - Description: Text file
- FT_ICR
  - Type: string
  - Description: Text file
- OrbiTrap
  - Type: string
  - Description: Text file

### Data_Processing

- Data_Processing_Glycan
  - Type: string
  - Description: Processing guidelines for glycan analysis
- Data_Processing_Glycoprotein
  - Type: string
  - Description: Processing guidelines for glycoprotein analysis

### Techniques_Glycan

- MassSpec
  - Type: string
  - Description: General Features - Document file
  