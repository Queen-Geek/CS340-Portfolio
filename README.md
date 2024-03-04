#CS340 Portfolio README

Grazioso Salvare Dashboard

#Project Overview
The Grazioso Salvare Dashboard is a web application developed to help the Grazioso Salvare company efficiently identify suitable animals from the Austin Animal Center that meet various rescue operation criteria. The application utilizes a MongoDB database to store animal data, Python middleware for server-side logic, and a Plotly-Dash-Leaflet interface for interactive visualization.

#Dataset
The project uses the aac_shelter_outcomes.csv file, which contains detailed records of animal outcomes from the Austin Animal Center. This dataset is instrumental in providing real-time data for the dashboard, enabling users to filter and search for animals based on specific attributes such as breed, age, and outcome type.

#Key Features
•	Branding with Logo: Custom branding is employed throughout the dashboard using the Grazioso Salvare logo.
•	CRUD Operations: The CRUD.py script allows Create, Read, Update, and Delete operations on the database records.
•	Data Table and Filters: Users can view and filter animal data based on various criteria to find suitable animals for rescue operations.
•	Visualizations: The dashboard features a pie chart for breed distribution and a map for geolocating animals or shelters.

#Technology Stack
•	Python 3.6+
•	MongoDB 4.2+
•	Pymongo 4.2
•	Plotly Dash
•	Dash Leaflet

#Installation
To run the project, ensure you have Python and MongoDB installed. Use pip to install the required libraries:
pip install pymongo plotly dash dash-leaflet 

#
1.	Set up your environment by installing the necessary software and libraries.
2.	Import the aac_shelter_outcomes.csv into your MongoDB instance.
3.	Execute the CRUD.py to interact with the database.

#Usage
To launch the dashboard:
1.	Start the Jupyter Notebook ProjectTwoDashboard.ipynb.
2.	The application will be served on a local web server and can be accessed through a web browser.

#Data Integration
The CSV data is imported into MongoDB, where it is then queried by the dashboard application to retrieve and display information.
Challenges
One of the challenges addressed was ensuring the accuracy of data filtering, particularly with variations in breed naming. This was addressed through careful database query design and regular expressions.

#Walkthrough
The Grazioso Salvare Dashboard was designed with essential elements to serve specific organizational requirements:
•	Incorporation of Brand Elements: The dashboard prominently features the Grazioso Salvare logo for brand consistency.
•	Direct Linking: There is a dedicated hyperlink directing users to the Grazioso Salvare official website.
•	Interactive Data Table: The dashboard displays an interactive table loaded with data from the Austin Animal Shelter, enhanced by tailor-made filters for:
•	Specialized Animal Selection Filters: These filters streamline the search process, enabling the identification of animals suited for distinct rescue services, such as:
•	Water Rescue operations
•	Mountain or Wilderness Rescue missions
•	Disaster Response or Individual Tracking tasks
•	Breed Composition Visualization: A pie chart vividly illustrates the distribution of breeds currently available at the shelter.
•	Geolocation Feature: An interactive map pinpoints the geographical location of any animal selected by the user.
These features were implemented to ensure that the dashboard meets the functional and aesthetic criteria set forth by Grazioso Salvare.

# Project Questions and Answwers
  
