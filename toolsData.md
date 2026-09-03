---
title: Tools
Tools_Header: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/About/Data_Usage_Policies_Header.png"
navTitles:
  - CCDI-supported tools
  - BARDI
  - CCDI Data Model
  - CCDI ecDNA
  - C3DC Data Model
  - FrESCO
  - MCI_JSON2TSV
  - NCCR Treatment Database
  - WSI Informative Slide Selection
  - Additional tools of interest
  - AttentionAML
  - caDSR
  - Cancer Genomics Cloud
  - CIViC
  - dbGaP
  - EwS-Pacbio
  - GDC
  - GWAS Explorer
  - Kids First Data Resource
  - Methylscape
  - M-PACT
  - NCH-IGM ClinVar Submitter's Page
  - PMTL
  - RanBALL
  - STQ
  - Tucan
---

## CCDI-supported tools

### BARDI

BARDI is a data engineering tool to make clinical data “AI-ready” by transforming raw, unstructured inputs (like pathology reports) into structured, model-friendly formats. It provides modular pipelines for preprocessing tasks such as tokenization, normalization, and batch data handling, simplifying the development and maintenance of large-scale data workflows for machine learning. Overall, prepares clinical text and related data so downstream model frameworks (like [FrESCO](https://github.com/DOE-NCI-MOSSAIC/FrESCO)) can efficiently perform tasks such as information extraction and prediction.

Link: [https://github.com/DOE-NCI-MOSSAIC/bardi](https://github.com/DOE-NCI-MOSSAIC/bardi)

Contact: [hansonha@ornl.gov](mailto:HANSONHA@ORNL.GOV), [hsuel@mail.nih.gov](mailto:hsuel@mail.nih.gov)

### CCDI Data Model

The Childhood Cancer Data Initiative (CCDI) Data Model is a structured framework developed to standardize and harmonize pediatric cancer data across diverse research platforms. It defines key entities—such as participants, diagnoses, biospecimens, and treatments—and their relationships to ensure consistent data representation. The model plays a central role in enabling data integration, sharing, and analysis within the CCDI Data Ecosystem. To interactively view the data model, please click [here](/data-model).

Link: [https://github.com/CBIIT/ccdi-model](https://github.com/CBIIT/ccdi-model)

Contact: [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov)

### CCDI ecDNA

The CCDI Extrachromosomal DNA (ecDNA) portal is a comprehensive catalog of circular extrachromosomal DNA associated with childhood cancers. ecDNA, which frequently harbors amplified oncogenes, is a key driver of tumor development and progression, and its presence is linked to poor outcomes across multiple pediatric cancer types. This resource enables researchers to explore the prevalence, structure, and gene content of ecDNA in pediatric tumors, supporting studies in cancer biology, diagnosis, and potential therapeutic targets.

Link: [https://ccdi-ecdna.org/](https://ccdi-ecdna.org/)

Contact: [support@ccdi-ecdna.org](mailto:support@ccdi-ecdna.org), [lchavez@sbpdiscovery.org](mailto:lchavez@sbpdiscovery.org)

### C3DC Data Model

The Childhood Cancer Clinical Data Commons (C3DC) Data Model is a structured framework designed to standardize and harmonize pediatric cancer clinical data across diverse studies and platforms. It defines key entities—such as participants, diagnoses, biospecimens, and treatments—and their interrelationships to ensure consistent and interoperable data representation. By supporting the harmonization of data from multiple sources, the model enables researchers to work with integrated datasets, promoting efficient data sharing, analysis, and collaboration. To interactively view the data model, please click [here.](https://clinicalcommons.ccdi.cancer.gov/data-model)

Link: [https://github.com/CBIIT/c3dc-model](https://github.com/CBIIT/c3dc-model)

Contact: [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov)

### FrESCO

FrESCO (Framework for Exploring Scalable Computational Oncology) is a modular deep learning NLP framework designed to automatically extract structured cancer information from clinical text documents at scale. FrESCO employs [BARDI](https://github.com/DOE-NCI-MOSSAIC/bardi) as part of processing. Surveillance, Epidemiology, and End Results (SEER) program collects and analyzes data from pathology reports across state registries, but extracting detailed cancer phenotypes from these reports is labor-intensive and requires expert knowledge. Automating this process can improve data consistency, speed, and enable time-sensitive applications like precision medicine.

Link: [https://github.com/DOE-NCI-MOSSAIC/FrESCO](https://github.com/DOE-NCI-MOSSAIC/FrESCO)

Contact: [hansonha@ornl.gov](mailto:HANSONHA@ORNL.GOV), [hsuel@mail.nih.gov](mailto:hsuel@mail.nih.gov)

### MCI_JSON2TSV

The MCI_JSON2TSV script is a Python-based command-line interface developed by the NCI's Childhood Cancer Data Initiative (CCDI). Its primary function is to convert Molecular Characterization Initiative's de-identified clinical report and clinical data files submitted in JSON format into tab-separated values (TSV) files. It can generate a single TSV that combines all case report form types, or, if preferred, create separate TSVs by form type or parsed variant results, making it easier to analyze, share, and integrate data with downstream systems. For more information on how to use this tool, please access documentation [here](https://www.ccdi.cancer.gov/MCI_JSON2TSV).

Link: [https://github.com/CBIIT/ChildhoodCancerDataInitiative-MCI_JSON2TSV](https://github.com/CBIIT/ChildhoodCancerDataInitiative-MCI_JSON2TSV)

Contact: [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov)

### NCCR Treatment Database

The NCCR Treatment Database provides structured data and tooling related to cancer treatment information derived from registry and clinical sources. It is designed to support AI/ML workflows and natural language processing by organizing treatment-related variables that can be used for model training, evaluation, and cancer surveillance research. This resource helps standardize and make treatment data more accessible for large-scale computational oncology efforts, enabling analysis of real-world cancer treatments alongside other population-level data.

Link: [https://github.com/DOE-NCI-MOSSAIC/nccr-treatment-database](https://github.com/DOE-NCI-MOSSAIC/nccr-treatment-database)

Contact: [hansonha@ornl.gov](mailto:HANSONHA@ORNL.GOV), [hsuel@mail.nih.gov](mailto:hsuel@mail.nih.gov)

### WSI Informative Slide Selection

A pipeline that uses deep learning models to classify histopathology whole-slide image (WSI) thumbnails across multiple diagnostic relevance tasks. It predicts slide-level attributes including absolute and relative informativeness, image quality, and tumor presence. The system enables efficient pre-screening and quality assessment of pathology slides to support downstream computational pathology workflows.

Link: [https://github.com/DOE-NCI-MOSSAIC/wsi-informative-slide-selection](https://github.com/DOE-NCI-MOSSAIC/wsi-informative-slide-selection)

Contact: [hansonha@ornl.gov](mailto:HANSONHA@ORNL.GOV), [hsuel@mail.nih.gov](mailto:hsuel@mail.nih.gov)

## Additional tools of interest

### AttentionAML

AttentionAML is a novel deep learning framework that uses an attention-based multilayer perceptron (MLP) model to accurately identify acute myeloid leukemia (AML) subtypes from transcriptomic data alone. A user-friendly Python package is available to help researchers implement the model. It enables precise classification and clustering of AML subtypes, and facilitates improved risk stratification and personalized treatment planning.

Link: [https://github.com/wan-mlab/AttentionAML](https://github.com/wan-mlab/AttentionAML)

Contact: [swan@unmc.edu](mailto:swan@unmc.edu)

### caDSR

The Cancer Data Standards Repository is one of the largest common data element (CDE) registries developed by the National Cancer Institute (NCI) and contains over **76,600 CDEs** covering many aspects of cancer research. There are over 490 pediatric CDEs used by various entities like CCDI Data Ecosystem and Pediatric Clinical Data commons. The **Pediatric Cancer Core Common Data Elements** were created to standardize data collection and sharing for pediatric cancer research. To explore these standards, visit the caDSR homepage and select "Pediatric Cancer Core CDEs" under the Favorites column for a custom report of key CDEs.

Link: [https://cadsr.cancer.gov/onedata/Home.jsp](https://cadsr.cancer.gov/onedata/Home.jsp)

Contact: [caDSR.RA@mail.nih.gov](mailto:caDSR.RA@mail.nih.gov)

### Cancer Genomics Cloud

The NCI's Cancer Genomics Cloud (CGC), powered by Velsera, is a cloud-based platform that enables analysis, storage, and computation of large cancer datasets. The CGC provides a user-friendly portal to access and analyze more than 3 petabytes of data. It offers over 900 bioinformatics tools and workflows, allowing users—including those without programming experience—to perform complex analyses and collaborate with a global community of over 8,000 researchers.

Link: [https://www.cancergenomicscloud.org/](https://www.cancergenomicscloud.org/)

Contact: [cgc-sb@velsera.com](mailto:cgc-sb@velsera.com)

### CIViC

Clinical Interpretation of Variants in Cancer (CIViC) is an open-access, open-source, community-driven knowledgebase for the clinical interpretation of cancer variants. The platform enables crowdsourced curation and expert moderation of literature-derived evidence, providing structured, peer-reviewed data on the clinical significance of somatic and germline mutations in cancer. CIViC supports variant interpretation for diagnosis, prognosis, and therapy selection, and integrates with emerging guidelines and other variant resources to advance precision oncology.

Link: [https://civicdb.org/](https://civicdb.org/)

Contact: [help@civicdb.org](mailto:help@civicdb.org)

### dbGaP

dbGaP (Database of Genotypes and Phenotypes) is a resource developed by the National Center for Biotechnology Information (NCBI) to store and distribute data from studies exploring the relationship between genetic variation (genotypes) and observable traits in humans (phenotypes). It houses genomic, imaging, clinical, and other types of individual-level data. To protect participant privacy, access to controlled-access data requires researchers to submit a [data access request](https://sharing.nih.gov/accessing-data/accessing-genomic-data/how-to-request-and-access-datasets-from-dbgap).

Link: [https://www.ncbi.nlm.nih.gov/gap/](https://www.ncbi.nlm.nih.gov/gap/)

Contact: [dbgap-help@ncbi.nlm.nih.gov](mailto:dbgap-help@ncbi.nlm.nih.gov)

### EwS-Pacbio

The EwS-Pacbio repository provides tools for analyzing long-read targeted sequencing FASTQ files to investigate microsatellites and germline variants associated with Ewing sarcoma (EwS) susceptibility. Leveraging PacBio sequencing technology, the resource enables high-resolution investigation of genetic risk factors, including variant analysis and microsatellite profiling. It includes workflows and visualizations fused in associated publications, supporting deeper insights into EwS-related genetic mechanisms.

Link 1: Code for 6p25.1 microsatellite and germline variant analysis is available at: [https://github.com/machiela-lab/EwS-Pacbio](https://github.com/machiela-lab/EwS-Pacbio)

Link 2: Code for gene expression analysis is available at: [https://github.com/calvin-s-rodrigues/EwS_6p25.1_RREB1](https://github.com/calvin-s-rodrigues/EwS_6p25.1_RREB1)

Contact: [mitchell.machiela@nih.gov](mailto:mitchell.machiela@nih.gov)

### GDC

The GDC Data Portal is a robust data-driven platform that allows cancer researchers and bioinformaticians to search and download cancer data for analysis.

Link: [https://portal.gdc.cancer.gov/](https://portal.gdc.cancer.gov/)

Contact: [support@nci-gdc.datacommons.io](mailto:support@nci-gdc.datacommons.io)

### GWAS Explorer

GWAS Explorer allows genetics researchers to search, visualize, and download aggregated association results from genome-wide association studies (GWAS). It provides association summary statistics for over 200 cancer and cancer-related phenotypes, harmonized from large-scale GWAS efforts. Interactive tools are available to visualize and examine association results utilizing dynamic Manhattan and Miami plots, stratify data by sex and ancestry, and review diagnostic plots (e.g., Q-q plots).

Link: [https://exploregwas.cancer.gov/#/](https://exploregwas.cancer.gov/#/)

Contact: [NCIExploreGWASWebAdmin@mail.nih.gov](mailto:NCIExploreGWASWebAdmin@mail.nih.gov)

### Kids First Data Resource

Gabriella Miller Kids First Data Resource Center (DRC)'s cloud-based platform provides access to large-scale pediatric genomic and clinical data for childhood cancer research. This helps researchers uncover new insights into the biology of childhood cancer and structural birth defects, including the discovery of shared genetic pathways between these disorders.

Link: [https://portal.kidsfirstdrc.org/login/](https://portal.kidsfirstdrc.org/login)

Contact: [support@kidsfirstdrc.org](mailto:support@kidsfirstdrc.org)

### Methylscape

Methylscape is a clinically reportable genome-wide DNA methylation profiling tool that classifies central nervous system tumors by comparing their epigenetic signatures to reference datasets, enabling more precise and objective tumor diagnosis beyond histopathology alone.

Link: [https://methylscape.ccr.cancer.gov/](https://methylscape.ccr.cancer.gov/)

Contact: [NCIMethylscapeWebAdmin@mail.nih.gov](mailto:NCIMethylscapeWebAdmin@mail.nih.gov)

### M-PACT

M-PACT is a deep learning-based classifier that uses DNA methylation profiles from cell-free DNA in cerebrospinal fluid to noninvasively identify pediatric central nervous system (CNS) tumor types with high accuracy (≈92% in benchmark cohorts). M-PACT overcomes challenges of low tumor DNA abundance and sparse methylation data in liquid biopsies, enabling accurate tumor classification and cellular deconvolution without requiring tissue biopsies.

Link: [https://mpact.stjude.org](https://mpact.stjude.org)

Contact: [paul.northcott@stjude.org](mailto:paul.northcott@stjude.org)

### NCH-IGM ClinVar Submitter's Page

ClinVar submissions are records provided by researchers, clinical labs, and other contributors that describe relationships between genetic variants and their clinical significance. These submissions include interpretations (such as pathogenic or benign), supporting evidence, and review status, helping aggregate and compare variant knowledge across the scientific and medical community. The Nationwide Children's Hospital Institute for Genomic Medicine (IGM) Clinical Laboratory submits clinically significant variants reviewed and curated from clinical testing for inclusion in ClinVar, including somatic and germline variants relevant for pediatric cancers. A listing of submitted clinical variants, viewable by gene and condition, from NCH-IGM is available at the submitter's page in ClinVar.

Link: [https://www.ncbi.nlm.nih.gov/clinvar/submitters/196472/](https://www.ncbi.nlm.nih.gov/clinvar/submitters/196472/)

Contact: [Catherine.Cottrell@nationwidechildrens.org](mailto:Catherine.Cottrell@nationwidechildrens.org)

### PMTL

In 2018, the United States Food & Drug Administration (FDA) published the Pediatric Molecular Target Lists (PMTL). Briefly, these lists contain targets that are **important for studies of pediatric cancer**; one list defines molecular targets that are relevant to the growth of pediatric cancer, while the other defines molecular targets that are explicitly not relevant. The targets in these lists have **special legal requirements** associated with drug development.

Link: [https://cbiit.github.io/ccdi-pmtl-pages/](https://cbiit.github.io/ccdi-pmtl-pages/)

Contact: [OCEPeRC@fda.hhs.gov](mailto:OCEPeRC@fda.hhs.gov)

### RanBALL

RanBALL is an ensemble machine learning model that uses random projection and support vector machines to accurately and cost-effectively identify B-cell acute lymphoblastic leukemia (B-ALL) subtypes using only transcriptomic profiling data. This tool improved clinical diagnosis, risk stratification, and personalized treatment for B-ALL patients through effective classification and visualization.

Link: [https://github.com/wan-mlab/RanBALL](https://github.com/wan-mlab/RanBALL)

Contact: [lli@unmc.edu](mailto:lli@unmc.edu)

### STQ

The Spatial Transcriptomics Quantification pipeline (STQ) enables deconvolution of mouse and human reads, alignment of imaging and spatial gene expression, and extraction of quantitative morphology and imaging features for 10x Genomics Visium spatial transcriptomics data together with matching H&E whole-slide images, facilitating integrated analysis of spatial gene expression and histology. Its utility in integrating transcriptomic and image-derived features support multimodal characterization of tumor microenvironments.

Link: [https://github.com/TheJacksonLaboratory/STQ](https://github.com/TheJacksonLaboratory/STQ)

Contact: [sergii.domanskyi@jax.org](mailto:sergii.domanskyi@jax.org)

### Tucan

Tucan is a methylation-based classification model for pediatric solid tumors. Tucan can distinguish 91 different pediatric solid tumor subtypes and works with both methylation array data or nanopore based methylation data as input.

Link: [https://github.com/UMCUGenetics/tucan](https://github.com/UMCUGenetics/tucan)

Contact: [l.a.kester@prinsesmaximacentrum.nl](mailto:l.a.kester@prinsesmaximacentrum.nl)
