# HR-Movement-Dashboard
A dashboard for HR planning managers

![Dash page 1](https://miro.medium.com/max/2732/1*WYoCD5vOFu6mRjBkXjDYTQ.png)

![Dash page 2](https://miro.medium.com/max/2732/1*3Pz0TmNq_gpGVd2xqxfeIQ.png)

![Dash page 3](https://miro.medium.com/max/2732/1*AReJW67a_fhDHc8PdZne3w.png)

This is a proof of concept I've developed for a course project.

Basic structure:
1. There are three regional excel files, for Americas, APAC and Europe, where respective HR enter details for new hires and exits
2. The regional files contain basic data fields like email, Name, Date of hire, Location, Org(Delivery, DeliveryOps, Support and Corporate), Exit date, type of exit(voluntary,involuntary), employment type, etc.
3. The R code reads the regional files, consolidates them into a "global" dataset and manipulates them to create a dashboard
4. The dashboard has three tabs: the main dash, new hires and attrition


Tools/concepts used:
1. I wanted to learn the flexdashboard library which is a simpler, easy to learn version of shiny. Flexdashboard uses R markdown to create an html output
2. I've used plotly for all the plots. It's built similar to ggplot2 ,it uses the grammar of graphics, but is a dynamic version. So you can use the labels as filters for the plots

