Utts & Heckard CH02
========================================================
author: Created by: Jill E. Thomley
date: Updated: 2018-02-05 15:54:43
autosize: true



Datasets
========================================================

* A **variable** is some characteristic of interest that can differ from one individual to the next.

* An **observational unit** (or **observation**) is a single individual, object, or entity about which we have collected data for one or more variables.

* An observation may be called a case, subject, or participant.

A **dataset** is a collection of information for all observations and variables in a study (e.g., survey or experiment). A common way to arrange data is to put variables in columns and observations in rows. This is what we see in **StatCrunch**. 



Loading Datasets in StatCrunch
========================================================

To access one of the datasets in Dr. Thomley's class data group...

* MyStatCrunch > My Groups > STT1810-Thomley

Click on "## data sets" to see the full list. You can search by name using the box under "Browse all" on the left side of the screen or scroll the alphabetical list. Click on the name to open the dataset. There are also groups for additional textbook datasets.

* Utts & Heckard 5th Edition Datasets
* Brase & Brase Selected Datasets

Use Explore > Groups to search for and join the groups. Use the search terms "Thomley", "Utts", and "Brase". 



Populations vs. Samples
========================================================

A sample is a subset chosen from a larger population of interest. In any given scenario, the population is defined by the research question(s) being investigated. 

* A summary measure for a **population** is called a **parameter**.

* A summary measure for a **sample** is called a **statistic**.

Sample statistics are used to estimate population parameters.

If we collect data from a whole population, it is called a **census**.



Types of Variables
========================================================

* categorical / qualitative
   + nominal
   + ordinal
   
* numerical / quantitative / measurement
   + interval
   + ratio

* explanatory / independent / predictor

* response / dependent / predicted



Data vs. Information
========================================================

Statistical methods help us transform raw data into information that provides knowledge and helps us make decisions.

* We use **descriptive statistics** to summarize datasets or make comparisons between datasets, but we do not go beyond the data we actually have. 

* In **inferential statistics**, sample data are used to generalize or make predictions about the larger population from which the sample was selected.

We will often talk about the **distribution** of a particular variable, which describes how often the possible responses occur.



Categorical Summaries
========================================================

* A **frequency table** summarizes frequencies and/or relative frequencies of different categories for a categorical variable.

* A **pie chart** can be used to visually summarize a categorical variable. They work best with a small number of categories.

* A **bar chart** can be used to visually summarize one or more categorical variables and are useful for making comparisons.

Frequency tables and bar charts can also be used for numerical data or to display/compare descriptive statistics. We will focus on using them for summarizing categorical data.



In StatCrunch
========================================================

* Stat > Tables > Frequency

* Graph > Pie Chart > With Data (if using a raw dataset)

* Graph > Bar Plot > With Data (if using a raw dataset)

   + Where &mdash; selects a subset of the data
   + Group By &mdash; divides data into groups
   + Other &mdash; puts small categories together
   + Options to format table or plot appearance
   + Options to put more than one plot on a page



More on StatCrunch Bar Plots
========================================================

TBA



Numerical Distributions
======================================================

The **distribution** of a numerical variable is the overall pattern of how often all the possible values occur. Informally, we can think of it as how the values "stack up" on the number line.

Important features of a numerical distribution...

* shape (symmetric, skewed, number of modes)
* center (the location or **average** of data values)
* spread (dispersion or **variability** among data values)
* outliers (unusually large or small data values)



Plots for Numerical Data
======================================================

There are many types of displays for numeric data and data visualization is a growing area of data science and statistics. Here we will focus on four types...

* dotplot
* stem-and-leaf plot
* histogram
* boxplot

Each of these plots has different strengths and weakesses.



Summaries for Numerical Data
======================================================

* five-number summary
   + minimum, Q<sub>1</sub>, median, Q<sub>3</sub>, maximum

* center
   + mean and median
   
* spread
   + range and interquartile range
   + variance and standard deviation

* percentiles



Median vs. Mean
======================================================

* A variable's **median** is the value that cuts the data set in half
   + 50% of the values are above the median, 50% are below
   + for an odd number of cases, the median is a data value
   + for an even number of cases, average two middle values

* A variable's **mean** is what we usually refer to as its "average"
   + sum of all values divided by total number of observations
   + represents the balance point of the variable's distribution

Both represent a distribution's "center"&mdash;just in different ways.



In StatCrunch
========================================================

* Stat > Summary Stats > Columns (for descriptive statistics)
* Graph > Dotplot
* Graph > Stem and Leaf
* Graph > Histogram
* Graph > Boxplot

   + Where &mdash; selects a subset of the data
   + Group By &mdash; divides data into groups
   + Other &mdash; puts small categories together
   + Options to format table or plot appearance
   + Options to put more than one plot on a page
   


Boxlots
======================================================

* Draw a box that spans Q<sub>1</sub> to Q<sub>3</sub>&mdash;the middle half of the data
* Show the median by drawing a line at the correct value inside the box&mdash;this cuts the middle half in half, 25% on each side
* Calculate fences to help identify outliers
   + Lower Fence = Q<sub>1</sub> - 1.5 &times; IQR
   + Upper Fence = Q<sub>3</sub> + 1.5 &times; IQR
* Indicate data points outside the fences using dots or circles&mdash;these points are considered **outliers**
* Draw whiskers to the largest and smallest non-outlier points



Causes of Outliers 
======================================================

* The value represents legitimate natural variability in the data. Discarding the value would misrepresent the distribution, so retain it and summarize appropriately. 

* A mistake was made in measuring, recording, or entering the data. Values should be corrected and kept when possible, or discarded if they cannot be be fixed.

* The value is not a mistake in measuring or recording, but the individual comes from a different group than the population of interest. In this case, the value should be discarded unless it is relevant to the research question.



Standard Deviation
======================================================

TBA



Bell-Shaped Curves
======================================================

TBA



Standardized Scores
======================================================

TBA



Good Datasets for Practice
======================================================

* Anthropometric
* Electoral Votes
* Normal Samples
* MLB-Salaries-2002
* MLB-Salaries-2013
* Oscar Ages
* Personality Type STT1810
* Personality Type STT3850
* WCS Weather Days
