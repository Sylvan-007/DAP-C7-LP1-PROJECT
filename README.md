# LP1 PROJECT_INDIAN STARTUP VENTURE 

##  CRISP-DM (Cross-Industry Standard Process for Data Mining) Methodology Application 

The CRISP-DM framework is a widely adopted methodology for data mining projects, providing a structured approach to planning and executing data analysis tasks. It comprises six major phases, each with its own set of tasks and deliverables, ensuring a comprehensive and iterative process.

The six(6) phases are;
 1. Business Understanding which focuses on understanding the objectives and requirements of the project.

 2. Data understanding  which drives the focus to identify, collect, and analyze the data sets that can help you accomplish the project goals.

 3. Data preparation which prepares the final datasets for modeling.

 4. Modeling to build and assess various models based on several differnt modeling techniques.

 5. Evaluation - To evaluate results and review process and determine the next steps.

 6. Deployment - To deploy the results can be as simple as generating a report or any requirement given.


# 1. Business Understanding

## Project Title

Indian Startup Ecosystem: "Insights for Prospective Investors"


## Objective

Your team aims to venture into the Indian start-up ecosystem. As the data expert, you need to investigate the ecosystem and propose the best course of action.

## Goal

Analyze funding patterns in the Indian startup ecosystem from 2018 to 2021 to determine sectoral investment trends, funding stage distributions, geographical hotspots, and top investors.

# 2. Data Understanding

Data Source: The datasets consists of separate CSV files for each year (2018-2021) detailing startup funding in India. 

The columns include:

1. Company/Brand: Name of the company/start-up
2. Founded: Year start-up was founded
3. Sector: Sector of service
4. What it does: Description of the company
5. Founders: Founders of the company
6. Investor: Investors
7. Amount($): Raised fund
8. Stage: Round of funding reached


# 3. Data Preparation
Tasks;

    1. Data Cleaning: Handle missing values, inconsistencies, and errors in the dataset.

    2. Data Integration: Combine yearly data into a single dataset for comprehensive analysis.

    3. Data Transformation: Normalize and standardize data, especially for funding amounts.

    4. Feature Engineering: Create new features if necessary, such as total funding by sector or funding amount by city.


# 4. Modeling
 
 ## Hypotheses:

    Null Hypothesis (H0): Funding amounts are evenly distributed across all sectors in the Indian startup ecosystem from 2018 to 2021, and technology-driven startups do not receive higher average funding compared to other sectors.

    Alternative Hypothesis (H1): Funding amounts are not evenly distributed across all sectors in the Indian startup ecosystem from 2018 to 2021, and technology-driven startups receive higher average funding compared to other sectors.

## Approach:

    1. Statistical Analysis: Conduct statistical tests to evaluate the distribution of funding amounts across sectors.

    2. Trend Analysis: Perform trend analysis to observe funding variations over the years.

    3. Correlation Analysis: Examine the relationship between funding stages and amounts.

    4. Geographical Analysis: Identify major funding locations and analyze geographical trends.


# 5. Evaluation

## Key Questions:

    1. Which sectors (Top 5) are receiving the most investment in the Indian startup ecosystem?
      We shall investigate which sectors stand out in terms of average funding received to identify potential investment hotspots.

    2. How do funding amounts vary across different startup sectors, yearly?
       We will analyze year-over-year trends to determine if funding increased, decreased, or remained stable, providing insight into overall investment climate changes.


    3. At what stage do businesses raise the most money across sectors?
       We shall examine funding distribution across different stages (e.g., seed, early, growth) to understand where investors are most likely to commit significant capital.

    4. Which are the top 10 locations that received funding?
       We will analyze funding distribution across various cities to determine if certain locations are emerging as major startup hubs.

    5. Are there specific cities that have become hubs for certain industries or types of startups?
        We will identify which cities(headquarters) are becoming specialized hubs for particular sectors or types of startups.

    6. Who are the top 3 investors in the top 5 sectors?
       We will identify key investors and their sector preferences to gauge influential players and sector-specific investment trends.

## Evaluation Metrics:

    1. Descriptive Statistics: Summary statistics for funding amounts across sectors, stages, and years.
    2. Visualization: Charts and graphs to illustrate key trends and patterns.
    3. Hypothesis Testing: Results of statistical tests to confirm or reject the hypotheses.


# 6. Deployment

## Sharing Insights:
    1. Publish Link to Github repository.

    2. Share the analysis on platforms like Medium, LinkedIn, Dev.to, or a personal blog.

    3. Use Power BI to deploy visualizations to make the insights accessible and understandable for a broad audience.

## Actionable Recommendations:

    1. Identify high-potential sectors for investment.

    2. Highlight key funding stages for strategic investments.

    3. Recommend geographical locations for establishing a presence based on funding trends.

    4. Suggest potential investors to engage with, based on their investment patterns.

## ARTICLE ON INVESTMENT ANALYSIS OF THE INDIAN START UP ECOSYSTEM

## Introduction

India’s startup ecosystem has witnessed tremendous growth over the past decade, driven by innovation across various sectors and significant funding from both domestic and international investors. This article explores a data science project analyzing the Indian startup-funding ecosystem, revealing trends, patterns, and insights that highlight the dynamics of this vibrant landscape. Such information is vital for stakeholders looking to make data-driven decisions in entering this business ecosystem.

## Project Overview

### Understanding the Data

When assigned this project, our team needed a deep understanding of the data. We extracted datasets from multiple sources, anticipating challenges in cleaning and merging them. Initially, we planned to merge and clean the dataset to perform Exploratory Data Analysis (EDA).

### Methodology: CRISP-DM Approach

We followed the CRISP-DM (Cross-Industry Standard Process for Data Mining) approach, a structured methodology for planning and executing data mining/science projects to ensure systematic, reliable, and actionable results. The steps include:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Evaluation
5. Deployment

## Business Understanding

The first step was crucial as it set the project’s direction. Our team outlined several insights we aimed to uncover from our datasets, forming our business objectives:

- Understand the ecosystem of start-ups in India.
- Identify the best course of action to venture into the ecosystem.
- Identify the best start-ups, sectors, and cities to invest in.

We formulated hypotheses to test these objectives:

- **Null Hypothesis (H0)**: Funding amounts are evenly distributed across all sectors in the Indian startup ecosystem from 2018 to 2021, and technology-driven startups do not receive higher average funding compared to other sectors.
- **Alternative Hypothesis (H1)**: Funding amounts are not evenly distributed across all sectors in the Indian startup ecosystem from 2018 to 2021, and technology-driven startups receive higher average funding compared to other sectors.

We defined key business questions to answer by the end of the project:

1. Which sectors (Top 5) are receiving the most investment in the Indian startup ecosystem?
2. How do funding amounts vary across different startup sectors yearly?
3. At what stage do businesses raise the most money across sectors?
4. Which are the top 10 locations that received funding?
5. Are there specific cities that have become hubs for certain industries or types of startups?
6. Who are the top 3 investors in the top 5 sectors?

## Data Understanding

We began by extracting datasets from various sources:

- 2018 data: Sourced from a GitHub repository.
- 2019 data: Downloaded manually from a OneDrive account.
- 2020/2021 data: Queried from a SQL server database.

A data dictionary was created to clarify data definitions, ensuring consistency and aiding in data preparation.

## Data Preparation

Data preparation involved transforming raw data into a clean, usable format for analysis. We imported requisite libraries into our Python notebook and followed these steps:

1. Data Collection: Gathered from SQL database, OneDrive, and GitHub repository.
2. Data Cleaning:
    - Handled missing values via imputation, deletion, or algorithms that manage missing data.
    - Removed duplicate records to ensure data integrity.
    - Corrected errors like typos, inconsistencies, and inaccuracies.
    - Merged datasets for 2018–2021 into a single dataframe.

### Visualization Before Cleaning

Initial visualizations showed columns like ‘Amount’ and ‘Sector’ had few null values, while columns like ‘Founded’ and ‘Investor’ had significant null values. Further cleaning involved resolving null and duplicate values, mapping and replacing stage column names, and converting the “amount” column from rupees to dollars.

### Data Validation

We ensured the prepared data was correct, complete, and suitable for analysis through rigorous checks and validations.

### Visualization After Cleaning

Effective data preparation was essential for the success of our project, directly impacting the quality of insights and recommendations.

## Power BI Deployment

The final stage of the CRISP-DM method involved deploying our insights using Power BI. We created a comprehensive dashboard to visualize key aspects of the Indian startup ecosystem.

### Deployment Process

1. Planning and Preparation: Visualized funding distribution across locations, sectors, and stages.
2. Licensing**: Used Power BI Pro for sharing and collaboration.
3. Setting Up Power BI Environment: Created an account and workspace for managing reports and dashboards.
4. Data Preparation and Modeling:
    - Imported data from Excel files and databases.
    - Used Power Query for data transformation.
    - Established relationships between data tables.
5. Building Reports and Dashboards:
    - Designed interactive and visually appealing reports.
    - Combined reports into a single dashboard.
6. Publishing and Sharing:
    - Published reports to the Power BI service.
    - Shared the dashboard with stakeholders.
7. Deployment and Maintenance:
    - Set data refresh schedules to keep the dashboard updated.
    - Monitored usage and performance for optimal functionality.

### Insights and Conclusions

The dashboard provided several key insights:

- **Top Locations Based on Funding Amount: Mumbai leads with 230bn in funding, followed by Bangalore (23bn) and Gurugram (7bn).
- Total Funding Per Sector: Financial Services received the highest funding, followed by Retail, Undisclosed, IT & Technology, and Education.
- Average Funding by Stage: Special Funding Types have the highest average funding, followed by Other Funding Types and Late-Stage funding.
- Distinct Locations and Sectors: The ecosystem spans 61 locations and 17 sectors, showcasing its diversity.
- Top Investors in the Top 5 Sectors: Leading investors include Alpha Wave Ventures, Facebook, Google, Fidelity, and SoftBank.

### Key Business Questions Addressed

1. Top 5 Sectors Receiving Most Investment: Financial Services, Retail, IT & Technology, and Education.
2. Funding Variation by Year: More funds were distributed in 2021, with Financial Services receiving the most funding.
3. Stage of Highest Funding: Special funding types are prominent at certain growth stages due to varying risk profiles, capital requirements, and strategic alignments.
4. Top 10 Funded Locations: Maharashtra, followed by other key cities.
5. Industry Hubs: Bengaluru for IT & Technology, Mumbai for Financial Services and Media, Delhi for Business Services and IT, Gurgaon for Business Services, Hyderabad for IT & Technology and Healthcare.
6. Top Investors: Specific investors lead in sectors like Education, Financial Services, IT & Technology, and Retail.

## Conclusion

Our project provided a comprehensive analysis of funding trends within the Indian startup ecosystem, offering actionable insights that drive innovation, growth, and investment. These insights inform strategic decision-making and support the continued evolution and success of the Indian startup landscape. By analyzing and visualizing complex data, we contribute to the dialogue surrounding entrepreneurship, innovation, and investment in India.

## Appreciation

I highly recommend Azubi Africa for their comprehensive and effective programs. Read more about Azubi Africa [here](https://azubiafrica.org) and learn about their life-changing programs.

Tags: Azubi Data Science