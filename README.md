# PowerBI-python-intergration
## Overview
The Power BI Visualization Program is a Python script that utilizes the Power BI Client library (powerbiclient) to authenticate a user and create a Power BI visualization from a CSV file. It provides an interactive and seamless way to connect to Power BI and generate visual representations of data.

## Features
* Authentication: The program supports two authentication methods: Device Code Login Authentication and Interactive Login Authentication. Device Code Login Authentication is used for the initial login process, where the user needs to copy a code and paste it into the authentication window. Interactive Login Authentication allows for easier subsequent logins by utilizing the credentials saved in the browser.

* Data Import: The program reads data from a CSV file and converts it into a pandas DataFrame. It assumes that the CSV file is located in the same directory as the script or notebook.

* Visualization Creation: Using the QuickVisualize class from the powerbiclient library, the program creates a Power BI visualization. It takes the dataset configuration obtained from the DataFrame and the authentication object as parameters.

* Display: The created visualization is displayed in the output of the script or notebook, allowing users to view and interact with the Power BI visualization.

## Prerequisites
* Python 3.x
* Installation of the powerbiclient library and its dependencies
* Installation of the pandas library

## Usage
1. Install the required libraries: powerbiclient and pandas.
2. Save the CSV file that contains the data for the Power BI visualization in the same directory as the script or notebook.
3. Import the necessary modules from the powerbiclient library, as well as pandas.
4. Set up the authentication method: 
   1.  Use DeviceCodeLoginAuthentication() for the initial authentication process. Copy the code displayed and paste it into the authentication window that appears when prompted.
   2. Use InteractiveLoginAuthentication() for subsequent logins, which utilize the credentials saved in the browser.
  
5. Read the CSV file into a pandas DataFrame using pd.read_csv()
6. Create the visualization using QuickVisualize and pass the dataset configuration obtained from the DataFrame and the authentication object as parameters.
7. Display the visualization object to render the Power BI visualization in the script or notebook output.


## Support and Contributions
For any questions, issues, or suggestions, please feel free to open an issue on the program's GitHub repository. Contributions are welcome!
