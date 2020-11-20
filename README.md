# Nba Analysis Project
This project harnesses the nba-api to fetch NBA Stats.<br/>
Documentation can be found here: https://pypi.org/project/nba-api/<br/>
<br/>This project is broken into four parts:<br/>
       &nbsp;&nbsp;&nbsp;  1. All Time Stats<br/>
       &nbsp;&nbsp;&nbsp;  2. Player Comparison<br/>
       &nbsp;&nbsp;&nbsp;  3. Team Anaylsis<br/>
       &nbsp;&nbsp;&nbsp;  4. Point Prediction (Machine Learning)<br/>
 <br/> Frameworks Used: Pandas, NumPy, Sklearn, Matplotlib, Plotly
## All Time Stats
Used Jupyter Widgets and Plotly to create interative lists as well as charts to depict all time NBA stats <br/>
<br/>**Features:**<br/>
 &nbsp;&nbsp;&nbsp; 1. Interactive List of All Time Stats <br/>
<img src="https://media.giphy.com/media/XE78Hl1uaCFbL8Pl9t/giphy.gif" width="480" height="270"/><br/>
<br/>
 &nbsp;&nbsp;&nbsp; 2. Interactive Chart of All Time Stats <br/>
 
 <img src="https://media.giphy.com/media/QDQido5dtQ8XWxBdpT/giphy.gif" width="480" height="270"/><br/>


## Player Comparison
Used Jupyter Widgets and Plotly to create interative lists as well as charts to depict player stats and comparisons <br/>
<br/>**Key Features:**<br/>
 &nbsp;&nbsp;&nbsp; 1. Query for Player Career Stats and View Interactive Chart <br/>
<img src="https://media.giphy.com/media/EcKI8QdvWMooQ4XhsG/giphy.gif" width="480" height="270"/><br/>
<br/>
 &nbsp;&nbsp;&nbsp; 2. Interactive Chart to Compare Players <br/>
 <img src="https://media.giphy.com/media/N3DMBZTbNHHJFKpdjl/giphy.gif" width="480" height="270"/><br/>
 <br/>
 &nbsp;&nbsp;&nbsp; 3. Other Features <br/>
  &nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp; 1. All Time Career Stats Data with Averages<br/>
  &nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp; 2. All Time Career Stats Data Comparison between Players
  
 ## Team Anaylsis 
 Used Jupyter Widgets and Plotly to create interative lists as well as charts to depict team stats and comparisons <br/>
 <br/>**Key Features:**<br/>
 &nbsp;&nbsp;&nbsp; 1. View All Time Stats Per Team (Query For Team) <br/>
<img src="https://media.giphy.com/media/htzrnaWz9sA0ONBTFw/giphy.gif" width="480" height="270"/><br/>
<br/>
 &nbsp;&nbsp;&nbsp; 2. Interactive Chart to view Win/Loss (Query for Regular,Pre and Post Seasons as well as Season Year and Team Data) <br/>
<img src="https://media.giphy.com/media/j1uVxp1TZkAAn4l1UH/giphy.gif" width="480" height="270"/><br/>
<br/>

## Point Prediction
 Created a Linear Regression Model to predict the amount of points a player would score using 2018-2019 Regular Season NBA Data
 <br/>**Correlation Matrix:**<br/>
 <img src="https://i.imgur.com/91LNDkj.png" width="480" height="270"/><br/>
<br/>
<br/>**Model Scores:**<br/>
<br/>Mean Absolute Error: 67.57841065663386
<br/>Mean Squared Error: 8226.306123212107
<br/>Root Mean Squared Error: 90.6989863405987
Model Accuracy: 0.9683556506013027
