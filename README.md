# DIAexchange

This repo controls issues/discussions and guidelines about DIAexchange project. The DIAexchange project is a collaboration between [PeptideAtlas](https://peptideatlas.org/), [PRIDE database](https://www.ebi.ac.uk/pride/) and [Andy Jones's Group](https://www.liverpool.ac.uk/computational-biology-facility/).  

Here we list the ongoing projects of the Grant and the software developed within the Grant.

## Standarization of DIA data

Withing this project we aim to standarize the way DIA data is disaminated in the public domain including the deposition to ProteomeXchange repositories. 

### DIA experiments in SDRF-proteomics

[SDRF-proteomics](https://github.com/bigbio/proteomics-sample-metadata) is an standard format for sample metadata annotation of proteomics experiments and also represent the experimental design of proteomics experiments. In the first release of the [format](https://www.nature.com/articles/s41467-021-26111-3) we included multiple examples of LFQ and TMT experiments. In this grant we aim the following: 

- Include multiple datasets examples about How to annotate properly DIA datasets in SDRF-proteomics.
- Provide a list of well-annotated experiments in SDRF-proteomics for reanalysis by the community.
- A new version of the SDRF-proteomics will be released including all the changes suggsted by the community, version 1.2 of SDRF.

### USIs for DIA datasets

The HUPO-PSI and ProteomeXchange Consortium have create a mechanism to visualize and retrieve the corresponding spectrum used to identified a given peptidoform. The initiative callled [universal spectrum identifier (USI)](https://www.nature.com/articles/s41592-021-01184-6). During the publication of the original specification we define multiple USIs for DDA experiments: 

- [mzspec:PXD000561:Adult_Frontalcortex_bRP_Elite_85_f09:scan:17555:VLHPLEGAVVIIFK/2](https://www.ebi.ac.uk/pride/archive/usi?usi=mzspec:PXD000561:Adult_Frontalcortex_bRP_Elite_85_f09:scan:17555:VLHPLEGAVVIIFK/2&resultType=FULL)
- [mzspec:PXD000966:CPTAC_CompRef_00_iTRAQ_05_2Feb12_Cougar_11-10-09.mzML:scan:12298:[iTRAQ4plex]-LHFFM[Oxidation]PGFAPLTSR/3](https://www.ebi.ac.uk/pride/archive/usi?usi=mzspec:PXD000966:CPTAC_CompRef_00_iTRAQ_05_2Feb12_Cougar_11-10-09.mzML:scan:12298:[iTRAQ4plex]-LHFFM[Oxidation]PGFAPLTSR/3&resultType=FULL)

Two major tools could be used to visualize USI from ProteomeXchange projects/datasets: 

- [PRIDE USI Viewer](https://www.ebi.ac.uk/pride/archive/usi)
- [ProteomeCentral USI Viewer](https://proteomecentral.proteomexchange.org/usi/)

During this Grant we aim to develop and provide and extend USIs for DIA experiments including the development of examples to show HOW USIs could be generate from multiple popular DIA tools such as DIA-NN, quantms and others. In addition, we plan to extend the USIs to represent peptidoforms arising from multiple scans within the same MS run. Ongoing issues: 

- [Geneting USIs for quantms workflow](https://github.com/PRIDE-Archive/diaexchange/issues/1)
- [Proposal for multiple scan representation of USIs](https://github.com/PRIDE-Archive/diaexchange/issues/2)

In addition, PRIDE Team is planning to extend PRIDE USI Viewer to enable the visualization of both use cases. 

### Standarizing spectral libraries

As part of the DIAexchange a standard file format for spectral libraries has been developed. The new developed format [mzSpecLib](https://github.com/HUPO-PSI/mzSpecLib) will enable to exchange spectral libraries for DIA workflows based on spectral libraries. 

## Additional topics

- DIAexchange web page. Related issues:
  - [Issue 3](https://github.com/PRIDE-Archive/diaexchange/issues/3)  



   
