# Unicorn-Companies-Data-Analysis
Project For Ironhack 

# Project Description

This project analyzes unicorn companies to understand trends and patterns in their growth and valuation. The main focus is on the time it takes for companies to achieve unicorn status, the impact of technology, and geographical insights.

## Dataset Information

Source: Maven Analytics

Time Frame: Data includes private companies with a valuation over $1 billion as of March 2022.
Size: Over a thousand unicorn companies.

Key Variables:
Company Name: The name of the unicorn company.

Valuation: The current valuation of the company in dollars.
Date Joined: The date the company achieved unicorn status.

Industry: The industry in which the company operates.

City, Country, Continent: Geographic information about the company's location.
Year Founded: The year the company was founded.

Funding: Total funding received by the company.
Select Investors: Key investors in the company.
ROI: Return on Investment, calculated as 
(
Current Valuation
−
Total Funding
)
/
Total Funding
(Current Valuation−Total Funding)/Total Funding.
ROI Rank: Ranking of the company based on ROI.

## Setup and Running the Code
1. Clone this repository:
    ```bash
    git clone [https://github.com/yourusername/unicorn-companies-analysis.git](https://github.com/RaynerMorla21/Unicorn-Companies-Data-Analysis/edit/main/README.md)
    ```
2. Navigate to the project directory:
    ```bash
    cd unicorn-companies-analysis
    ```
3. Install the necessary Python packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook or Python scripts to perform the analysis.

## Analysis Process

Data Cleaning and Preprocessing:

Removed duplicate entries to ensure each company appears only once.

Handled missing values by imputing with median values or dropping rows if critical data was missing.

Converted date fields to datetime format for accurate calculations.

Standardized monetary values by removing symbols and ensuring consistent units (e.g., converting billions and millions).

Feature Engineering:

Calculated the Time to Unicorn as the difference between Year Became Unicorn and Year Founded.

Created a Decade Founded field to group companies by the decade they were founded for trend analysis.
Descriptive Statistics and Trend Analysis:

Calculated mean, median, and range for the time to become a unicorn.
Analyzed trends over different periods, particularly with technological advancements.
Visualization Using Tableau:

Created visualizations to illustrate key findings and insights.

## Summary of Findings

Biggest ROI: Zapier achieved the highest return on investment with a 450% growth.

Longest Time to Become a Unicorn: Otto Book Health Care took 98 years to become a unicorn.

Average Time to Become a Unicorn: On average, it takes about 7 years for companies to reach unicorn status, but in the last decade, this has decreased to approximately 5 years.

Technology and Time Correlation: A significant insight from the scatter plot analysis shows a correlation between time and technology. As technology has advanced, companies have been able to reach unicorn status more quickly.

Geographical Insights: The United States leads the world in unicorn companies, with a total of 562. However, China is home to the highest-valued unicorn, Bytedance.

Industry Insights: There is a strong relationship between technology and unicorn companies, with many tech startups achieving rapid growth and high valuations.

## Viewing the Tableau Report
- View the Tableau report [here][(https://public.tableau.com/app/profile/rayner.morla/viz/Unicorncompaniestableau/Dashboard1#1).


## Presentation
- View the presentation slides [here](https://www.canva.com/design/DAGJPqjCUWc/_vLgcXkDWqUuVyx3_R4BEQ/edit?utm_content=DAGJPqjCUWc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

## Author
- Rayner J Morla
- Raynermorla21@gmail.com

