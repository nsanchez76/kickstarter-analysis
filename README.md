# Kickstarter Campaign Analysis

## Overview of Project
An analysis was performed on a set of data containing information about thousands of Kickstarter campaigns. It was determined that theater campaigns launched in the month of May June were the most successful. It was also noted that plays with a smaller goal were more successful than those with larger goals.

### Purpose
The purpose of this analysis was to provide the client with an analysis of how different Kickstarter campaigns focusing on theater and plays performed by examining their launch dates and their goals.

# Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Microsoft Excel was used in the analysis of Kickstarter campaign outcomes based on their launch dates. This began with the extraction of the "Years" data of the "Date Created Conversion" column into its own column. A Pivot Table was then created in a new tab named "Theater Outcomes by Launch Date". The "Parent Category" and "Years" fields were added to the Filters section. The "outcomes" field was added to the Columns section. The "Date Created Conversion" field was added to the Rows section. The "outcomes" field was also added to the Values section. The "count of outcomes" in the Values section was chosen as the appropriate measure. The "Years2" and "Quarters" fields that were automatically added to the Rows section by MS-Excel were deleted. The "Column Labels" were sorted in descending order. "Theater" was chosen from the "Parent Category" filter.

A Pivot Chart was created based on the Pivot Table. It shows that Kickstarter campaigns related to theater had more successful campaigns than failed campaigns. There were also more failed campaigns than canceled ones. The chart also showed that Kickstarter theater campaigns launched in the month of May were the most successful. The resulting Pivot Chart is shown here:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106849689/173723043-fc14550b-275f-4ae4-b3ba-b2f7ebe94eb4.png)

### Analysis of Outcomes Based on Goals
Microsoft Excel was used in the analysis of the outcomes of Kickstarter campaigns for plays based on their goals. First, a new tab was created named "Outcomes Based on Goals". Column headers were added: "Goal", "Number Successful", "Number Failed", "Number Canceled", "Total Project", "Percentage Successful", "Percentage Failed", "Percentage Canceled". Ranges were created under the "Goal" header. The "COUNTIFS()" function was used to examine the full data set in the "Kickstarter" tab. It was customized to return the number of successful plays within the specified ranges in the "Number Successful" column. It was also used to return the number of failed and canceled campaigns in their respective columns. The "SUM()" function was then used to sum up the total number of campaigns in each goal range. The percentage successful, failed, and canceled were calculated and the respective columns were formatted as percentages.

A chart was created using the defined "Goal" ranges, the "Percentage Successful", the "Percentage Failed" and the "Percentage Canceled" data. The chart shows that there were more successful campaigns with lower goals than failed campaigns with lower goals. This order flips as the goal amount increases. There were also no canceled campaigns. The resulting chart is shown here:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106849689/173723187-0a08e0cb-eeae-4375-8170-33c5ae294a0f.png)

### Challenges and Difficulties Encountered
The challenges with the "Theater Outcomes by Launch Date" analysis were that there was a large amount of data to be analyzed. This data had many different types, as well as many different formats. The extraction of the "Years" information from the "Date Created Conversion" column helped in filtering the data. The "Parent Category" was also helpful in focusing the analysis on a specific type of Kickstarter campaign.

The challenges with the "Outcomes Based on Goals" had similar challenges. The use of the "COUNTIFS()" function was helpful in sifting through the data and reporting only what was needed for the analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Conclusion 1: There were more successful campaigns than failed or canceled.
  - Conclusion 2: Campaigns launched in the month of May were the most successful.

- What can you conclude about the Outcomes based on Goals?
  - Conclusion: There were more successful campaigns with smaller goals than there were that failed with smaller goals. This is the inverse with larger goals.

- What are some limitations of this dataset?
  - Some limitations of the dataset is that there are too many different categories of campaigns. There are also too many different data types.

- What are some other possible tables and/or graphs that we could create?
  - It would be possible to create a table and chart for comparing the success of similar campaigns in different countries. Also to created a table and chart for comparing the goal amounts vs. outcomes in different countries.
