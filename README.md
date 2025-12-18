
# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# UK MONETARY POLICY 2019-2025

This project explores the United Kingdom's monetary policy environment over the period 2019–2025, using key macroeconomic indicators to analyse movements in the policy interest rate.The analysis focuses on three primary variables:

Interest Rate (Bank Rate)

Inflation (Consumer Price Index, CPI)

Economic Activity (Gross Domestic Product, GDP)
The emphasis is on data preparation, time-series alignment, exploratory analysis, and visualisation of trends and relationships over time.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
*This project uses publicly available UK macroeconomic time-series data covering the period 2019–2025.
The dataset is constructed by merging multiple official sources and focuses on three key variables central to monetary policy analysis:
1. Policy Interest Rate; The Bank of England official rate, sourced from BoE
2. Consumer Price Index (CPI); measure of inflation, sourced from ONS 
3. Gross Domestic Product (GDP); a measure of economic output, sourced from ONS 


## Business Requirements
The specific business requirements are:
i.  Data Integration and Consistency:
Collect, clean, and merge official UK macroeconomic data from multiple sources.
ii.Ensure all variables (policy interest rate, CPI, GDP) are aligned to a common quarterly time index for comparability

* Monitoring Key Economic Indicators:
i. Track trends in the Bank of England’s policy interest rate.
ii.Analyze inflation dynamics through  the Consumer 
Price Index (CPI).
iii. Monitor the GDP

iv.Trend or time-series analysis to explore relationship between interest rates, inflation, and GDP.
* Store the dataset in a format that is easy to use and update


## Hypothesis and how to validate?
1. Interest Rate and Inflation Relationship:

Hypothesis: Changes in the Bank of England’s policy interest rate have a measurable impact on the Consumer Price Index (CPI), with higher interest rates reducing inflationary pressures.

2. Interest Rate and Economic Growth:
Hypothesis: Adjustments in the policy interest rate influence GDP growth, with higher rates potentially slowing economic activity.

3. Inflation and Economic Output Dynamics:
Hypothesis: There exists a trade-off between inflation and GDP growth, consistent with standard macroeconomic theory

Validation Approach:
* Time-Series Analysis: Examine historical quarterly trends and correlations between interest rates, CPI, and GDP
* Visualization: Employ charts and plots to detect  patterns, and potential causal relationships between variables.

## Project Plan
* High-Level Steps:

i.Data Collection: Gathered publicly available UK macroeconomic time-series data (policy interest rate, CPI, GDP) from official sources.

ii.Data Processing: Cleaned, aggregated, and aligned all variables to a common quarterly time index to ensure consistency.

iii. We would conduct  descriptive statistics and visualizations to understand trends, seasonality, and correlations among variables.
iv. Interpretation and validation 

* How was the data managed throughout the collection, processing, analysis and interpretation steps?
Collection: Integrated multiple official sources, ensuring all data points were accurate and up-to-date.

Processing: The processing :

Involves removing irrelevant columns and duplicate records

Handling missing values and ensuring consistent data types

Renaming columns for clarity and consistency

Converting dates into a uniform quarterly format

Aggregating data where necessary to ensure all variables aligned temporally

Storage: The data was stored locally. Raw data saved in teh Raw folder while the final_df.csv saved in the cleaned folder
Version control (Git) was used to track the chamges to code and data processing steps.

Analysis:The final dataset (final_df.csv) was loaded into the Data_Visualisation notebook for analysis and visualisation

Interpretation: The result were interpreted in an ecominc context explaining how changes in inlation and interest rates corresponded with movement in GDP. 


* Why did you choose the research methodologies you used?
Data visualization is used to explore trends, patterns, and relationships between the UK policy interest rate, inflation (CPI), and GDP over time. Visual analysis allows us to interpret temporal dynamics clearly and communicate insights about monetary policy. 


## The rationale to map the business requirements to the Data Visualisations

Visualizations allow us to monitor key indicators (interest rate, CPI, GDP), explore relationships between them, and communicate trends clearly.




## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.88  
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* The project uses only publicly available UK macroeconomic data, so there are no privacy concerns.

L
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 



## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
