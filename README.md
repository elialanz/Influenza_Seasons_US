**Tableau Visualization Project Link ↓** https://public.tableau.com/app/profile/elia.lanzuise/viz/MappingInfluenzaDeathsInUSA/InfluenzaDeathsInUS

## Influenza Seasons US Project

The Influenza Data Profiling & Visualization project involved analyzing real public health data from the Centers for Disease Control and Prevention (CDC) to evaluate influenza mortality, vaccination coverage, and demographic patterns across U.S. states. Using Microsoft Excel as the main analytical environment and Tableau for visualization, I developed a complete data profiling and cleaning workflow that transformed raw government health data into a structured, insight ready dataset suitable for statistical and visual analysis.

### Influenza Data Analysis & Insights

In this project, I worked with the CDC’s Influenza Deaths dataset and complementary U.S. Census population data to understand the reliability, structure, and consistency of large scale public health information. The outcome was a set of cleaned, validated datasets and a Tableau storyboard showing how influenza mortality varied across time and geography.

The project began with a rigorous data profiling phase in Excel, where I transferred the raw influenza dataset into a structured task template.

**I documented every variable:**
- Data type (text, numeric, date/time)
- Measurement level (nominal, ordinal, discrete, continuous)
- Time property (time-variant or time-invariant)
- Structure (structured vs. unstructured fields)

This formed the foundation of the Data Profile of Raw Data sheet, establishing a transparent overview of how the information was organized before analysis.

**Next, I performed a detailed data integrity assessment.**

Using Excel functions such as MIN, MAX, and AVERAGE, I calculated descriptive statistics for all quantitative variables to evaluate data accuracy spotting unrealistic outliers and verifying that averages aligned with expected epidemiological ranges. I then built frequency tables for categorical fields (state, year, gender, and cause) to evaluate data consistency and identify issues such as spelling variations, inconsistent date formats, and non standard state names.

After documenting every integrity issue, I moved to the Cleaned Data tab, where I corrected all formatting, naming, and structural inconsistencies.

**In this stage, this is what I did:**
- Standardized state and region names
- Reformatted dates for time-series compatibility
- Removed redundant text fields
- Applied uniform numeric precision
- Added missing category labels where appropriate
- Used VLOOKUP formula to merge parts of data together

In the Data Profile of Cleaned Data sheet, I listed all transformations made to improve data quality, and recalculated the summary statistics to confirm that values now aligned with expected ranges.
A new Data Integrity of Cleaned Data tab was then created to validate that cleaning improved accuracy and internal consistency, ensuring each variable’s minimum, maximum, and mean reflected realistic values and that no invalid categories remained.

This same process was repeated for the secondary dataset from the U.S. Census, which provided population context for normalization and rate calculations.
Both datasets were then merged conceptually for comparative analysis of mortality rates relative to population size.

After completing the full Excel based profiling and cleaning, I imported the final dataset into Tableau to communicate the findings visually.

**This project demonstrates my ability to:**

- Build complete data profiling documentation for large health datasets.
- Identify and correct data integrity issues using Excel (accuracy, consistency, completeness).
- Apply descriptive statistics and frequency analysis for quality assurance.
- Clean and standardize structured data for analytical use.
- Combine Excel based data preparation with Tableau storytelling to communicate insights clearly to decision makers.
