# Meta_Analysis_Feedback_Timing
A Meta-analysis of the Impact of Feedback Timing on Learning Outcomes

## Data Sources

### Database Search Results
- **Folder**: `database_search_results`
- **Description**: Contains the initial results of database searches as detailed in the Search_protocol sheet within the `MA_Feedback_DecisionSpreadsheet_Relevant_studies.xlsx`.

### Other Sources
- **File**: `other_sources_results.zip`
- **Description**: Includes the results from additional sources, supplementing the primary database search results.

### Decision Spreadsheets
- **Files**:
  - `MA_Feedback_DecisionSpreadsheet_Relevant_studies.csv`
  - `MA_Feedback_DecisionSpreadsheet_Relevant_studies.xlsx`
- **Description**: These files contain coded decisions from screening and full-text review stages, serving as input for various analytical processes.

### Main Data
- **File**: `MA_Feedback_Data.csv`
- **Description**: This CSV file contains the core data for effect size calculations and subsequent meta-analytic evaluations.

### Codebook for Data Extraction
- **File**: `MA_Feedback_Data_Extraction_CodeBook.csv`
- **Description**: Provides a detailed codebook for the data extraction process, defining variables and coding schemes used in the data collection phase.

## Code Scripts

### Jupyter Notebook for Screening Analysis
- **File**: `0-inclusion_exclusion_stages_and_PRISMA.ipynb`
- **Description**: Analyzes screening and full-text review decisions, outputs PRISMA flow diagrams and descriptive statistics of the included studies.

### R Markdown for Effect Size Calculation
- **File**: `1-effect_size_calculation.Rmd`
- **Description**: Calculates the effect sizes required for the meta-analysis using data from `MA_Feedback_Data.csv`.

### R Markdown for Meta-Analysis
- **File**: `2-meta_analysis.Rmd`
- **Description**: Conducts the main meta-analysis and moderator analyses, using the effect sizes calculated in `1-effect_size_calculation.Rmd`.

## Instructions
- **Files**:
  - `Fulltext_Reviewer_Instructions.pdf`
  - `Title+Abstract_Screener_Instructions.pdf`
- **Description**: These documents provide detailed instructions for reviewers at the title/abstract screening and full-text review stages.

## Output Files

### PRISMA Flow Diagram and Statistics
- **File**: `output_0-inclusion_exclusion_stages_and_PRISMA.pdf`
- **Description**: Contains the PRISMA flow diagram and descriptive statistics derived from the initial screening and review processes.
