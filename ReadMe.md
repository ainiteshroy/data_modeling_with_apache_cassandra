## PURPOSE
This project sets up a NoSQL database for Sparkify's app's usage session data. This data is stored as csv logs on a daily basis. Apache Cassandra is used as the non-relational database. Non-Relational DBMS is chosen for fast writes, and the tables are denormalised for fast data retrieval. Fast writes and data retrievals are going to be important for user experience.
Given three queries, three tables have been created, optimized for each of them. It is tried that partition column is chosen on the basis of arguments of WHERE clause.

## HOW TO RUN
1. Ensure csv logs are stored in event_data, and Apache Cassandra is installed on the local machine.
2. Run the Jupyter notebook file. Add new cells to run queries.