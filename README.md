# Data Procurement & Storage Challenge

### Task
The goal of this assessment was to make a scraper that could take the contents of the table on [ESPN's RPM statistics](http://www.espn.com/nba/statistics/rpm) and store it in a SQLite database. I completed this using Python's Request library and BeautifulSoup to parse the HTML, Pandas to coalesce the data into a nice table format, and then uploaded it to a local SQLite Database. Here is an image of the database.

![Image of NBA RPM SQLite Database](https://i.ibb.co/h93p9N7/rpm.png)

### Stretch Goals
If I had more time, I would attempt to accomplish the following.
  * Pull other statistics such as PPG, Assists, Blocks, etc that can give give more context to each respective RPM stats.
  * Optimize data storage (Maybe using a dictionary instead of an array for each statistic/category)
