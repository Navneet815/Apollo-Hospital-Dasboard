# Apollo Healthcare Analytics Dashboard with Power BI

## Overview
This project uses Power BI to analyze healthcare datasets, providing insights into patient demographics, treatment outcomes, cost implications, and overall hospital performance. The resulting dashboard aims to uncover trends, identify areas for improvement, and support data-driven decision-making in the healthcare industry.

## Project Goals
- Analyze patient demographics, diagnoses, and treatment outcomes.
- Identify the cost implications of various medical treatments and procedures.
- Evaluate hospital performance metrics and trends.
- Create an interactive Power BI dashboard to visualize key insights and metrics.

## Datasets Used
The project uses two key datasets:
- **Patient Medical Records**: Contains patient information such as age, gender, blood type, diagnosis, treatments, admission and discharge dates, and total bills.
- **Hospital Treatment Details**: Provides detailed insights on hospital treatments, including treating doctor, room number, daily costs, treatment types, and recovery ratings.

## Methodology
The analysis and dashboard creation followed a systematic approach:
1. **Data Importing & Initial Examination**: Datasets were imported into Power BI and examined for missing values, inconsistencies, or irrelevant data.
2. **Merging & Relating Datasets**: The datasets were merged using the common "PatientID" column to consolidate the data into a single dataset.
3. **Data Cleaning**: The data was cleaned by addressing missing values, removing duplicates, and correcting any errors.
4. **Data Type Conversion**: Dates such as Admission and Discharge were converted to the appropriate date format. Length of Stay was calculated for analysis.
5. **Categorization**: Patients were categorized into age groups (e.g., Child, Adult, Senior) based on their age to make the analysis more insightful.
6. **DAX Calculations**: Key calculations were made using DAX to derive insights:
   - **Total Treatment Cost**: Computed the total cost of treatment for each patient.
   - **Average Recovery Rating**: Analyzed recovery ratings by treatment type.
   - **Patient Load Per Room**: Examined the average number of patients per room.
   - **Doctor’s Patient Load**: Analyzed the number of patients attended by each doctor.
   - **Correlation Analysis**: Explored the correlation between length of stay and treatment cost.
   - **Predictive Models**: Built models to predict recovery ratings and future hospital capacity.
7. **Dashboard Design**: A comprehensive, interactive Power BI dashboard was created, including:
   - **Patient Demographics**: Breakdown by age, gender, and blood type.
   - **Treatment Costs**: Total treatment costs by hospital and treatment type.
   - **Recovery Ratings**: Average recovery rating across different treatment types.
   - **Hospital Performance**: Key performance indicators like patient load, treatment costs, and recovery rates.

## Key Insights
- **Common Diagnoses**: Flu, COVID-19, Hypertension, Diabetes.
- **Treatment Types**: Medication, Therapy, Surgery.
- **Treatment Costs**: Total treatment costs range from $2,500 to $15,000.
- **Patient Demographics**: A significant portion of the patient population falls within the Infant and Adult age groups. Patients are distributed across various blood types, with AB+ being the most prevalent.
- **Hospital Performance**: A comparison of treatment costs and recovery ratings across different hospitals.

### Apollo Healthcare Overview Insights
- **Total Treatment Costs**: $11.04 million
- **Patient Demographics**:
  - Total Patients: 1,000
  - Average Age: 50.5 years
  - Patients by Gender: Male: 329, Female: 337, Other: 334
  - Patients by Age Group: Infant (46.2%), Adult (36.7%), Senior (11.2%)
  - Patients by Blood Type: AB+ (135), A+ (131), O- (117), etc.
- **Treatment Costs**: The average treatment cost per hospital ranges from $958.43 to $1,037.80.
- **Treatment Cost by Type**: Medication: $3.9M, Therapy: $3.8M, Surgery: (details not yet provided).

## Technologies Used
- **Power BI**: For data analysis, visualization, and dashboard creation.
- **DAX**: For calculations and data analysis.
- **Excel**: For initial data cleaning and preparation.
- **SQL**: For data queries and merging datasets (if applicable).

## Future Work and Improvements
- **Advanced Predictive Modeling**: Enhance prediction accuracy for patient recovery and treatment outcomes.
- **Trend Analysis**: Further analyze trends in hospital admissions, patient outcomes, and treatment costs.
- **Integration of Patient Feedback**: Include patient satisfaction surveys to improve treatment insights.
- **Healthcare Policy Implications**: Analyze the impact of hospital policies on treatment outcomes and costs.
