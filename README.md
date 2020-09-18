# Project 1: Exploring Attributable Factors of Covid-19 Deaths


Using data provided by the Center for Disease Control and Prevention, our group explored two datasets to investigate how age, pre-existing conditions, and geographic location correlates with  Covid-19 deaths. Both of the datasets we used include data starting from February 2020 to the date we downloaded the data. The following is a list of questions we were most interested in pursuing:


Do pre-existing conditions increase the risk of death caused by Covid-19? If so, which pre-existing conditions have resulted in the highest mortality in reported Covid-19 related deaths?

People with pre-existing conditions have been deemed as one of the most vulnerable populations of contracting Covid-19 and experiencing more severe symptoms. Using data from data.cdc.gov, we created a bar graph to visualize the number of Covid-19 deaths grouped by each provided condition group. Through our visualization, we found that the majority of people who succumbed to Covid-19 also had either malignant neoplasms or a variety of other conditions or ailments. Next, we delved deeper into each condition group and plotted the number of Covid-19 deaths versus each condition. Here, we found that along with Covid19 infection, influenza and pneumonia, hypertensive diseases, and all other conditions were most associated with Covid-19 related fatalities.

Does age correlate with the number of reported Covid-19 deaths?

While we have seen how Covid-19 has affected people of all ages, most coverage on Covid-19 related deaths has largely focused on people over the age of 65. Thus, we wanted to visualize the number of Covid-19 deaths versus age. In our first plot, we created a scatter plot of the sum of deaths versus age group. Next, we applied a regression line to our data to find the correlation between age and Covid-19 deaths. Here, we found that age highly correlates with Covid-19 deaths where an increase in age increases the likelihood of death from Covid-19. In our second graph, we created a boxplot of the maximum deaths per age group. First, we grouped all deaths by state to find the maximum death count by state. Since only the maximum count was used, we found that the maximum death count is largely comprised of people who are 65 and older. Again, we saw as the age group increased, so did the number of Covid-19 deaths. 




What is the spatial distribution of Covid-19 deaths in the United States? 

Within the United States, the pandemic has mainly affected states located on the east and west coasts. To visualize the spatial distribution of Covid-19 deaths, we utilized the plotly package to create a map that shows the number of Covid-19 deaths for each state. From this map, we came to the conclusion that the majority of deaths are from states that were hit the hardest by the pandemic, which were New York, New Jersey, California, Texas and Florida. We then explored the number of Covid-19 deaths in New Jersey to determine which counties were most impacted by the disease. In this graph, we chose to create a pie chart to represent the percentages of Covid-19 deaths in each county. We found that Bergen, Essex, and Middlesex counties had the highest number of Covid-19 deaths when compared to other counties within the state.


Overall, what is the mortality rate of Covid-19 in the United States?

In order to answer this question, we looked at the proportion of Covid-19 deaths to overall deaths. Using county-level data, we selected and compared a couple of counties within New Jersey to observe the differences in Covid-19 deaths. From our analysis, we found that in Bergen and Essex counties, Covid-19 deaths accounted for roughly 28% and 30% of all deaths, respectively. 


