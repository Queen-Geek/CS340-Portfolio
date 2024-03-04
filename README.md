# CS340 Portfolio README

Grazioso Salvare Dashboard

# Project Overview
The Grazioso Salvare Dashboard is a web application developed to help the Grazioso Salvare company efficiently identify suitable animals from the Austin Animal Center that meet various rescue operation criteria. The application utilizes a MongoDB database to store animal data, Python middleware for server-side logic, and a Plotly-Dash-Leaflet interface for interactive visualization.

# Dataset
The project uses the aac_shelter_outcomes.csv file, which contains detailed records of animal outcomes from the Austin Animal Center. This dataset is instrumental in providing real-time data for the dashboard, enabling users to filter and search for animals based on specific attributes such as breed, age, and outcome type.

# Key Features
•	Branding with Logo: Custom branding is employed throughout the dashboard using the Grazioso Salvare logo.
•	CRUD Operations: The CRUD.py script allows Create, Read, Update, and Delete operations on the database records.
•	Data Table and Filters: Users can view and filter animal data based on various criteria to find suitable animals for rescue operations.
•	Visualizations: The dashboard features a pie chart for breed distribution and a map for geolocating animals or shelters.

# Technology Stack
•	Python 3.6+
•	MongoDB 4.2+
•	Pymongo 4.2
•	Plotly Dash
•	Dash Leaflet

# Installation
To run the project, ensure you have Python and MongoDB installed. Use pip to install the required libraries:
pip install pymongo plotly dash dash-leaflet 

1.	Set up your environment by installing the necessary software and libraries.
2.	Import the aac_shelter_outcomes.csv into your MongoDB instance.
3.	Execute the CRUD.py to interact with the database.

# Usage
To launch the dashboard:
1.	Start the Jupyter Notebook ProjectTwoDashboard.ipynb.
2.	The application will be served on a local web server and can be accessed through a web browser.

# Data Integration
The CSV data is imported into MongoDB, where it is then queried by the dashboard application to retrieve and display information.

# Challenges
One of the challenges addressed was ensuring the accuracy of data filtering, particularly with variations in breed naming. This was addressed through careful database query design and regular expressions.

# Walkthrough
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

  # Questions
  How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the       
  dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?
  How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this 
  project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?
  What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

  # Answer
  Writing maintainable, readable, and adaptable code is a key aspect of software development, particularly in projects that require scalability and longevity. In the CRUD Python module 
  from Project One, this approach allowed for a clear and efficient way to manage database operations, which was instrumental when integrating the dashboard widgets in Project Two.

  Maintainable code means that it's structured and documented well enough for others (or yourself at a later time) to understand and modify. Readable code is clear and intuitive, often 
  achieved through consistent naming conventions and a logical structure that follows best practices. Adaptable code is flexible to changes, whether they are new requirements or 
  adjustments in existing functionalities.

  Working with this method provides numerous advantages, such as simplifying debugging and facilitating collaboration among developers who may need to work with the codebase. It also 
  ensures that the software can evolve over time as new requirements emerge.

  This CRUD module, designed to be reusable and modular, could be applied in future projects that require database interactions. For instance, it could be repurposed for different types 
  of databases or expanded to include more complex queries and transactions.

  Approaching problems as a computer scientist involves systematic thinking and applying computational methods to devise solutions. In the case of Grazioso Salvare, the approach to 
  database and dashboard design was strategic and methodical. Unlike some previous assignments that may have been more theoretical, this project demanded practical, user-centric 
  solutions. Techniques like data modeling, user interface design, and performance optimization were key strategies.

  The iterative nature of this project work, building upon foundational computer science skills, is an example of how such an approach can evolve over time, leading to the successful 
  completion of complex, real-world projects.

  Computer scientists play a pivotal role in shaping technologies that impact our daily lives. Their work matters because it contributes to advancements in various fields and industries. 
  For a company like Grazioso Salvare, efficient and effective management of data through well-designed software can streamline operations, enhance decision-making, and ultimately 
  support the company's mission more effectively.
