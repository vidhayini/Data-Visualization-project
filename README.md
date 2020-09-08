##Terrorism analysis With Insights

#This is my project as part of Internship program by Forsk Technologies in thier Project Season 3.
It is a Web application designed using Python with Dash and Plotly, displaying the trends of terrorism attacks using a dataset.

Two Visualizations have been implemented:
1)Map Tool-World Map,
           India Map
2)Chart Tool- World Chart,
              India Chart
              
#Map Tool(UI):
Eight Filters are used in the form of dropdowns and a Slider for both World and Inida Map Tools.
One of the feature added here is filtering the dropdowns based on previous one's using callbacks.If the user selects the region then country dropdown displays the values based on the region selected, and then the state and city.Legends indicate the type of attack on maps.

In India map the region and country are set by default using callbacks.

#Chart Tool(UI):
Three filters are used in the form of a dropdown, a search filter and a slider.
The graph displays the count on y-axis and year on x-axis. The results are displayed based on the selections from filters. 

India Chart Tool displays only related to India as by default region and country are selected to be 'South Asia' and India'.
