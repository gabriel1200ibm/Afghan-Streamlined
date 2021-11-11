# Afghan-Streamlined
## Content

- [Why Afghanistan?](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#why-afghanistan)
- [Before starting](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#before-starting)
- [Overview](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#overview)
- [Querying the Data](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#querying-the-data)
- [Translating the Tweets](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#translating-the-tweets)
- [Cleaning & Selecting the Data](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#cleaning--selecting-the-data)
- [Calculating Sentiment](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#calculating-sentiment)
- [Merging Column & Sentiment Data](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#merging-column-data-and-sentiment-data)
- [Visualizing the Data](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#visualizing-the-data)
- [What we learned](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#what-we-learned)
- [Appendix](https://github.com/gabriel1200/Afghanistan/blob/master/README.md#what-we-learned)

## Why Afghanistan?
- Large sample, able to retrieve over 400k tweets within (x) kilometers of the country. 
- Continuous change with clear inflection points. The country was taken over throughout the month(allowing us to compare sentiment by day) and had multiple incidents that generated high traffic (allowing us to compare sentiment surrounding key events)
- Allowed us to showcase Watson’s translation functionality & identify sentiment in non English languages.

**Software Used**

All scripting was done in **Python**, using **Jupyter Notebook** for live development and **Pandas** for data manipulation. The project was hosted on the **CP4D** platform, with all dashboards created via **Cognos** on that platform.

**What you'll need **
 - A jupyter notebook setup on your local computer.
 -  Access to a CP4D cluster
 -  _Twitter API Developer Key to pull the query_* (For the purposes of the cookbook, we'll link the csv file with our query results instead)