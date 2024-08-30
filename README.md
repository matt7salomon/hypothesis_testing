# hypothesis_testing

Problem 2 Data Quality / Data Analysis

The Safety and Insurance Team is interested in understanding reported accident rate, namely total reported accidents per million miles. We have provided a mock dataset ‘mock_accident_data.csv’ of miles and reported accidents by month, city, product (e.g. UberX, UberEATS), and segment (e.g. segmentation for drivers, riders, or trips).

Please include any code / formulas (R, Python, SQL, etc.) you wrote for the analysis in your response and delete the dataset when you have finished with the challenge.

Using the attached dataset, please do the following:
Perform any cleaning, exploratory analysis, to identify any unusual or bad data. What adjustments would you make to the dataset before analyzing further?
Propose charts, dashboards, or metrics to monitor to help the team better understand trends in the reported accident rate. 
Based on your work in B above, provide a forecast for overall reported accident rate for Jan 2017.
Build a model (e.g., generalized linear model) to analyze the reported accident rate per mile as a function of the features in the data (i.e., Month, Segment, City, and Product). Please consider the following in your analysis:
What type of distribution to choose?
How to select important features?  
How to check that your model assumptions are supported by data?
Summarize the steps you take to build the model and report the results. Explain the findings from the model. 
Conduct the following hypothesis tests and report your results:
The accident rate per mile of Segment G is different from that of Segment A. 
The accident rate per mile of Segment G is different from that of Segment B.
The accident rate per mile of Segment G is 40% lower than that of Segment A.


Problem 3 Spatial Analysis

All subsequent questions concern this dataset. Please download this file and confirm that you have received 3,060,528 rows of data. Please support your answer with cogent R, Python or other languages.

Compute the following metrics for the 'widgets' column in the dataset.
the mean
the median
the absolute difference between the 75th and 25th percentile 

In reviewing the 'widgets' field of the dataset, describe the rows you would exclude as unusual/errors/outliers and your rationale. How did the exclusion affect the mean and median of the field. 

The dataset shows the number of widgets which exist at each latitude, longitude on Earth. Answer the following:
Which US State(s) have the fewest total widgets?
Which US State has the 4th highest total widgets? This answer should not depend on whether or not you are excluding outliers, so long as you have done so reasonably.
Please give a table of total widgets by state. Bonus points if you attach a link to a choropleth.


