# Phonepe Pulse Data Visualization and Exploration
*This project provides a user-friendly tool for exploring and visualizing data from the Phonepe Pulse Github repository. The solution includes data extraction, transformation, database insertion, and dashboard creation using Streamlit and Plotly in Python.*

###Technologies
###The following technologies were used in this project:

* Github Cloning
* Python
* Pandas
* MySQL
* mysql-connector-python
* Streamlit
* Plotly
###Problem Statement
The Phonepe Pulse Github repository contains a large amount of data related to various metrics and statistics. The goal of this project is to extract this data, process it, and visualize it in a user-friendly manner. The solution must include data extraction, transformation, database insertion, and dashboard creation using Streamlit and Plotly.

###Approach
The approach used in this project includes the following steps:

Data extraction: Clone the Github repository using scripting to fetch the data and store it in a suitable format such as CSV or JSON.
Data transformation: Use Python and Pandas to manipulate and pre-process the data. This may include cleaning the data, handling missing values, and transforming the data into a format suitable for analysis and visualization.
Database insertion: Use the "mysql-connector-python" library in Python to connect to a MySQL database and insert the transformed data using SQL commands.
Dashboard creation: Use Streamlit and Plotly to create an interactive and visually appealing dashboard. Plotly's built-in geo map functions can be used to display the data on a map and Streamlit can be used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.
Data retrieval: Use the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe. Use the data in the dataframe to update the dashboard dynamically.
Deployment: Ensure the solution is secure, efficient, and user-friendly. Test the solution thoroughly and deploy the dashboard publicly, making it accessible to users.
Results
The result of this project is a live geo visualization dashboard that displays information and insights from the Phonepe Pulse Github repository in an interactive and visually appealing manner. The dashboard has at least 10 different dropdown options for users to select different facts and figures to display. The data is stored in a MySQL database for efficient retrieval and the dashboard is dynamically updated to reflect the latest data.

Users can access the dashboard from a web browser and easily navigate the different visualizations and facts and figures displayed. The dashboard provides valuable insights and information about the data in the Phonepe Pulse Github repository, making it a valuable tool for data analysis and decision-making.

###Dataset
The dataset used in this project can be found in the Data Link and is inspired from PhonePe Pulse.

###Learning Outcomes
By completing this project, you will gain hands-on experience with data extraction, processing, and visualization, as well as experience working with databases, dashboards, and web development. This project will provide a foundation for further learning and development in these areas and help you build a portfolio of practical skills.

###Installation
To install the necessary libraries, run the following command:

bash
Copy code
pip install -r requirements.txt
Usage
To run the dashboard, execute the following command in your terminal:

bash
Copy code
streamlit run app.py
The dashboard should be accessible in your web browser at http://localhost:8501.
