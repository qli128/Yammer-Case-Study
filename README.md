# Yammer-Case-Study
1. Investigating a Drop in User Engagement
2. Understanding Search Functionality
3. Validating A/B Test Results



### Description
These are the case studies provided by MODE.com SQL Tutorial. I did major queries in SQL to select analytical information (through `pandasql` API), but I also conducted some data manipulation and visualization in Python (mainly on `pandas`, `matplotlib` libraries).

The first one is about investiagting drop of engagement from July to August, 2014. I conducted several analysis, including time, email types, major events, users activity and region. Later I drew conclusions on what I've found and made recommendations for further analysis.

The second one is to analyze whether there exists problems on 'search' function within Yammer. I looked into users search behaviors, click through and search results, and conclude that the recommended search results should be re-ordering based on users preferences.

The third one is to conduct A/B test on deciding whether to launch new features by spliting users into control and experiment group and observing the change of relavant metrics. After evaluting several metrics that might reflect users reaction using hypothesis test of two samples, I would suggest to launch this new feature.



### Major Libraries
- pandas: to manage .csv files and dataframes more conviniently
- pandasql: run SQL query under pandas dataframe, it will return table as dataframe so it's easy to draw plots on top of that
- matplotlib: data visualization



### More...
- I referenced sample ideas from Mode.com and columnist from medium.com
- It is definetly more convinient, easier and faster to manipulate data directly in pandas, not sqlite...but a very good practice of JOIN, GROUP BY and WINDOW FUNCTIONs in SQL
