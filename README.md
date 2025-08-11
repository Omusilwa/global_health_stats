## Automated Analysis and Visualization of Global Hospital Data

**Overview**

This project analyzes a comprehensive global health dataset to determine disease prevalence, identify epidemiological trends, and present findings through automation and interactive visualization. The dataset spans multiple countries and years, covering various diseases, treatments, and healthcare outcomes.

The analysis supports health policy planning, epidemiological research, and predictive modeling, enabling data-driven decisions that can improve healthcare delivery and resource allocation.

---

**Dataset Description**
The dataset contains detailed metrics on:
- Disease Indicators – Prevalence, incidence, mortality, and recovery rates.
- Healthcare Infrastructure – Healthcare access %, doctors per 1,000 people, hospital beds per 1,000 people.
- Treatment Information – Primary treatment type, average treatment cost, availability of vaccines/treatments.
- Socio-Economic Factors – Per capita income, education index, urbanization rate.
- Outcome Measures – Disability-Adjusted Life Years (DALYs) and five-year improvement rates.

Geographic & Temporal Coverage: Data from multiple countries and years, enabling both cross-sectional and longitudinal analysis.

---

**Use Cases**
1. Healthcare Policy Analysis – Identify high-burden diseases and allocate resources effectively.
2. Epidemiological Studies – Examine disease-socioeconomic correlations (e.g., income, education, urbanization).
3. Predictive Modeling – Forecast disease prevalence, mortality rates, and treatment outcomes.
4. Global Health Research – Support targeted interventions and public health campaigns.

---

**Data Cleaning Priorities**
A robust cleaning pipeline ensures reliability and consistency in the analysis:

1. Understand the Data Structure
    - Identify variables: disease type, demographics, time period, location, outcomes.
    - Develop metadata to define column meanings.

2. Handle Missing Data
    - Quantify missing values per column.
    - Drop, fill, or flag values based on significance.
    - Special attention to critical epidemiology fields (date, disease name).

3. Standardize Data Formats
    - Dates in `YYYY` format.
    - Normalize categorical values (e.g., unify “Malaria”, “malaria”, “MALARIA”).
    - Standardize Column Values.
----

**Methodology**
- Data Ingestion – Load dataset from CSV into Pandas DataFrame.
- Data Profiling – Summary statistics, distribution checks, missing value analysis.
- Data Cleaning – Apply transformations as outlined in Data Cleaning Priorities.

