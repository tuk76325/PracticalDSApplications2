# PracticalDSApplications2
This repository contains modules that have been completed to practice data handling with real world applications.

# DENSITY OF TRAFFIC COLLISION FATALITIES OVER A ROAD MAP OF NYC
This problem builds on your knowledge of working with relational data (SQL/Pandas) and working with numpy arrays. The final step will be to use some reference map data to render the density of traffic collision fatalities over a road map of NYC.

# DATA MINING TO FIND POTENTIAL "COMMUNITIES"
This problem builds on knowledge of Numpy, pandas, database organization, graph abstractions, and basic Python (for interfacing with other Python libraries). Goodreads is a website devoted to curating user-generated book reviews. We'll do some data-mining to uncover "communities" of users who like the same books. Such insights might help users find like-minded communities and generate better book recommendations.

Overall workflow. This notebook has six (6) parts.

    Part A: Analyze user-book interactions [SQL, pandas]
    Part B: Power-law analysis [pandas, Numpy]
    Part C: Edge lists, NetworkX, and graph clusters [Python, graphs]
    Part D: Finding communities via graph clustering [SQL, pandas]
    Part E: Identifying "top reads" by community [pandas]
    Part F: Merging inventory metadata [pandas]

# CAMPAIGN FINANACE GEOGRAPHY
This problem builds on knowledge of Pandas, SQLite, and Sparse Matrices. The Federal Election Commission tracks each individual campaign contribution over $200. Among the information collected is the name and address of the person making the contribution and the committee receiving the contribution. Note that all contributions are actually made to committees. Some committees are directly connected to individual candidates, but others are more "general purpose". There are specific rules governing what each type of committee is allowed to actually spend their money on (this is well beyond the scope of this notebook).

Our goal is to use the contributors' ZIP codes and candidate committees to calculate some similarity scores. Specifically, we want to measure how similar geographic areas are based on the candidates to whom they made contributions and measure how similar candidates are based on the geographic areas that contributed to their campaigns.

We are using data pulled from the official FEC website. The individual contributions files are huge, so some of the initial (and time consuming) processing has already been taken care of.

# CAPTURING DATA CHANGES FOR SLOWLY CHANGING DIMENSIONS
This problem builds on your knowledge of working with tabular data.

Scenario:
  You have just been hired by the hot new startup Spot-i-flix-ify (this is a fictional company which will offer video and audio streaming services) as a Data Scientist. This is a small startup so you have to "wear many different hats," so to speak. Your first task on the job is to set up their data warehousing so that they can capture a historical record of their operations for analysis later. The operational database (which someone else has already set up) only contains the current state of the operation to maintain maximum efficiency while performing tasks like adding new customers, changing services, applying promotions, etc. It will not contain any history and is not intended have complex queries run against it. While this is a fictional company and simulation data, there is a real-world use case for the processes developed in this notebook.

# PUNT, KICK, OR GO FOR IT? AMERICAN FOOTBALL ANALYSIS
The framework of a 4th down play makes the offense's decision on what to do on the fourth down an interesting question. We will provide data-driven guidance on which option (punting, kicking a field goal attempt, or running a play) will give the offense the best chance of winning the game. We have sourced play level data from ESPN for over 2000 games from the 2000-2022 NFL seasons and loaded it into a Pandas DataFrame. 

# ACTOR NETWORK ANALYSIS
This problem builds on knowledge of Pandas, base Python data structures, and using new tools (some exercises require use of features from the networkx package, which is well documented). 

Our goal is to create a graph analysis where the nodes are actors collected from given data, and the edge is the relationship between them. Graph analysis is performed on this data using the networkx package.
