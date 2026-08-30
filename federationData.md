---
title: CCDI Data Federation Resource
Federation_Header: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/Federation/Federation_Header.png"
CCDI_Federation_Data_Access: "https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/Federation/CCDI_Federation_Data_Access_02052026.png"
navTitles:
  - Data Access
  - Additional Available Resources
  - Agent Skill to support streamlined discovery and analysis
  - Blog
  - Contribute to CCDI Data Federation Resource
  - Contact
---

Data federation enables users to pull data from across various resources as if they were accessing a single virtual database, rather than consolidating all data into a single centralized repository. The data remain at the original source but become searchable and findable to the research community through a standard application programming interface (API). This allows the creation of a virtual cohort and facilitates large-scale analytic research by making deidentified participant-level data (non-PHI/PII) findable across the sources.

The Childhood Cancer Data Initiative (CCDI) is piloting data federation with Kids First Data Resource Center, the Pediatric Cancer Data Commons, St. Jude Cloud, and the Treehouse Childhood Cancer Initiative. These resources provide information about genomic, clinical, imaging, and biospecimen data in these data sets.

The CCDI Data Federation Resource has since expanded to include CCDI data as well as data from CCDI ecDNA and the Pediatric Solid Tumor Program-IUSCCC, all of which can be queried through the CCDI Data Federation API. This list will continue to grow as more organizations harmonize their data with CCDI standards and implement the CCDI’s data federation API.

## Data Access

Researchers can search for deidentified individual-level data through the API, which provides metadata that aids in the creation of virtual cohorts across multiple data types from participating resources by accessing CCDI’s Data Federation Resource API.

To access the CCDI Data Federation Resource API, please click [here](https://cbiit.github.io/ccdi-federation-api-aggregation/).

To access participating nodes API, please click [here](https://cbiit.github.io/ccdi-federation-api-spec).

The API does not deliver files. Rather, it provides an open-access subset of the metadata (e.g., demographics) that match a user’s search criteria and provides the location of the complete data set. The data are accessible according to the policies at each contributing resource.

## Additional Available Resources

The CCDI Data Federation Resource offers a suite of resources including the [OpenAPI Specification](https://cbiit.github.io/ccdi-federation-api-aggregation/swagger-aggr.yml), [Data Model Navigator](https://ccdi.cancer.gov/data-federation-data-model), [Data Federation Resource Wiki](https://github.com/CBIIT/ccdi-federation-api-spec/wiki), and [GitHub Repository](https://github.com/CBIIT/ccdi-federation-api)
to support participating node development. You may also get assistance or report an [issue](https://github.com/CBIIT/ccdi-federation-api-spec/issues/new/choose). Read more about CCDI Federation API in the [blog](https://cbiit.github.io/ccdi-federation-api/blog/09-25-2024-introducing-the-federation-api.html).


### Agent Skill to support streamlined discovery and analysis 
The CCDI Data Federation now includes a new Agent Skill designed to help users plan, validate, explain, and execute metadata-only queries using the CCDI Federation Resource API. The CCDI Data Federation Agent Skill bridges the gap between research intent and API precision.  The Agent Skill serves as a metadata-aware copilot for the CCDI Federation API. Its purpose is not to retrieve raw research data, but to assist users in planning, validating, explaining, and optionally executing metadata-only API queries.

```responsive-img
wide: 'https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/Federation/CCDI_Federation_Resource_AI_Skill_08242026.png'
alt: 'test'
Caption: ""
```
![Infographic of the CCDI Federation Resource AI Skill, showing a five-step, metadata-only workflow: ask, map, verify, fetch, and summarize, with guardrails for read-only API access and no clinical interpretation](https://raw.githubusercontent.com/CBIIT/CCDI_Hub_Assets/main/Image/Resources/Federation/CCDI_Federation_Resource_AI_Skill_08242026.png)

A dedicated git repository (https://github.com/CBIIT/ccdi-federation-ai) is available with instructions and further information about the CCDI Data Federation Agent Skill.  


### Blog 
Read more about the CCDI Federation Agent Skill and API in the [blog](https://cbiit.github.io/ccdi-federation-api/blog/09-25-2024-introducing-the-federation-api.html) to monitor growth and technical revisions as they are implemented.

## Contribute to CCDI Data Federation Resource

We invite the community to join us in empowering research through CCDI data federation. Organizations that implement CCDI’s data federation API harmonize data according to CCDI standards to ensure data are searchable.

If interested in becoming a member of the CCDI Data Federation Resource, please send an email to [ncichildhoodcancerdatainitiative@mail.nih.gov](mailto:ncichildhoodcancerdatainitiative@mail.nih.gov).

## Contact

[Email us](mailto:ncichildhoodcancerdatainitiative@mail.nih.gov) with questions related to CCDI federated data or accessing the CCDI Data Ecosystem.
