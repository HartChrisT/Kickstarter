# Kickstarting with Excel

## Overview of Project

### Purpose
To perform a deep analysis into kickstarter data to uncover trends.

## Analysis and Challenges

### Analysis of Theater Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92996865/146660548-8638179a-d638-46fc-a27e-f8ff127ffb90.png)


### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92996865/146660557-ece8b0f4-87e4-448a-9345-45a83e5a4f8b.png)

### Challenges and Difficulties Encountered
One challenge was figuring out how to only select the sorted data from the kickstarter table when performing an analysis on it and not the hidden data. The countifs() function helped with that a lot, although it was a bit confusing and took me a long time to figure out. Before doing the project, I encountered a similar problem when calculating statistics, but instead of using the countifs() function, I used the aggregate() function. For the countifs() function, I ended up having to put two seperate statements in for the range, ie countifs(rangeX:X,>=Y,rangeX:X<=Z)

In the Outcomes based on Goals part, I had trouble figuring out how to get the row labels in order, if I should use a pivot table, and how to change the names of the legend from "x" calculation of Percentage to just percentage. I was able to get the row labels in order by setting the sort option to manual, I used a pivot table because I had trouble trying to do it without one, and I had to add a space after changing the name of the column in the pivot table to avoid an excel error. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Theater Outcomes tend to have a higher rate of success in the spring and summer months, when compared with fall and winter. The most successful month being May and then a linear decline thereafter. Therefore, setting a launch date close to the month of May is crucial.

The rate of failed outcomes by month throughout the year remain relatively constant when compared to successful outcomes. Based on this observation, one may conclude that people have a higher interest in theater during mid spring to mid summer.

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
