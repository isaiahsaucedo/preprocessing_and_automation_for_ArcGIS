# Exploring Python inside of ArcGIS

This repository introduces a walkthrough on how to start getting familiar with the arcpy library and explore some of what it has to offer. Though it may be more efficient to utilize the ArcGIS Toolbox, it might be useful to start pulling functions and script outside this environment in order to better collaborate and scale with larger projects. Here is a simple way to get started.

## Step 0: Create or Open an ArcGIS Project

## Step 1: Run a Process inside ArcGIS
Choose a process you would like to run in the Geoprocessing Toolbox, and run it on a file inside the directory in which your data resides. You can find the 'Tools' section under the 'Analysis' tab.

![alt text](https://github.com/isaiahsaucedo/python_and_ArcGIS/blob/master/geoprocessing.png)

## Step 2: Look up History 
The History button allows you to examine processes you previously ran and displays them on the right pane. 

![alt text](https://github.com/isaiahsaucedo/python_and_ArcGIS/blob/master/hist-location.png)

## Step 3: Drag and Drop 
Drag and drop the process ran in the previous step into the Python window below. You may also do this by right clicking on a process and select "Send to Python Window". 

![alt text](https://github.com/isaiahsaucedo/python_and_ArcGIS/blob/master/history.png)
![alt text](https://github.com/isaiahsaucedo/python_and_ArcGIS/blob/master/python-win.png)

## Step 4: Start exploring 
From here, you may hover over the script to examine the optional and required parameters for the selected method. These functions can then be added into a separate python file to make more room for specific, personalized tasks. Happy Scripting! 
