# Visualization-Interactive-Dashboard
### The purpose of this repository is to provide an example of my Interactive Dashboarding capabilities
#### For this project, I used the kaggle dataset [Formula 1 World Championship (1950-2023)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
From the above dataset, I chose to visualize all of Formula 1 Driver Lewis Hamilton's Qualifying performances throughout his career. The objective was to filter by the Grand Prix, and the year in which each Grand Prix took place.
For context, Qualifying is where drivers attempt to set their fastest laps to determine their starting position for the Race. Qualifying is structured of into 3 sessions. 'Q1' where the slowest 5 drivers are eliminated, 'Q2' where the next slowest 5 drivers are eliminated, and 'Q3' where the top 10 drivers are classified by their overall lap time. 

##### [Creating a Dataframe to be Visualized](https://github.com/Nikhil-1421/Visualization-Interactive-Dashboard/blob/main/Creating%20Dataframe%20to%20be%20Visualized.ipynb)
I began by using kaggle to create a notebook where I could parse information from the various dataframes to create one collective dataframe that only displayed Hamilton's qualifying 1,2, and 3 lap times, respectively, his finishing position for the overall qualifying, the year of the grand prix, and the name of the grand prix.

##### [Lewis Quali FINAL](https://github.com/Nikhil-1421/Visualization-Interactive-Dashboard/blob/main/Lewis%20Quali%20FINAL.ipynb)
Next I used a local Jupyter Notebook to perform some Data Wrangling, and to manipulate the dataframe I had created to better output the information I needed it to. Lastly, I used Jupyter Notebook to launch the Dashboard on a local server. 

#### [Example of Dashboard in Use](https://www.canva.com/design/DAF67LtrjaY/lmPvJoZqJyzG9iMorCdgHw/watch?utm_content=DAF67LtrjaY&utm_campaign=share_your_design&utm_medium=link&utm_source=shareyourdesignpanel)
Because the dashboard I created can only be viewed on a local server for free, I have uploaded a video of the interactive dashboard in use and it can be viewed with the above link. The dashboard creates a scatterplot of Hamilton's Qualifying times and plots them based on which session they occured within. If a laptime of 0 is observed, that indicates that Lewis did not perform well enough in the session prior to make it to that session. There were some years where Formula 1 did not hold a particular Grand Prix, the example in the video is the 2020 Monaco Grand Prix - for those instances I had the dashboard output a message indicating that Lewis wasnt here! 

Thanks for checking out my dashboard!
