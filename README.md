# InfoVis-Final-Project
 Visualized the Stop and Crime UK dataset to reveal patterns in criminal activity across the UK utilizing tableau. Applied theoretical concepts of visualising geo-spatial, multi-dimensional categorical, continuous variables in the data.


## How to use the worksheets (we also made a video to help if you run into any problem):

Tableau doesn't allow for linking local data with relative paths, so the user will have to do so manually. When opening a new worksheet for the first time, the user will be prompted with many error message and asked to locate the data. All of our data is in the same folder as this README file and it should be relatively easy to find the data files (.csv) and link it back with Tableau. 

Note that the videos of our visual analysis of the datasets can be directly viewed in the ScreenCast folder. 

If the reader is asked to provide the information about the database, here is what to add:

Server: 		136.144.218.47
Port: 			3306
Database: 		crime_data_uk
Username: 		tudelftteacher
Password: 		!QsxI5rc6ODEb390lO
SSL is NOT required

Before opening "Crime Data.twb" and "Demographic.twb" please move the "Local Data" folder into ".../Documents/My Tableau Repository". This folder contains a library used to show the LA codes on the map and these two worksheets won't work without it.

If some dashboards don't work after opening "Stop and search.twb":
	1) please go to the "SearchedObjectsOverTime" sheet in Tableau (in the list of sheets and dashboard on the bottom)
	2) click on the "Abc" symbol next to "Date" (the reader can easily find this on the top left corner of tableau, under "Dimensions")
	3) Select "Date" instead of "String"
This problem has appeared to us when moving the worksheet from one device to another but we haven't been able to find a solution online or in the Tableau documentation.
