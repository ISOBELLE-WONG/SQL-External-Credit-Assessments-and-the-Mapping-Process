**Project Name: External Credit Assessments and Mapping Process**

**Introduction:**
This project addresses the regulatory requirements set by the Office of the Superintendent of Financial Institutions (OSFI) for big banks to utilize external credit assessments. It involves the mapping of credit ratings from major international agencies to risk weights, ensuring compliance with regulatory standards.

**Objective:**
Derive standardized risk weightings for security issuers based on external credit assessments, following OSFI's guidelines.

**Inputs:**
- Fixed income securities data ("bond_jan_2020.csv")
- Mapping tables from external to internal ratings ("lt_rating_to_ig.csv") and internal ratings to grades ("ig_to_rating.csv").

**Challenges:**
- Handling varying availability of external ratings for each instrument.
- Determining the second highest rating accurately.
- Addressing instruments with no external ratings.

**SQL Code Overview:**
The SQL code involves several steps:
1. Segmentation of unique identifiers.
2. Mapping external credit assessments to internal ratings.
3. Union and processing of ratings data.
4. Calculation and assignment of final ratings.
5. Generation of a comprehensive rating report.

**Outcome:**
The project streamlines the risk weight assignment process, ensuring objective mapping consistent with credit risk levels, benefiting banking clients by enhancing risk assessment accuracy and compliance.

**Note:**
Ensure proper data source referencing and maintain consistency in SQL code execution for accurate results.
