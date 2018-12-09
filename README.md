# Data 512 A-6 Final Project - Predicting Earthquakes

### Abstract


The overall goal of this project is to analyze publicly available data for earthquakes and apply various machine learning algorithms to try and predict future occurrences.

All the code used for cleaning, prepping and transforming the data as well as creating the visualizations and running the algorithms have been written in Python, and has been listed in the Jupyter notebook 'Data512_Final_Project.ipynb'.

This work was performed as the final project for the Data 512 course at the University of Washington Fall 2018.<br>
The course wiki page can be found at the link below <br>
[Course Wiki](https://wiki.communitydata.cc/Human_Centered_Data_Science_(Fall_2018)/Assignments#Weekly_reading_reflections) <br>
Lets jump in.

### License

The code is released under the MIT license, and is intended to be fully reproducible. 
Additional details can be found at the link below <br>
[License](https://github.com/Gmoog/data512_finalproject/blob/master/LICENSE)

### Reproducibility

All the code and analysis performed in here is intended to be fully reproducible. <br>
To clone this repository use the command <br>
 > git clone https://github.com/Gmoog/data512_finalproject.git


In case you would rather not clone the entire repository, the data can be downloaded in a tab separated file, and can be imported into excel or python for analysis. <br>
The data can be downloaded from the link below <br>
[National Geophysical Data Center / World Data Service (NGDC/WDS): Significant Earthquake Database. National Geophysical Data Center, NOAA](http://dx.doi.org/10.7289/V5TD9V7K)

### Data

The data is from the significant earthquake database, and contains historic data from 2150 BC to the present day, of earthquakes from all over the world. The data is constantly updated to reflect the latest events.


As per the description from the 'data.nodc.noaa.gov' site where the data is hosted:
 > The Significant Earthquake Database is a global listing of over 5,700 earthquakes from 2150 BC to the present. A significant earthquake is classified as one that meets at least one of the following criteria:
 
 > caused deaths, caused moderate damage (approximately 1 million dollars or more), magnitude 7.5 or greater, Modified Mercalli Intensity (MMI) X or greater, or the earthquake generated a tsunami. 
 
 > The database provides information on the date and time of occurrence, latitude and longitude, focal depth, magnitude, maximum MMI intensity, and socio-economic data such as the total number of casualties, injuries, houses destroyed, and houses damaged, and dollar damage estimates. 
References, political geography, and additional comments are also provided for each earthquake. If the earthquake was associated with a tsunami or volcanic eruption, it is flagged and linked to the related tsunami event or significant volcanic eruption.
 

The fields that are key from the perspective of our analysis are detailed in the table below <br>

| Field Name    | Datatype      | Description |
| :-------------: | :-------------: | :-------------: |
|  Year | Integer | The year of occurence  |
| Focal Depth  | Integer  | Depth of the epicenter |
| Eq_Primary | Float | Magnitude of the earthquake |
| Country | String | Name of the country |
| Location_Name | String | Specific location in the country | 
| Latitude | Float | Coordinates of the exact location |
| Longitude | Float | Coordinates of the exact location |



The data can be downloaded in a tab separated file, and can be imported into excel or python for analysis.<br>
All the data used in this analysis can be found in the file 'earthquake_historical.tsv' <br>

For more information about the data and downloading it, please access the link below <br>
[National Geophysical Data Center / World Data Service (NGDC/WDS): Significant Earthquake Database. National Geophysical Data Center, NOAA](http://dx.doi.org/10.7289/V5TD9V7K)


__License__

The data is hosted on a public information website, and can be freely distributed and copied, with the appropriate credits.

A copy of the text from the webiste is quoted below for reference:

> The National Centers for Environmental Information (formerly the National Geophysical Data Center) website is provided as a public service by the U.S. Department of Commerce, National Oceanic and Atmospheric Administration (NOAA), National Environmental Satellite, Data and Information Service (NESDIS). Information presented on these web pages is considered public information and may be distributed or copied. 

More details about their privacy policy can be found at the link below <br>
[NOAA privacy](https://www.ngdc.noaa.gov/ngdcinfo/privacy.html)


### Software and Tools used

All of the analysis has been performed using Python and its libraries like Pandas and Numpy with matplotlib aiding in the visualizations. The data is not too big, and all the training and testing of the models were done locally, without needing support from cloud computing resources (Amazon EC2). <br>

I list out all the python packages used in the analysis below <br>
- Numpy <br>
- Pandas <br>
- Matplotlib <br>
- Basemap <br>

The different algorithms tested on the data are part of the Scikit Learn python package <br>

- Linear Regression <br>
- Decision tree <br>
- Random forest <br>


### Resources

[Machine learning predicts earthquakes in a lab](https://www.cam.ac.uk/research/news/machine-learning-used-to-predict-earthquakes-in-a-lab-setting) <br>
[Hindukush earthquake magnitude prediction](https://www.researchgate.net/publication/307951466_Earthquake_magnitude_prediction_in_Hindukush_region_using_machine_learning_techniques) <br>
[Analysis of soil radon data using decision trees](https://www.sciencedirect.com/science/article/pii/S0969804303000940)<br>
[Using Neural Networks to predict earthquake magnitude](https://www.sciencedirect.com/science/article/pii/S0893608009000926)<br>
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6033417/ <br>
https://earthquake.usgs.gov/data/data.php#eq <br>
https://arxiv.org/pdf/1702.05774.pdf <br>
https://www.scientificamerican.com/article/can-artificial-intelligence-predict-earthquakes/



