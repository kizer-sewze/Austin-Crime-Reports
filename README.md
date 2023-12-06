# Austin-Crime-Reports
Final Project for SD 322E Elements of Data Science

Our project is looking at crime data across Austin in the year 2023 and aims to analyze the various factors that shape crime in Austin, such as the location where the crime was committed and the factors that affect the rate at which the crime was officially cleared. Our goals for this project are to 1) quantify the types of crime in accordance with the location of the crime and 2) explore the factors that could correlate to a quicker time of resolution for the crime. 

Link to the data: https://data.austintexas.gov/Public-Safety/Crime-Reports/fdj4-gpfu 

The dataset contains information about crime in Austin with data starting from January 2018 that is updated weekly. The data is from the Austin Police Department. For the purposes of our project, we used only the data from January 2023 onwards, because of how large the dataset was. The dataset contains many different variables relating to Austin crimes, but the ones we are primarily interested in are the variables relating to location (zip code, district, council_district, address, location type), the type of crime (family violence), and the dates when the crime was committed or cleared (occured date time, report time, etc). 

Our hypotheses are 
  1) The clearance rate of a council district is highly dependent on the number of crimes committed within it.
  2) The clearance rate of a council district is highly dependent on its affluence.
  3) The number of crimes committed per council district is highly dependent on its clearance rate.
  4) The affluence of each council district is highly dependent on its  average clearance time. 



