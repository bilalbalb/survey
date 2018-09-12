Birth Date Survey
-----------------
Overview
--------
This application ask user for birth date then shows confirmation if everyting worked fine. The allowed max date is the date of survey, while the min date is 
01 01 1990. 

Application Structure
---------------------

1. app folder: The entry point for all the UI components.
2. Welcome folder: Contains the landing page for the application
3. survey folder: Contains the survey form
4. survey-list folder: Contains the result of survey
5. page-not-found folder: Contains the component for any wrong requested page
6. dialog folder: Contains confirmation dialog upon submiting the survey question
7. Services folder: This folder contains 2 services: A) backend service: This service simulate DB by using in memory api
						     B) survey service: This service is reponsible of reading and wrting to db
8. shared folder: Contains material module, which import/export the required angular material modules

Used Technology
---------------
Angular 6, bootstrap, font-awesome, angular material, in-memory-api

Run the application by navigate to src folder then type "ng serve -o". You need angular cli installed

