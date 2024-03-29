Lockitron power management
================

Initial exploratory analysis of aggregate Lockitron activity data. 


The analysis follows through steps:

- Pulling the activity data from the MySQL database.
- Identifying the global time-of-day and day-of-week activity patterns.
- Testing different models and features of the activity data.
- Creating a global dynamic monitoring frequency profile.
- Creating individual profiles that evolve from the global profile with a learning rate.
- Identifying the power savings.

The raw results can viewed with the ipython notebook viewer:

http://nbviewer.ipython.org/github/svacha/power_management/blob/master/power_consumption.ipynb

Slides showing overview of the results can be viewed at:

https://svacha.github.io/lockitron

