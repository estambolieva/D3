# World Cup Attendace Visualization  
  
## Description  
  
This is an interactive visualization of the attendance of the world cup from 1930 until 2014.  
The D3.js map animates through all of the years, in which the world cup is held - the yellow circle correcponds to number of attendees per world cup, while all the countries in blue (the rest are invisible) show, which countries participated in a given year.  
The buttons allow the user to click on an year of their choice independently of their cronological order.  
  
## How to Run Visualization  
   
 + open terminal  
 + navigate to the `animation-globe` directory using the cd command  
 + when there, check which version of Python your machine has installed on. To do so, execute the following in terminal:  
     `python --version`  
 + if the python version is 3.5, type in terminal:   
     `python -m http.server 8000` 
 + if the python version is 2.7, type in terminal:   
     `python -m SimpleHTTPServer`   
 + open a browser of your choice  
 + type in  
     `localhost:8000`  
 + click on `globe_animation.html` and explore the visualization  

## How to re-create this visualization  
  
1. First create a static map without any of the data from the world cup attendance.    
2. Create a bubble (thematic) graphic, which plots circles corresponding to the volume of attendace for each world cup. These circles are plotted on top of the countries, which have hosted the world cup games.  
3. Create your author-driven narrative – animate which countries and volume of attendance for each year of games. Notice that the world cup has been mostly hsoted in South America or Europe.  
4. Allow for a reader-driven narrative - allow the readers to interact with your visualization. Create buttons for each year of world cup games and allow the user to click through these buttons to explore the data shown to them.  
  
## How the visualization looks like  
  
   