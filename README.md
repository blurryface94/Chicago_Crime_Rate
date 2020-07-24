# Chicago Crime Rate
Predicting Crime Rates using Facebook's Prophet Time series. The data contains the summary of of crimes committed in Chicago. This case study examines the data to predict the crime rates.
 
 
## Table of contents
* [Technologies](#technologies)
* [Data](#data)
* [Model Details](#modeldetails)

## Technologies
  The following technologies were used for this part of the project:
  * Python 3
  * Jupyter notebook
  * Pandas: Python package for data analysis
  * Matplotlib and Seaborn: Python 2D plotting library
  * Sklearn: Python package for modeling creation
  * Prophet: Python package for prediction
  
## Data 
The Chicago Crime dataset contains the summary of the reported crimes which occured in the city of Chicago from the year 2001 to 2017. The dataset is acquired from Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. Datasource: https://www.kaggle.com/currie32/crimes-in-chicago
The dataset contains:
1. ID: Unique identifier for the record.
2. Case Number: The Chicago Police Department RD Number (Records Division Number), which is unique to the incident.
3. Date: Date when the incident occurred.
4. Block: address where the incident occurred
5. IUCR: The Illinois Unifrom Crime Reporting code.
6. Primary Type: The primary description of the IUCR code.
7. Description: The secondary description of the IUCR code, a subcategory of the primary description.
8. Location Description: Description of the location where the incident occurred.
9. Arrest: Indicates whether an arrest was made.
10. Domestic: Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.
11. Beat: Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car.
12. District: Indicates the police district where the incident occurred.
13. Ward: The ward (City Council district) where the incident occurred.
14. Community Area: Indicates the community area where the incident occurred. Chicago has 77 community areas.
15. FBI Code: Indicates the crime classification as outlined in the FBI's National Incident-Based Reporting System (NIBRS).
16. X Coordinate: The x coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection.
17. Y Coordinate: The y coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection.
18. Year: Year the incident occurred.
19. Updated On: Date and time the record was last updated.
20. Latitude: The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
21. Longitude: The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
22. Location: The location where the incident occurred in a format that allows for creation of maps and other geographic operations on this data portal. This location is shifted from the actual location for partial redaction but falls on the same block.

## Model Details
The following image shows the crime rate predicted for 2018 with the data for from the year 2007 to 2017:
<img width="836" alt="Screen Shot 2020-07-24 at 2 25 43 pm" src="https://user-images.githubusercontent.com/39994111/88361388-2cf4ae00-cdbc-11ea-9e93-8328de972abc.png">

The following image shows the break down of the prediction based on seasonality:
<img width="836" alt="Screen Shot 2020-07-24 at 2 46 28 pm" src="https://user-images.githubusercontent.com/39994111/88361833-be185480-cdbd-11ea-8ddc-23e7782c002c.png">


The following image shows the crime rate predicted for 2018 and 2019 with the data for from the year 2007 to 2017:
<img width="836" alt="Screen Shot 2020-07-24 at 2 26 24 pm" src="https://user-images.githubusercontent.com/39994111/88361457-59102f00-cdbc-11ea-803d-76a25464fd6e.png">

The following image shows the break down of the prediction based on seasonality:
<img width="836" alt="Screen Shot 2020-07-24 at 2 26 36 pm" src="https://user-images.githubusercontent.com/39994111/88361754-6f6aba80-cdbd-11ea-8634-8a7dd8460bfe.png">




