# Travel Trends Maven National Rail Insights for Rail Managers
## Created & Analyzed by Saddam Ansari @Aspiring Data Analyst [Linkedin](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)

### Live Dashboard at Novypro [Live_link_Novypro](https://project.novypro.com/0kedOi)

#

## About Maven National Rail
undefinedMaven National Rail is a prominent company dedicated to providing comprehensive business services to passenger train operators across England, Scotland, and Wales.

With a commitment to enhancing the efficiency and performance of rail transport, Maven National Rail collaborates with various operators to deliver top-notch solutions that cater to the evolving needs of the railway industry.


#



## Project Objective
For the Maven Rail Challenge, I took on the role of a Business Intelligence (BI) Developer for National Rail.

My manager tasked me with creating an exploratory dashboard with the following objectives:

 * 1. **Identify the Most Popular Routes:** Analyze booking data to determine which train routes are the most frequented by passengers.

 * 2. **Determine Peak Travel Times:** Assess travel patterns to pinpoint the busiest travel times, allowing for better resource allocation and scheduling.

 * 3. **Analyze Revenue from Different Ticket Types & Classes:** Evaluate revenue streams from various ticket categories and classes to understand financial performance and customer preferences.

 * 4. **Diagnose On-time Performance and Contributing Factors:** Investigate punctuality issues and identify factors that impact train schedules to improve overall service reliability.

Before proceeding further, I would like to provide an overview of the dataset used in this project

#


## About the Dataset
![Screenshot 2024-06-07 093208](https://github.com/user-saddam123/Travel-Trends-Maven-National-Rail-Insights-for-Rail-Managers/assets/123800896/6b985e8f-050f-47f3-a077-59d7baed934c)

For this dashboard, I have been provided with a dataset related to ticket bookings for Maven National Rail from December 8, 2023, to April 30, 2024. The dataset contains 31,563 rows of data, capturing essential details about each ticket purchase.

## Data Preparation and Cleaning
When I first loaded the dataset into Power BI, I used the Power Query Editor to meticulously ensure the quality and consistency of each column. Here's a summary of the key data preparation and cleaning steps I undertook:

**1. Ensuring Data Quality:** I began by checking the data quality for each column, making sure there were no discrepancies or inconsistencies in the data types and values.

**2. Standardizing Delay Reasons:** I standardized various entries in the "Reason for Delay" column for consistency:

 * Replaced "Staffing" and "Staff Shortage" with "Staff Shortage."
 * Consolidated "Weather Conditions" and "Weather" into "Weather."
 * Unified "Signal failure" and "Signal Failure" into "Signal Failure."

**3. Creating a Travel Route Column:** I introduced a new column called "Travel Route," which merges the "Departure Station" and "Arrival Station" columns. This was done using the merge function in Power Query Editor, allowing for better analysis of specific travel routes.

**4. Additional Minor Adjustments:** I made other minor changes and adjustments to the dataset to enhance its overall quality and consistency.

Through these steps, I ensured that the dataset was clean, consistent, and ready for insightful analysis and visualization in the dashboard.

## Dashboard Overview
Based on the project objectives and stakeholder requests, I have created a single-page Power BI report dashboard with dimensions of 3300 pixels in height and 2400 pixels in width.

My main goal in designing this dashboard was to keep it simple and intuitive, ensuring that stakeholders could easily understand the insights and make strategic decisions for the future based on the data presented.

*Key Features of the Dashboard: Bookmarks for Easy Navigation:

The dashboard includes five bookmarks to facilitate user navigation and enhance the user experience:

◾ About Dataset: Provides detailed information about the dataset used for the analysis.

◾ Project Objective : Summarizes the primary objectives of the project.

◾ Key Notes: Highlights important points and insights derived from the data.

◾ User Guide: Offers a guide on how to use the dashboard effectively.

◾ Filters :Allows users to apply filters and customize the data view according to their needs.

By clicking on these bookmarks, users can quickly access relevant sections and select values as per their requirements, making the dashboard interactive and user-friendly.

Lets Jump to Dashboard:
#


## Important KPI's:
