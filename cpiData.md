---
CPI_Header_URL: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/CPI/CPI_Header.png"
CPI_Img_URL: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/CPI/CPI_Img.png"
CPI_Cross_Dataset_Linkages_Icon_URL: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/CPI/CPI_Cross_Dataset_Linkages_Icon.svg"
CPI_Domain_Coverage_Icon_URL: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/CPI/CPI_Domain_Coverage_Icon.svg"
CPI_Total_Mapped_Participants_Ids_Icon_URL: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/CPI/CPI_Total_Mapped_Participants_Ids_Icon.svg"
CPI_Unique_Participants_Icon_URL: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/CPI/CPI_Unique_Participants_Icon.svg"
---

The Childhood Cancer Data Initiative (CCDI) Participant Index (CPI) maps research participant identifiers across multiple studies and institutions, collectively referred to as “Domains”. By mapping these identifiers, CPI enables researchers to connect data associated with the same participant across different datasets stored in sources such as the CCDI Hub/Childhood Cancer Clinical Data Commons and National Childhood Cancer Registry (NCCR) Data Platform. This mapping capability enhances the discovery of multimodal data, facilitating the exploration of complex research questions, and ultimately supporting the development of innovative therapies for pediatric cancers.

---

# Components

“Identifiers” and “Domains” make up the structure of the CPI. These elements are essential for organizing and mapping participant data across various studies and organizations. The key components include:

- **Identifier**: A public identifier appearing in a research dataset accessible to researchers (e.g., Kids First ID, GENIE ID).
  - **Domain ID Type**: specifies whether the Domain ID corresponds to a participant, PDX, cell line, or organoid.
- **Domain**: Groups of unique participant IDs categorized as follows:
  - **Organizational Identifier**: A project/network of unique participant identifiers (e.g. Children's Oncology Group, AACR GENIE, Pediatric Cancer Data Commons). As part of CCDI’s privacy-preserving data integration approach, certain organizational identifiers are designated as restricted (Children’s Oncology Group (COG) IDs and National Childhood Cancer Registry (NCCR) IDs). These identifiers are used exclusively for data mapping and are not disclosed to users; NCCR data presence is indicated only after a k-anonymity threshold of five is satisfied.
  - **Data Set**: A single dataset for a particular study where data files for the participants can be found (e.g., dbGaP accession numbers).
  - **Study**: Programmatic references to research initiatives (e.g., TARGET, Gabriella Miller Kids First).

Further information on CPI components and functions can be found at [participantindex-docs.ccdi.cancer.gov](https://participantindex-docs.ccdi.cancer.gov).

| Property | Value |
| --- | --- |
| id | CPI_Components |

---

# Core Functions of the CPI

The CPI API functions as a reference service that allows software applications to communicate with each other, providing information on participants’ research IDs to authorized applications. Integration with the CPI is currently under development for applications like the CCDI Hub and Federation Data Resource.

The CPI addresses key questions such as:

- **Which participants and domains are associated with mine?** Authorized applications can input participant ID(s) and retrieve all associated IDs along with their respective domains. This helps in mapping participants across different data sets and studies.
- **What are the current domains in the CPI and their participant statistics?** Authorized users can access comprehensive information about each domain within the CPI database. This includes the domain name, description, category, and a URL linking to additional data, offering context about where a participant’s data is present. Also available are participant statistics for each domain, including the number of participants mapped to various domains, along with the total counts of participants.

| Property | Value |
| --- | --- |
| id | Core_Functions_of_the_CPI |

---

# Request Access

The CPI API will be made available to applications and services authorized by NCI. Interested system owners may initiate a request for access by emailing [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov).

| Property | Value |
| --- | --- |
| id | CPI_Request_Access |

---

# Contribute to the CPI

We invite the community to join us in empowering childhood cancer research. By contributing to the CPI, you can help expand the scope and depth of participant information available to researchers, which could facilitate more comprehensive studies and potentially leading to groundbreaking discoveries. To contribute:

1. **Submit a Contribution Request**: Contact the [CPI Support Team](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov) to express your interest.
2. **Data Preparation**: Once a request is received, the CPI Support Team will provide the CPI Submission Template for participant ID and domain categorization.
3. **Data Submission**: Follow the provided instructions to submit your data to the CPI.

| Property | Value |
| --- | --- |
| id | Contribute_to_the_CPI |

---

# Contact

For more information or to request access to the CPI API, please contact the CPI support team at [NCIChildhoodCancerDataInitiative@mail.nih.gov](mailto:NCIChildhoodCancerDataInitiative@mail.nih.gov).

| Property | Value |
| --- | --- |
| id | CPI_Contact |
