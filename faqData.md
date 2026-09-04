---
title: CCDI FAQs
headerImage: ""
categories:
  - id: data-exploration
    name: Data Exploration and Data Access
  - id: mci
    name: Molecular Characterization Initiative (MCI)
  - id: data-submission
    name: Data Submission to CCDI
---

# How do I filter and query metadata related to studies in the Childhood Cancer Clinical Data Commons (C3DC)?

Users can explore data two ways in C3DC: by participants or by files.

To filter and query metadata by participants, start by navigating to the [Explore Participants](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/exploreParticipants)) tab. On the left-hand side, a panel of filters allows users to refine the metadata using criteria such as study, diagnosis, anatomic site, and more. As filters are applied, the dashboard dynamically updates the displayed data and counts. Once filtering is complete, users can export metadata from the metadata tables at the bottom of the screen, view and filter the associated files on the [Explore Files](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/exploreFiles) tab or further explore the filtered data using the [Cohort Analyzer](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/cohortAnalyzer).

To filter and query metadata by files, start by navigating to the [Explore Files](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/exploreFiles) tab. On the left-hand side, a panel of filters allows users to refine the metadata using criteria such as data category, file type, or library strategy. As filters are applied, the dashboard dynamically updates the displayed data and counts. Once filtering is complete, users can export metadata from the metadata tables at the bottom of the screen, view and filter the associated participants on the [Explore Participants](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/exploreParticipants) tab or further explore the filtered data using the [Cohort Analyzer](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/cohortAnalyzer).

For more information, please see the [C3DC user guide](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/user_guide).

| Property | Value |
| --- | --- |
| id | filter-query-metadata |
| category | data-exploration |

---

# How can I apply for controlled data access to a CCDI-indexed study?

To gain access to controlled data, researchers must first have an NIH eRA Commons account for authentication.

Researchers may then request authorization by the NIH database of Genotypes and Phenotypes (dbGaP). Authorization is enforced by the Data Commons Framework Services (DCFS), whether accessing directly from DCFS or through the Cancer Genomics Cloud (CGC). A step-by-step breakdown of the data access request process is available in this [guide](https://sharing.nih.gov/accessing-data/accessing-genomic-data/how-to-request-and-access-datasets-from-dbgap).

For more information on applying for controlled data access, please see the ‘Data Access’ and ‘Appendix A: database of Genotypes and Phenotypes (dbGaP)’ sections in the [C3DC user guide](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/user_guide).

| Property | Value |
| --- | --- |
| id | controlled-data-access |
| category | data-exploration |

---

# What should I do if I cannot access CCDI data from the Cancer Genomics Cloud (CGC)?

You will need to verify whether your dbGaP data access request is still active or has expired. There are two ways to do this:

**Option 1: DCF**

Log into the NCI [Data Commons Framework Services](https://dcf.gen3.org/) portal using your eRA Commons credentials. After logging in, click the 'Profile' button in the upper-right hand corner. You should see a list of the phs accession numbers of studies for which you have access. If your access is active and you are still experiencing issues, please contact the [CGC Helpdesk](mailto:support@velsera.com) for further assistance.  If your access has expired, please follow the dbGaP renewal process to restore access. To learn more about submitting a renewal request, please view the [dbGaP video tutorial](https://www.youtube.com/watch?v=Xyldg6RDxqc) on project renewals.

**Option 2: dbGaP**

Log into [dbGaP](https://dbgap.ncbi.nlm.nih.gov/aa/wga.cgi?page=login) using your eRA Commons credentials. Navigate to the ‘My Projects’ tab in the dbGaP ‘Authorized Access’ section. You can then view which projects you are approved to access. Please note that an annual renewal of access is required for access to a project. If your access has expired, please follow the dbGaP renewal process to restore access. To learn more about submitting a renewal request, please view the [dbGaP video tutorial](https://www.youtube.com/watch?v=Xyldg6RDxqc) on project renewals.

| Property | Value |
| --- | --- |
| id | cgc-access-issues |
| category | data-exploration |

---

# As a dbGaP-approved user for studies in the Childhood Cancer Clinical Data Commons (C3DC), how can I download the data?

Please refer to the instructions in the [C3DC user guide](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/user_guide): **Appendix B: NCI Data Commons Framework Services (DCFS): Controlled Data Access Instructions** and **Appendix C: The Cancer Genomics Cloud (CGC)**.

We recommend using the Data Commons Framework (DCF) index of files with the gen3-client to download large amounts of files. For more information, please see **Appendix B** in the [C3DC user guide](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/user_guide).

For some historical projects, such as phs000720, portions of the data are stored in the NCBI SRA repository. Please see [this guide](https://github.com/ncbi/sra-tools/wiki) for using SRA Toolkit to download data from SRA.

| Property | Value |
| --- | --- |
| id | download-dbgap-approved |
| category | data-exploration |

---

# What is the difference between data in the Childhood Cancer Clinical Data Commons (C3DC), the CCDI cBioPortal, and the GDC?

Data hosted at the C3DC are source metadata and files from the CCDI indexed studies and are explorable via facet filters for finding relevant data files for user download and analysis.  These data include molecular assay files, imaging, and clinical files. Additionally, clinical alteration data from clinical reports, when available, are presented in the genetic analysis facet and table in the C3DC application. In contrast, data hosted at CCDI cBioPortal are currently derived data from source mutation call files and visualized through a number of widgets such as OncoPrints, mutation plots, survival plots to allow for deep analysis into specific alterations across different disease types. Molecular data available at the GDC have been harmonized with GDC Data Harmonization pipelines.

| Property | Value |
| --- | --- |
| id | c3dc-cbioportal-gdc-difference |
| category | data-exploration |

---

# How do I cite data in the CCDI?

The NCI expects users to acknowledge CCDI data use as follows:

“The results published here are, in whole or in part, derived from the analysis of data listed in the Childhood Cancer Clinical Data Commons (C3DC) ([https://clinicalcommons.ccdi.cancer.gov/](https://clinicalcommons.ccdi.cancer.gov/)), established by the Childhood Cancer Data Initiative (CCDI)”.

To cite individual studies, note the CCDI Study ID (e.g., phs002790) and include the name and URL or link for the Childhood Cancer Clinical Data Commons (https://clinicalcommons.ccdi.cancer.gov/), along with the phrase, established by the National Cancer Institute’s Childhood Cancer Data Initiative (CCDI).

Example: “The results analyzed and <published or shown> here are based in whole or in part from analyzing the Molecular Characterization Initiative data listed in the C3DC (https://clinicalcommons.ccdi.cancer.gov/) under Study ID phs002790, established by the Childhood Cancer Data Initiative (CCDI).”

For more information, please see the [CCDI Data Usage Policies and Terms](https://ccdi.cancer.gov/data-usage-policies).

| Property | Value |
| --- | --- |
| id | cite-ccdi-data |
| category | data-exploration |

---

# Are there restrictions on the use of CCDI Data in publications?

Users may publish findings derived from CCDI data in accordance with applicable data use terms and policies. Users are expected to comply with any data use limitations, acknowledge relevant data and funding sources as required, and ensure that no information is disclosed that could reasonably be used to identify individual participants.

| Property | Value |
| --- | --- |
| id | publication-restrictions |
| category | data-exploration |

---

# What is the cadence of data releases in CCDI and how can I stay informed of when they occur?

Releases aim for a quarterly cadence. Updates on releases can be found at the [News](/news) and [Release Notes](/release-notes) pages of the [ccdi.cancer.gov](https://ccdi.cancer.gov) website and [Release Notes](https://clinicalcommons.ccdi.cancer.gov/release_notes_pdf) pages of the CCDI C3DC application.

| Property | Value |
| --- | --- |
| id | data-release-cadence |
| category | data-exploration |

---

# Where can I find more information about the CCDI Data Model?

The [CCDI Data Model](https://clinicalcommons.ccdi.cancer.gov/data_model) can be viewed in the interactive Data Model Navigator application where data model properties and acceptable values can be viewed and downloaded for interoperability and reference.

| Property | Value |
| --- | --- |
| id | data-model-info |
| category | data-exploration |

---

# Who do I contact for assistance or report an issue about the CCDI Ecosystem applications and data?

For inquiries, suggestions or assistance with CCDI Ecosystem applications and data, please email the CCDI mailbox at [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov).

| Property | Value |
| --- | --- |
| id | contact-assistance |
| category | data-exploration |

---

# How do I find alternate participant IDs that might be used in other commons, studies or clinical trials?  

The CCDI Participant Index (CPI) is a CCDI-supported API that manages, maps, and shares research participant IDs representing the same de-identified individual across different projects, cross-referencing all known IDs for a participant across pediatric cancer studies spanning multiple diverse domains. 

There are two ways to access these mappings: 

1. View mapped IDs in the C3DC: the [Participant Explore Dashboard](https://clinicalcommons-integrated-dev.ccdi.cancer.gov/exploreParticipants) displays participant research identifiers and their mapped IDs, serving as a reference point for finding a participant's data across resources. Users can also download facet-filtered, participant table records that include available alternate IDs.  
2. Request direct API access: for programmatic or bulk ID cross-referencing, system owners can request access by emailing [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov).

For more information, please CPI API specification here: [https://participantindex-docs.ccdi.cancer.gov/](https://participantindex-docs.ccdi.cancer.gov/)

| Property | Value |
| --- | --- |
| id | alternative-ids |
| category | data-exploration |

---

# Do the clinical summary reports/lab data exist in a structured format?

De-identified clinical summary reports are available in both PDF and JSON formats. Data from the sample reports can also be parsed and filtered using the CCDI MCI JSON2TSV tool, available as a [GitHub repository](https://github.com/CBIIT/ChildhoodCancerDataInitiative-MCI_JSON2TSV/) with documentation as well as a [public application](https://cgc.sbgenomics.com/public/apps/rowan_beck_era/ccdi-mci-json2tsv-commit/json2tsv) in the Cancer Genomics Cloud (CGC) to perform transformations on CGC hosted files. The JSON2TSV tool can parse a set of MCI clinical report JSONs and transform and aggregate them to human-readable formats.

| Property | Value |
| --- | --- |
| id | mci-clinical-reports-format |
| category | mci |

---

# Can sites connect MCI’s genomic data with clinical reports and other data types (such as imaging)?

Yes. Deidentified clinical reports are available in both JSON and PDF formats and can be accessed through the dbGaP approval process along with the underlying genomic data. All data shared through the CCDI Data Ecosystem are associated with USIs, which allows these data types to be connected. For assistance with access or mapping, please contact the CCDI Helpdesk at [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov).

| Property | Value |
| --- | --- |
| id | mci-connect-data-types |
| category | mci |

---

# Are there institutional IDs attached to the MCI data so we can connect to the treatment or EHR information at our sites?

No, institutional IDs are not attached to the data as CCDI does not receive them. All data shared through the CCDI Data Ecosystem are associated only with USIs. However, sites can work with CCDI to connect data using the CCDI Participant Index (CPI), which can facilitate the mapping of COG IDs to USIs when COG IDs are available at the institution. For questions, please contact the CCDI mailbox at [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov).

| Property | Value |
| --- | --- |
| id | mci-institutional-ids |
| category | mci |

---

# Is it possible to download the de-identified clinical summary reports for MCI participants directly without going through the dbGaP approval process?

No. Access to MCI participant-level clinical data, including de-identified clinical summary reports, requires appropriate authorization through the dbGaP data access process. Although the reports are de-identified, they may contain information that is subject to controlled-access requirements designed to protect participant privacy and comply with data-sharing policies.

However, certain MCI data are available through open-access resources. Somatic variants and alterations can be explored through the C3DC Genetic Analysis Node. Clinical and molecular data can be explored through the CCDI cBioPortal, and open-access methylation data files are available through the Genomic Data Commons (GDC).

| Property | Value |
| --- | --- |
| id | mci-clinical-reports-without-dbgap |
| category | mci |

---

# Why are some participants no longer available in the MCI study within the Childhood Cancer Clinical Data Commons (C3DC) and CCDI cBioPortal?

From time to time, participant eligibility is reviewed by the Children's Oncology Group (COG) Statistical Data Coordinating Center. When notified by COG, CCDI removes ineligible participants and associated data from CCDI Ecosystem applications and resources. The list of removed participants is available for download from the [CCDI MCI website](/MCI).

| Property | Value |
| --- | --- |
| id | mci-removed-participants |
| category | mci |

---

# How can I access metadata for the MCI imaging data in the Imaging Data Commons (IDC)?

Several CCDI studies have pathology images available in the [Imaging Data Commons](https://portal.imaging.datacommons.cancer.gov/) (IDC), including the MCI. To download the associated clinical data for MCI participants with pathology slide images, there are two options:

**Option 1: Download Participant IDs and Upload to CCDI**

1. [Visit the IDC Slide Microscopy Summary](https://portal.imaging.datacommons.cancer.gov/explore/).
2. Download the list of participant IDs by selecting the Kebab/More Options menu in the “Selected Patient IDs” panel > Export Chart > Export Data.
3. Go to the C3DC Explore Participants page.
4. Upload your list of participant IDs under the “Demographics” section.
5. The application will filter the results for you. From these filtered results, you can download each tab of the table for the selected metadata that is presented.
6. For all metadata on the study, go to the “Studies” tab, and select the download icon in the “Manifest” column to download the manifest metadata as an XLSX file.

**Option 2: Use the CCDI C3DC website to Apply Filters**

1. Go to the C3DC Explore Participants page.
2. On the left side, find the filter panel and click on the “Study” option.
3. Select **phs002790** under the “dbGaP Accession” facet to limit the datasets to the MCI study.
4. Go to the “Studies” tab at the bottom of the page.
5. Click the download icon in the “Manifest” column to download the manifest metadata as an XLSX file.

| Property | Value |
| --- | --- |
| id | mci-idc-imaging-metadata |
| category | mci |

---

# What is the process for submitting pediatric cancer datasets to be hosted in the CCDI Data Ecosystem?

Detailed guidance for submitting data and tools is available in the [CCDI Data Ecosystem: Data & Tools Submission Guidance](/Submission_Guide.pdf) document.

The CCDI Data Model and submission template are available in GitHub: [https://github.com/CBIIT/ccdi-model/tree/main/metadata-manifest](https://github.com/CBIIT/ccdi-model/tree/main/metadata-manifest). The most up-to-date version of the CCDI metadata template can be downloaded by selecting the download icon on the GitHub page. The ‘Dictionary’ tab contains the metadata property name, descriptions, and associated Common Data Elements (CDEs). The ‘Terms and Value Sets’ tab lists the permissible values for each metadata property.

| Property | Value |
| --- | --- |
| id | submit-datasets |
| category | data-submission |
