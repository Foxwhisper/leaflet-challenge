# **leaflet-challenge**
## Instructions
Before You Begin
Create a new repository for this project called `leaflet-challenge`.  
Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: Leaflet-Part-1 and Leaflet-Part-2.
This Challenge uses both HTML and JavaScript, so be sure to add all the necessary files. These will be the main files to run for analysis.

### Instructions Part 1: Create the Earthquake Visualization

![2-BasicMap](https://github.com/user-attachments/assets/4fc97503-ff21-4d24-ada7-6365c2395929)

Your first task is to visualize an earthquake dataset. Complete the following steps:  

Get your dataset. To do so, follow these steps:  
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the `USGS GeoJSON Feed` page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:
![3-Data](https://github.com/user-attachments/assets/8a2ec458-5797-4bfa-adf4-8ec9d7899067)


When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:
![4-JSON](https://github.com/user-attachments/assets/087a4ecd-f235-4699-bd4b-0a8f322bbe96)


Import and visualize the data by doing the following:  
* Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.  
     * Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
     * Hint: The depth of the earth can be found as the third coordinate for each earthquake.  

* Include popups that provide additional information about the earthquake when its associated marker is clicked.  
* Create a legend that will provide context for your map data.  
* Your visualization should look something like the preceding map.  

### Instructions Part 2: Gather and Plot More Data  

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at `https://github.com/fraxen/tectonicplates`.  

This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.  

The following image is an example screenshot of what you should produce:

![5-Advanced](https://github.com/user-attachments/assets/cd5bf20f-1d90-4ac1-be85-184980a5f892)
  
Perform the following tasks:  
* Plot the tectonic plates dataset on the map in addition to the earthquakes.  
* Add other base maps to choose from.  
* Put each dataset into separate overlays that can be turned on and off independently.  
* Add layer controls to your map.  

### Requirements
These requirements apply only to "Part 1: Create the Earthquake Visualization" as "Part 2" is optional with no extra points earning.

### References
Dataset created by the United States Geological SurveyLinks to an external site..
