# SQL Final Project: Pandemic Data Analysis

## Tasks and Results

### Task 1: Data Loading
**Description:** Create pandemic schema and import infectious_cases data from CSV file using MySQL Import wizard.

**Screenshot of the result**

![p1_data_loading](results/p1_create_use_pandemic.png)

### Task 2: Database Normalization
**Description:** Normalize the infectious_cases table to 3NF by splitting it into entities and infectious_cases_normalized tables. Verify that the normalization preserved all data records.

**Screenshot of the result**
![p2_3NF](results/p2_3NF.png)

![p2_normalization_verification](results/p2a_normalization_verification_counts.png)

**Result:** 245 | 245 | 10521 | 10521 - All counts match, normalization successful.

### Task 3: Data Analysis
**Description:** For each unique combination of Entity and Code (or their IDs), calculate the average, minimum, maximum, and sum for the Number_rabies attribute. Filter out empty values ('') from Number_rabies. Sort results by average in descending order and display only top 10 rows.

**Screenshot of the result**

![p3_data_analysis](results/p3_rabies_statistics.png)

### Task 4: Date Calculations
**Description:** Create date difference columns using SQL functions to analyze time spans in the data.

**Screenshot of the result**

![p4_date_calculations](results/p4_date_calculations.png)

### Task 5: Custom Function
**Description:** Build a function to calculate year differences or disease rates.

**Screenshot of the result**

![p5_custom_function](results/p5_custom_function.png)

## Folder Structure
- `results/` - Contains screenshots and output files for each step
- `sql_queries.txt` - Documentation of all SQL commands executed

## Database
- MySQL database
- Schema: pandemic
- Main tables: infectious_cases, entities, infectious_cases_normalized
