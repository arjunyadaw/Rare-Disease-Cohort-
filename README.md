# Systematic identification of rare disease patients in electronic health records enables evaluation of COVID-19 or other clinical outcomes
xyz,yyz,..
# Project summary 
There are over 10,000 rare diseases. 

In fact, rare diseases are estimated to affect more than 30 million people in the United States. Each disease may be rare individually, but people with rare diseases often face similar challenges. These challenges may include accessing information, getting a diagnosis, and finding resources (https://rarediseases.info.nih.gov/about). In the United States, a rare disease is one that fewer than 200,000 people live with. (In other words, 6 per 100,00 individuals.)

Mapping rare diseases to EHR data is challenging because large number of rare disease are not codded or mapped to group of disorders or phenotype. In this project, we aim to create rare disease mapping to EHR system by using ICD-10 codes & SNOMED-CT codes. We constructed a cohort of COVID-19 infected individuals that had a rare disease (RDs) diagnosis prior to COVID-19 infection, as defined in our workflow figure 2.  To accomplish this, we created a curated list of unique rare diseases, defined by 12,004 GARD IDs(ref of GARD website).  These GARD_IDs were mapped with ORPHANET (July 2023 version) which mapped 9,369 rare diseases.  Of the 9,369 GARD IDs mapping to ORPHANET, 2,725 did not map to either a SNOMED_CT or ICD10 code and were discarded.  The remaining diseases were represented by 6,555 SNOMED-CT and 575 ICD10 codes.  We note that ICD10 codes represent single diseases with no descendent.  
