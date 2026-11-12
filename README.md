# GeoPulse: Hyper-Local Retail Mobility Analytics

> **Project:** Internship project assigned by Infotact Solutions\
> **Role:** Data Associate L1 Intern\
> **Domain:** Data Analytics\
> **Project period:** 10 November 2026 -- 10 December 2026\
> **Internship duration:** 3 months

## 1. Project Overview

GeoPulse is a data analytics project focused on understanding local
retail activity and customer movement patterns in a selected area.

The project will involve collecting or sourcing relevant data, cleaning
and organizing it, analyzing it, and presenting useful findings through
visualizations, reports, and an interactive dashboard.

**Note:** The exact study area, dataset, data sources, and final tools
will be confirmed and documented as the project progresses.

## 2. Project Objectives

-   Collect relevant local retail and customer-footfall data.
-   Clean, validate, and organize the collected data.
-   Analyze retail activity and available customer movement indicators.
-   Identify useful trends and patterns, such as busy periods and
    differences between business areas.
-   Create clear charts, reports, and an interactive dashboard.
-   Document the analysis process, findings, and limitations.

## 3. Project Scope

The planned work includes:

1.  Understand the project requirements and select a study area.
2.  Identify suitable and permitted data sources.
3.  Collect data about local businesses and, where feasible, aggregated
    customer footfall.
4.  Store the data in a structured format such as CSV or Excel.
5.  Check data quality and clean the dataset.
6.  Perform exploratory and descriptive data analysis.
7.  Create visualizations and an interactive dashboard.
8.  Summarize findings and prepare the final report and presentation.

## 4. Data Collection Plan

Potential sources include:

-   **Field observation:** Record approximate customer footfall at
    selected locations and time periods, where observation is permitted.
-   **Business survey:** Ask shopkeepers for voluntary, approximate
    business information, such as customer counts by time period.
-   **Customer survey:** Use a short voluntary questionnaire about
    shopping preferences and visit frequency.
-   **Open data:** Use suitable public sources for business locations
    and categories.
-   **Practice datasets:** Use openly available retail datasets if local
    data is limited. Clearly label these as external/sample data.

### Planned data fields

  -----------------------------------------------------------------------
  Field                   Description             Example
  ----------------------- ----------------------- -----------------------
  `area`                  Locality or area name   Pimpri

  `business_name`         Business name, if       Sample Store
                          publicly available or   
                          permission is given     

  `business_type`         Type of business        Grocery

  `observation_date`      Date of observation     2026-11-15

  `time_period`           Time range observed     6 PM--7 PM

  `approx_footfall`       Approximate number of   45
                          visits                  
                          observed/reported       

  `data_source`           Where the record came   Field observation
                          from                    

  `notes`                 Relevant non-personal   Weekend
                          notes                   
  -----------------------------------------------------------------------

Only collect fields that are necessary and can be obtained responsibly.
Do not collect names, phone numbers, precise personal movement
histories, or other identifying customer information.

## 5. Data Privacy and Ethics

-   Ask for permission before conducting surveys or collecting
    information from businesses.
-   Explain the purpose of the survey and make participation voluntary.
-   Record aggregate counts rather than identifying or tracking
    individual people.
-   Do not collect personal location histories or sensitive personal
    information.
-   Use public data in accordance with its terms and attribution
    requirements.
-   Keep collected data secure and report limitations honestly.

## 6. Planned Analysis

The analysis will depend on the data actually collected. Possible
questions include:

-   Which business categories are present in the selected area?
-   Which locations or time periods have higher observed footfall?
-   How does observed footfall vary by day or time?
-   Are there differences in activity between selected localities?
-   What practical observations can be shared with local retailers?

The project will not claim that footfall proves an individual customer's
movement or purchasing behavior.

## 7. Tools and Technologies

The following tools are candidates and will be finalized based on
project needs:

  Tool                              Planned use
  --------------------------------- -----------------------------------
  Microsoft Excel / Google Sheets   Data entry and basic organization
  Python                            Data cleaning and analysis
  Pandas                            Data manipulation
  Matplotlib / Seaborn              Charts and visualizations
  Power BI / Tableau                Interactive dashboard
  SQL (optional)                    Querying structured data

## 8. Project Workflow

1.  Requirement understanding
2.  Study-area selection
3.  Data collection
4.  Data validation and cleaning
5.  Exploratory data analysis
6.  Visualization
7.  Dashboard development
8.  Findings and recommendations
9.  Documentation and final presentation

## 9. Expected Deliverables

As listed in the assignment letter:

-   Source code (if applicable)
-   Project documentation
-   Project report
-   Presentation (PPT)
-   Model evaluation results (if applicable)
-   Final project demonstration (if applicable)

## 10. Timeline

  -----------------------------------------------------------------------
  Period                              Planned activity
  ----------------------------------- -----------------------------------
  10--16 Nov 2026                     Understand requirements, select
                                      study area, plan data collection

  17--23 Nov 2026                     Collect and organize data

  24--30 Nov 2026                     Clean data and perform analysis

  1--6 Dec 2026                       Create visualizations and dashboard

  7--10 Dec 2026                      Complete report, documentation, and
                                      presentation
  -----------------------------------------------------------------------

*This is a proposed working plan for the one-month project window.
Update it according to mentor instructions and actual progress.*

## 11. Suggested Repository Structure

``` text
GeoPulse/
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── reports/
├── dashboard/
└── presentation/
```

Keep private or identifying information out of the repository. Do not
upload confidential data or credentials.

## 12. Project Status

**Status:** Planning

  Task                              Status
  --------------------------------- -------------
  Understand assignment             In progress
  Select study area                 Not started
  Confirm data sources              Not started
  Collect data                      Not started
  Clean and analyze data            Not started
  Build visualizations/dashboard    Not started
  Prepare report and presentation   Not started

Update this section as work is completed.

## 13. Limitations

-   Results will depend on the amount, quality, and coverage of the
    available data.
-   Manual footfall observations are estimates and may not represent
    every customer visit.
-   Survey responses may not represent the entire local population.
-   Findings should be interpreted as observations from the selected
    study area and collection period, not as universal conclusions.

## 14. Acknowledgement

This project is being undertaken as part of the Data Analytics
internship assignment from **Infotact Solutions**.

------------------------------------------------------------------------

**Maintained by:** Sarang Bandu Khandate\
**Last updated:** 12 November 2026
