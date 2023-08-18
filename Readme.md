###
UiPath Project: 

This UiPath project automates the process of managing customer requests on zohodesk using Excel.

Prerequisites
•	UiPath Studio installed.
•	Excel application and Outlook email account configured.

Setup Instructions
1.	Clone or download the project repository to your local machine.
2.	Open UiPath Studio:
3.	Launch UiPath Studio on your computer.
4.	Open the Project:
5.	In UiPath Studio, click on "Open Project" and navigate to the project directory.
6.	Install Dependencies:
7.	Open the "Manage Packages" window from the "Design" tab.
8.	Install the following dependencies from the "Official" feed:
•	UiPath.Excel.Activities
•	UiPath.Mail.Activities
•	UiPath.System.Activities
•	UiPath.UIAutomation.Activities
9.	Update Configuration:
10.	Open the Config.xlsx file in the "Config" folder.
11.	Configure the required settings, such as email credentials, file paths, etc.
12.	Run the Workflow:
13.	Open the Main.xaml file in the "Main" folder.
14.	Click the "Run" button in UiPath Studio to execute the automation.
15. To terminate or interupt press the esc key.
16.	Deploy the robot by publishing and assign unattended robot from https://cloud.uipath.com/  Ochestrator.


Workflow Steps
1.	Read Requests:
•	Read customer requests from the Excel file specified in the configuration.
•	Process and analyze the requests.

2.	Update Excel File:
•	Update the Excel file with the processing status and relevant details.

