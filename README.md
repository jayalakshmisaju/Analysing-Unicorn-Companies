# Analyzing-Unicorn-Companies

### PROJECT OVERVIEW

This project involves analyzing data related to unicorn companies—startups that have reached a valuation of $1 billion or more. The data is processed using MySQL, and the analysis focuses on data cleaning, exploration, and deriving insights about the global unicorn landscape.Additionally, a Tableau dashboard has been created to visualize the findings.

### DATA CLEANING

-Duplicate Values: Checked for duplicate company entries in the datasets. Bolt and Fabric were identified as duplicates but were preserved as they operate in different locations.

-Column Renaming: Columns were renamed for consistency and clarity. For example, Year Founded was renamed to Year_Founded.

-Date Formatting: Dates were reformatted to standard date types, and new columns (Year_Joined, Month_Joined, Day_Joined) were created to facilitate time-based analysis.

-Unnecessary Data Removal: Removed rows with unknown or zero funding values to ensure data accuracy.

-Formatting Funding and Valuation: Converted funding and valuation figures into numerical formats for better analysis, handling entries marked with 'M' for millions and 'B' for billions.
