### Problem Statement

This Marketing Performance Dashboard is designed to give an overview of campaign performance metrics across different channels. The dashboard focuses on the following key marketing KPIs:
1. Total Ad Spend - Shows the total amount of money spent on advertisements.
2. Total Website Visits - Displays the total number of website visits received from all campaigns.
3. Average Conversion Rate - Highlights the average conversion rate across different channels.
4. Average CTR (Click-Through Rate) - Measures how often people click on your ad after seeing it.

The dashboard further visualizes:
- Count of Customers by Age Group (Bar Chart)
- Sum of Website Visits by Campaign Channel (Donut Chart)
- Average of Conversion Rate by Campaign Channel (Line Chart)
- Time Spent on Site vs. Average Conversion Rate (Scatter Plot)

A slicer for filtering by campaign type (Awareness, Consideration, Conversion, Retention) is included to allow dynamic segmentation of the data.

---

### Steps Followed

#### Step 1: Creating Card Visuals for Key Metrics
- Visuals Created: 4 Card Visuals
    1. Total Ad Spend: Displays the total amount spent on ads.
    2. Total Website Visits: Summarizes the total website visits across all campaigns.
    3. Average Conversion Rate: Calculates the average rate of website visitors who converted (e.g., purchased).
    4. Average CTR: Shows the average click-through rate, i.e., the percentage of people who clicked on the ad.

- Process:
    - Drag a Card Visual from the Visualizations pane.
    - Select the respective metric (e.g., Total Ad Spend, Total Website Visits, Average Conversion Rate, Average CTR) from the dataset.
    - Adjust format settings to display the values in an understandable format (e.g., for currency or percentage values).

#### Step 2: Count of Customers by Age Group (Bar Chart)
- Visual Created: Bar Chart showing the count of customers by age group.
  
- Process:
    - Insert a Clustered Bar Chart from the Visualizations pane.
    - Add the Customer ID to the Values field.
    - Add the Age Group column to the Axis field.
    - Adjust the chart's formatting to show a clear breakdown of customer counts across different age groups.

#### Step 3: Sum of Website Visits by Campaign Channel (Donut Chart)
- Visual Created: Donut Chart showing the sum of website visits by campaign channel.
  
- Process:
    - Insert a Donut Chart.
    - Drag the Website Visits field to the Values section.
    - Add Campaign Channel to the Legend section to break down the visits by each channel.
    - Format the donut chart for clarity and adjust the display of values inside the chart.

#### Step 4: Average of Conversion Rate by Campaign Channel (Line Chart)
- Visual Created: Line Chart showing the average conversion rate for each campaign channel.
  
- Process:
    - Insert a Line Chart.
    - Add Conversion Rate to the Values field, setting the aggregation to Average.
    - Add Campaign Channel to the Axis field.
    - Format the line chart to display the average conversion rate for each campaign channel.

#### Step 5: Time Spent on Site vs Average Conversion Rate (Scatter Plot)
- Visual Created: Scatter Plot comparing the time spent on site with the average conversion rate by channel.
  
- Process:
    - Insert a Scatter Plot visual.
    - Drag Time Spent on Site to the X-Axis field.
    - Drag Conversion Rate to the Y-Axis field, ensuring it is set to the Average aggregation.
    - Add Campaign Channel to the Legend to differentiate between channels.
    - Format the plot to display the comparison between time spent on site and conversion rates clearly.

#### Step 6: Adding Campaign Type Slicer
- Slicer Created: A slicer for Campaign Type.
  
- Process:
    - Insert a Slicer from the Visualizations pane.
    - Add the Campaign Type field to the slicer to allow filtering of the dashboard by Awareness, Consideration, Conversion, and Retention.
    - Place the slicer at the top of the dashboard for easy access.
  
---

### Insights Derived from the Dashboard
- Age Group Insights: The bar chart shows how different age groups respond to the campaigns, helping the marketing team identify which age segments have the highest customer counts.
- Campaign Channel Performance: The donut chart highlights which channels (e.g., PPC, SEO, Social Media) generate the most website visits, allowing the team to prioritize high-performing channels.
- Conversion Rate Trends: The line chart provides insights into how different campaign channels are converting, which can help allocate marketing spend more effectively.
- Time Spent vs. Conversion: The scatter plot provides an understanding of how the time users spend on the site correlates with conversion rates across different channels.

