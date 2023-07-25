# reddit-data-project
Protifolio project that consists in getting reddit data through an API and store it on a SQL Server to further read it and run sentiment analysis.

This is a Python project for my portifolio, the goal is to connect to reddit API using PWAR to get posts from r/ politics and store them.
On my SQL Server I have a post table, with an unique ID and a dimension table with the sentiment analysis' columns plus other post informations from que reddit API.
The sentiment analysis was made using NLTK.
In the future I'll create a Power BI dashboard to display the data.
