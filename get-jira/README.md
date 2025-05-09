# Get jira

This function takes a jira api token as input and returns a dataframe representing edges between tickets in JIRA.

One row is one edge relation between tickets, a row is uniquely defined by the source ticket id and target ticket id.

Top parent is project. 

