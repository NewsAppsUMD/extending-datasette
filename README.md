# extending-datasette

This assignment explores some of Datasette's features, including how it handles address data and 

Follow along, adding code and files as instructed.

### Setup

We'll need to install some things using pip, so run these commands:

* pip install sqlite_utils datasette geocode-sqlite
* datasette install datasette-codespaces
* datasette install datasette-cluster-map


### Geocoding



Then we can view them on a map using the [Datasette Cluster Map plugin](https://datasette.io/plugins/datasette-cluster-map).


### Admissions Data

Using the admissions.csv file in the data folder, load that file into a new sqlite database called umd.db.

Then run datasette serve umd.db so that you can browse the data. Try faceting on different columns. The goal is to find something interesting and then describe in this file what information would be most useful and how you might organize it. In other words, draft a basic proposal for an app that accomplishes one or more tasks for its users, the potential features it would have (including visuals). You don't have to *build* those things, just describe them, and use examples of what a user might do. The more specific the better. If you find a particular view of the data useful, describe that (you should include the URL from your codespace). If there are things you would do with this data that requires additional information or data, tell me about that, too.



### 