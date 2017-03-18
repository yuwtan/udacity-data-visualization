# Udacity-data-visualization


## Summary

This data visualization shows the trend that shorter baseball players tend to have higher batting average batting. In this visualization, baseball players are grouped by height (x coordinate) and handedness (color). The number of players in a group is denoted by the bubble size, and the average of batting average within a group is shown by the y coordinate. The trend is clear for all handedness, with very few outliers.


## Design

Firstly, I chose to make a scatterplot because I wanted to show this two-variable elationship. It is easy for readers to figure out what the height and mean batting average are for each point on the chart and tell the trend across different height values. I used colors to encode handedness. Given there are only 3 options, the color encoding would not confuse readers and is easy to distinguish. I also put the legend to the right top corner which is easy to find.

After I got all these feedbacks, I decided to improve my visualization with better layout and animation. I added a title and some comments that help readers to perceive my story. I also changed the simple scatterplot to a bubble plot which could show the population of each group and make readers clear about the trend power as well as the outliers. Finally, I applied animation to the visualization so readers could choose what handedness they want to focus on. The chart is even clearer when readers choose to only check one handedness.

## Feedback

### vishy730:

First of all congrats on getting yourself till here. The visualization looks good. However, I would like to add a couple of points here as the basic criteria for this project is to tell a story via visualization. Having said that, you can start the story with some description or introduction kind of thing something like this.

Does height of a player effect the batting average? Let us see some interesting trends and identify the relationship between the two.

Are there any trends that you could show with the help of a color line or anything else?


### gugu:

I think this is a good visualization. However, I think it is not very convincing by showing simply the averages. For example, the blue point at height 79 looks more like an outlier for me. It would be great if you could show me the confidence intervals, or just show me the count of players for each point, which I think could be easy to implement by changing the size of the point.


### usagi:

From the visualization, I can clearly see that as the height increases, the batting average decreases. I have some questions and suggestions.
1. Since I am not a baseball fan, it would be nice if you could add comments that help me to understand the meaning of variables.
2. I got confused with the dependent variable at first. It seems that you are showing the average of "batting average", not simply "batting average". Is it correct?
3. To better show the trend, I suggest adding lines that connect the dots.
4. The tall players seem to be some outliers. Maybe you can ignore them?


## Resources
1. Scott Murray. (2013). Interactive Data Visualization for the Web. Sebastopol, CA: O'Reilly Media, Inc.
2. https://github.com/PMSI-AlignAlytics/dimple/wiki
3. https://classroom.udacity.com/courses/ud507
4. http://learnjsdata.com/read_data.html
5. https://discussions.udacity.com/t/project-feedback-baseball-data-visualization/229623
6. http://bl.ocks.org/tybyers/736da90eefe0c347a1d6
