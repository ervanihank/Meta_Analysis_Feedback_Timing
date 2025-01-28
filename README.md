# Meta_Analysis_Feedback_Timing
A Meta-analysis of the Impact of Feedback Timing on Learning Outcomes

## Data Sources

### Database Search Results
- **Folder**: `database_search_results`
- **Description**: Contains the results of the database searches as outlined in the Search_protocol sheet within the `MA_Feedback_DecisionSpreadsheet_Relevant_studies.xlsx`. This folder includes the initial data files used for the meta-analysis.

### Decision Spreadsheet
- **File**: `MA_Feedback_DecisionSpreadsheet_Relevant_studies.xlsx`
- **Description**: This Excel file includes a 'Search_protocol' sheet which details the search criteria and results. It serves as the primary file for reviewing search strategies and initial findings.

### Screening and Review Decisions
- **File**: `MA_Feedback_DecisionSpreadsheet_Relevant_studies.csv`
- **Description**: Contains coded decisions from the screening and full-text review stages. This CSV file is used as input for the Jupyter Notebook script to analyze the screening results and detailed decisions made during the review process.

## Code Scripts

### Jupyter Notebook Analysis
- **File**: `0-inclusion_exclusion_stages_and_PRISMA.ipynb`
- **Description**: This Jupyter Notebook processes the information from the `MA_Feedback_DecisionSpreadsheet_Relevant_studies.csv` file. It outputs detailed descriptive statistics about the title and abstract screening, full-text review decision stages, the PRISMA flow diagram information, and statistics on the included studies.

## Output Files

### PRISMA Flow Diagram and Statistics
- **File**: `output_0-inclusion_exclusion_stages_and_PRISMA.pdf`
- **Description**: A compiled PDF document that presents the PRISMA flow diagram and descriptive statistics derived from the Jupyter Notebook analysis. This file encapsulates the results of the meta-analysis process stages.
