# Sales-Conversion-Analysis

The analysis involves exploring a dataset related to sales conversion and performing various visualizations to gain insights.

Here's a breakdown of the code and its analysis:

The code begins by importing necessary libraries such as numpy, pandas, matplotlib, and seaborn for data manipulation, visualization, and analysis.

The dataset is loaded using the pandas library's read_csv function. The dataset is assumed to be in a file named "KAG_conversion_data.csv" in the same directory.

Some initial exploratory steps are taken. The first five records of the dataset are displayed using the head() function to get a glimpse of the data.

The info() function is used to obtain information about the dataset, including the column names and the presence of any missing values.

The describe() function is called to generate descriptive statistics of the dataset, such as count, mean, standard deviation, minimum, maximum, and percentiles.

A correlation matrix is created using the seaborn library's heatmap function. It focuses on the correlation between specific columns (Impressions, Clicks, Spent, Total_Conversion, Approved_Conversion, interest). The resulting heatmap provides insights into the relationships between these variables.

The code replaces specific values in the "xyz_campaign_id" column with corresponding labels ("C_1", "C_2", "C_3") using the replace function.

A count plot (bar chart) is created to visualize the distribution of the "xyz_campaign_id" column using the seaborn library's countplot function.

Another bar plot is generated to compare the amount of money spent on each campaign ("xyz_campaign_id") using the seaborn library's barplot function.

A bar plot is created to show the relationship between the "xyz_campaign_id" and the "Approved_Conversion" columns. This plot indicates which campaign resulted in the highest number of approved conversions.

A count plot (bar chart) is created to determine the majority age group using the seaborn library's countplot function.

A bar plot is generated to show the relationship between "xyz_campaign_id," "Approved_Conversion," and "age" using the seaborn library's barplot function. This plot helps identify which age group (specified by "age") had the highest number of approved conversions for each campaign.

Another bar plot is created to show the relationship between "age," "Clicks," and "gender" using the seaborn library's barplot function. This plot focuses on the number of clicks by different age groups and genders.

A count plot (bar chart) is created to determine the gender count using the seaborn library's countplot function.

A count plot (bar chart) is created to visualize the distribution of "interest" using the seaborn library's countplot function.

A scatter plot is generated to explore the relationship between "interest" and "Approved_Conversion" using the matplotlib library's scatter function. This plot helps identify the impact of different interest levels on the number of approved conversions.

Two facet grid plots (scatter plots) are created to visualize the relationships between "interest," "Approved_Conversion," "age," and "gender." These plots provide insights into how age and gender influence the relationship between interest and approved conversions.

Finally, a summary of the key findings is presented based on the analysis conducted. The summary includes recommendations and observations derived from the data and visualizations.

