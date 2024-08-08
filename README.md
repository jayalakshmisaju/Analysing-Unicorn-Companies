# Analyzing-Unicorn-Companies

### PROJECT OVERVIEW

This project involves analyzing data related to unicorn companies—startups that have reached a valuation of $1 billion or more. The data is processed using MySQL, and the analysis focuses on data cleaning, exploration, and deriving insights about the global unicorn landscape.Additionally, a Tableau dashboard has been created to visualize the findings.

### DATA
[Data](https://www.mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=UNICORN)

| Column Name  | Value               |
|--------------|---------------------|
| Company      | Name of the Unicorn Company |
| Valuation    | Company Worth         |
| Date Joined  | Date of Reaching Billion-Dollar Mark  |
| Industry     | Industry of the company|
| City         | City of the company                     |
| Country      | Country of the company                     |
| Continent    | Continent of the company                     |
| Year Founded | Founding Year                    |
| Funding      | Capital raised                    |
| Select Investors |Investors of the company                |



### DATA CLEANING

- Duplicate Values: Checked for duplicate company entries in the datasets. Bolt and Fabric were identified as duplicates but were preserved as they operate in different locations.

- Column Renaming: Columns were renamed for consistency and clarity. For example, Year Founded was renamed to Year_Founded.

- Date Formatting: Dates were reformatted to standard date types, and new columns (Year_Joined, Month_Joined, Day_Joined) were created to facilitate time-based analysis.

- Unnecessary Data Removal: Removed rows with unknown or zero funding values to ensure data accuracy.

- Formatting Funding and Valuation: Converted funding and valuation figures into numerical formats for better analysis, handling entries marked with 'M' for millions and 'B' for billions.

### DATA EXPOLRATION

- Total Unicorn Companies: The dataset includes 1,601 unicorn companies across 46 countries. The United States leads with the highest number of unicorns, followed by China and India.

- Average Duration to Become a Unicorn: On average, it takes about 7 years for a startup to achieve unicorn status.

- Industries with Most Unicorns: Fintech is the leading industry, followed by Internet software & services, eCommerce, and Artificial Intelligence.

- Top Unicorns by ROI: Companies like Zapier, Dunamu, and Workhuman have the highest returns on investment (ROI), with Zapier leading significantly.

- Leading Investors: Accel is the most prominent investor, backing 46 unicorns, followed by Andreessen Horowitz and Sequoia Capital China.

### DATA VISUALIZATION 

#### TABLEAU DASHBOARD



![Dashboard 1 (1)](https://github.com/user-attachments/assets/b206b3d8-a37e-4b7f-ae77-3f7f5b07431c)

