---
title: CCDI MCI_JSON2TSV
# Headings below must match ## line text in the body exactly.
navTitles:
  - Finding and Exporting MCI Clinical JSON files in C3DC Explore Dashboard
  - Running the JSON2TSV tool in the Cancer Genomics Cloud (CGC)
  - CGC Resources
  - Contact and MCI JSON2TSV Source Code
---

The CCDI MCI JSON2TSV Tool aggregates and reformats data in CCDI Molecular Characterization Initiative (MCI) clinical reports in JSON format from Children’s Oncology Group (COG) and the Nationwide Children’s Hospital Institute for Genomic Medicine (NCH-IGM) into tabular format files (TSV). These include participant-level clinical data and clinician reviewed, sample-level significant genomic alterations contained in clinical reports.

When both COG and NCH-IGM clinical reports are input to be processed together, the tool also generates an integrated format (XLSX) that combines clinical data from both report types, displaying data for a patient as a single record. Patient data are separated by MCI enrollment groups into distinct sheets in the integrated workbook for relevant comparison of clinical report data by MCI enrollment group.

The CCDI MCI JSON2TSV Tool is presented as an application in the Cancer Genomics Cloud (CGC) that can be imported into CGC users’ workspace to perform aggregation and reformatting of MCI clinical reports. The application version of the tool is available at this link: [https://cgc.sbgenomics.com/u/rowan_letter_era/ccdi-mci-json2tsv-commit](https://cgc.sbgenomics.com/u/rowan_letter_era/ccdi-mci-json2tsv-commit).

For more information regarding using the CGC, including registering an account and applying for first time use credits, please see [Getting Started](https://www.cancergenomicscloud.org/getting-started).

> **Note:** COG clinical reports detail CRFs related to treatment, diagnosis, laboratory tests and other clinical data. NCH-IGM clinical reports detail clinician curated molecular alterations, including somatic and germline mutations and copy number alterations, from the Somatic Disease/Germline Comparator Exome Test; fusion events from the Archer Fusion panel Solid Tumor Fusion Analysis; and CNS Tumor Classification by Methylation Array, from DKFZ CNS Classifier versions v11b6, v12.6 or IGM Central Nervous System Classifier V1.0. The data dictionary for the JSON2TSV tool will be updated with subsequent MCI COG and/or IGM releases to incorporate any new data elements being transmitted by COG or IGM in clinical data files for the integrated view.

## Finding and Exporting MCI Clinical JSON files in C3DC Explore Dashboard

| Property | Value |
| --- | --- |
| id | FINDING_AND_EXPORTING_MCI_CLINICAL_JSON |

MCI and other CCDI indexed studies’ data files are indexed at the C3DC Explore Dashboard. To find MCI clinical JSON reports in the C3DC application, use the following facets:

Filter down to the MCI study, dbGaP accession `phs002790`, from the Explore Participants dashboard:

**Figure D1: Participant Explore Study filters to select for MCI participant data**

![Figure D1: Participant Explore Study filters to select for MCI participant data](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/MCI_JSON2TSV/FigureD1.png)

Then select the clinical files of interest from the Explore Files dashboard **Data Category > Data Category** facet. Note that selections in the dashboard are additive.

- **Clinical:** Selects all Clinical files, COG and IGM.
- **COG Clinical Report:** Select COG clinical data reports.
- **Gene Fusion Clinical Report:** Select reports of clinician reviewed, disease relevant fusions from Archer Fusion panel, delivered by IGM.
- **Methylation Clinical Data:** Select output of clinically validated methylation-based disease classifier, MCI CNS cases only, delivered by IGM.
- **Tumor Normal Clinical Data:** Select reports of clinician reviewed, disease relevant mutations and copy number alterations from Somatic Germline Exome Comparator test, delivered by IGM.

**Figure D2: File Explore Data Category filters for selecting relevant clinical files for MCI participants**

![Figure D2: File Explore Data Category filters for selecting relevant clinical files for MCI participants](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/MCI_JSON2TSV/FigureD2.png)

Additional filters from other facets, including Diagnosis, Demographics, etc., can be applied to further filter clinical files down to those from applicable participants of the MCI study.

To export files to the CGC for download or to run the MCI JSON2TSV app version:

**Figure D3: Adding filtered files to Cart and exporting to CGC**

![Figure D3: Adding filtered files to Cart and exporting to CGC](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/MCI_JSON2TSV/FigureD3.png)

1. After filtering down from facets the relevant cohort and files, navigate to the **Files** tab and select **Add all filtered files** button to add all files to the cart.

2. Select the files **Cart** button in the upper right-hand corner to navigate to the cart page. From the cart page, select the **Available Export Options** dropdown menu, and select **Export to Cancer Genomics Cloud**.

3. Users will then be prompted to log into the CGC with their eRA Commons or other login method. After authentication, users will be prompted with a dialog box. Specify which project to direct files to, existing project in CGC or create a new project, how to handle naming conflicts, add any applicable tags (optional), and then check the confirmation box for complying with any data use agreements for the data. Users can then initiate the export by selecting the green button in the lower right-hand corner, **Import data**.

> **Note:** To export controlled access files from the C3DC Explore Files dashboard into the Cancer Genomics Cloud, users must have been granted controlled data access via dbGaP for applicable studies in CCDI, i.e. `phs002790`. For more information, please see Appendix A for dbGaP controlled data access.

## Running the JSON2TSV tool in the Cancer Genomics Cloud (CGC)

| Property | Value |
| --- | --- |
| id | RUNNING_JSON2TSV_IN_CGC |

The MCI JSON2TSV tool is supported and maintained by the CCDI team and is available at GitHub for use on a local computer, or as an application at the Cancer Genomics Cloud (CGC). For large amounts of data and/or for a more user friendly version, we highly suggest using the CGC application version, as users can export MCI clinical report files from the CCDI Hub to the CGC and run the tool on files in their cloud workspace as opposed to downloading large amounts of files locally.

Prior to running the application, ensure that the clinical JSON files of interest have been moved into a folder within the **Files** tab to serve as input to the application:

**Figure D4: Moving imported files in CGC into designated input folder for JSON2TSV tool**

![Figure D4: Moving imported files in CGC into designated input folder for JSON2TSV tool](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/MCI_JSON2TSV/FigureD4.png)

1. From the **Files** tab in the working CGC project, select the **New Folder** button from the upper right-hand corner. From the pop-up dialog box, enter the name of the folder and then select **Create**.

2. Select the files to be moved to the folder from the left-hand checkboxes, or the select-all checkbox in the column header, then select **Move** from the task bar and then select the created folder to move the files to. Finally, initialize the file move by selecting the green **Move** button in the lower right-hand corner.

A summarized view of installing and running the app in CGC workspace is below:

**Figure D5: Steps for installing and running the JSON2TSV tool in a given CGC Project space**

![Figure D5: Steps for installing and running the JSON2TSV tool in a given CGC Project space](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/MCI_JSON2TSV/FigureD5.png)

1. From the working CGC project, select the **Apps** button in task bar.

2. From the Apps page in the working CGC project, click the green **Add apps** button, and select **Public apps** from dropdown.

3. In pop-up box, enter search term `JSON2TSV`.

4. The CCDI MCI JSON2TSV application should pop up; select the app or select the **Copy** button to copy app to the working CGC project.

5. To run the app, from within the JSON2TSV app instance copied to the working CGC project, select the green **Run** button in upper right-hand corner.

6. From the run application page, select the input folder that contains the JSON files to be aggregated and transformed.

7. To initiate the run of the application on the selected input folder, select the blue **Run** button in upper right-hand corner. Cost and duration for transforming 1,000 files is ~`$0.02` and 3 minutes, respectively.

8. Files will be output at conclusion of application run in the **Files** tab of the working CGC project.

**Figure D6: Example output file set for JSON2TSV tool**

![Figure D6: Example output file set for JSON2TSV tool](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/MCI_JSON2TSV/FigureD6.png)

Outputs can be downloaded or directed to a specific created folder in Root directory of project; this can be specified when specifying inputs to tool at set up of run/task.

## CGC Resources

| Property | Value |
| --- | --- |
| id | CGC_RESOURCES |

- **CGC Resource Site:** [https://cgc.sbgenomics.com/](https://cgc.sbgenomics.com/)
- **CGC User Guide:** [https://docs.cancergenomicscloud.org/page/comprehensive-tips-for-reliable-and-efficient-analysis-set-up](https://docs.cancergenomicscloud.org/page/comprehensive-tips-for-reliable-and-efficient-analysis-set-up)
- **CGC Quick Start Guide:** [https://docs.cancergenomicscloud.org/page/uncontrolled-data-quickstart-guide](https://docs.cancergenomicscloud.org/page/uncontrolled-data-quickstart-guide)
- **CGC FAQ:** [https://www.cancergenomicscloud.org/frequently-asked-questions](https://www.cancergenomicscloud.org/frequently-asked-questions)

## Contact and MCI JSON2TSV Source Code

| Property | Value |
| --- | --- |
| id | CONTACT_AND_SOURCE_CODE |

For inquiries related to the JSON2TSV tool, the CCDI, its resources, or how to get involved please send an email to [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov)

Inquiries related to the CGC platform and for requesting pilot credits, please contact [support@velsera.com](mailto:support@velsera.com)

Source code for the CCDI MCI JSON2TSV tool can be found at the following repository: [https://github.com/CBIIT/ChildhoodCancerDataInitiative-MCI_JSON2TSV/](https://github.com/CBIIT/ChildhoodCancerDataInitiative-MCI_JSON2TSV/)
