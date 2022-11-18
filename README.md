# CMPG323-Overview-30328608


CMPG323 Project 1 | Introduction to working with repositories


## Branching strategies
My branching strategy is trunk based development. The main idea behind this strategy is to make smaller changes more frequently and to limit merge conflicts.


## Project and Repository Structure
Each project will have its own repository. The overview repository will encompass links to the other project repositories.

![image](https://user-images.githubusercontent.com/111441837/185397070-478a7443-10ab-414c-a199-9631ca17e8fe.png)


## List of repositories
Links to other reposities created for other projects will be added to overview repository
Other repositories to be created may be: CMPG323 Project 2 repository, CMPG323 Project 3 repository, CMPG323 Project 4 repository, CMPG323 Project 5 repository

##Use of .gitignore file
An agile methodology approach is assumed for projects throughout the semester. .gitignore files were added under each project repository as needed.

##Storage of credentials and sensitive info
Currently the project and repository are public with 3 additional accounts added as collaborators for marking purposes. Additional security measures will be implemented should need arise. 

##References
CMPG323 Virtual class video recording
Haddad, R. 2022. What Are the Best Git Branching Strategies. https://www.flagship.io/git-branching-strategies/#:~:text=A%20branching%20strategy%2C%20therefore%2C%20is,interact%20with%20a%20shared%20codebase. Date of access: 18 Aug. 2022

Project 2 | API Development :

Link to project 2 repository:
https://github.com/nandigobile/CMPG323-Project2-30328608

This project entailed creating CRUD RESTful API project that would connect to a database storing IoT device data. The API project need contain a get, post, patch and delete method per resource.

The datasource is prepared by configuring the database- creating an SQL Server with a secure service account.
The API is then connected to data source.
Methods(GET, POST, PATCH, DELETE are implemeted for for Device,Zone, Category management functionality.
To close out the project, Security is implemeteed by ensuring that authentication has been set up to restrict access to the API.
The API project is then published to the service hosted on Azure.

Project 3 | Standards and patterns :

Link to project 3 repository:
https://github.com/nandigobile/CMPG323-Project-3-30328608-forked-repo-

For this project an existing ASP.NET Core MVC is gviven that required to be enhanced and improved.

To setup the project, an existing project was forked and the Web App was connceted to the datasource.
Design pattern implementation followed by creating repository classes for data acess operations relating to Devices, Zones and Categories. Thereafter data access operations were transferred from the controllers to the repository classes. Finally  repository classes were implemented in the controllers in place of data access operations that have been transferred to the repository classes.
To close out the project, security was ensured ny checking that no credentials are stored on GitHub and the app was published.

Project 4 | Testing and RPA:

Link to project 4 repository:
https://github.com/nandigobile/CMPG323-Project-4-30328608

This project is focused on RPA Testing and Uipath automation. Data from the excel file is read and executed by Uipath studio to automatiocally insert the values to the connected office site. This technology facilitates menial tasks input to avail people the time to focus on more intuitive tasks.

A Uipath process was created, data from a given access file was read and iterated over in Uipath to create records on the web application. Record results were tested and an excel spreadsheet with the testing results was updated. The Uipath solution was published to Uipath Orchestrator

Project 5 | Reporting and Monitoring:

Link to project 5 repository:
https://github.com/nandigobile/CMPG323-Project-5-30328608

This project is centered on using powerBI to provide insightful reports baseed on the connected office initiative to the relevant stakeholders.

There are mainly four report pages and a calculated full category field. Relationships have also been modelled to illustrate how the different entities/data sources relate to each other.

The first page is the High-level Metrics report which shows business stakeholders a summary of important data, namely:the number of distinct category names, the number of distinct device names, and the number of distinct zone names.

The second page of the report is the Device Monitoring page. This page comprises of visuals that can enable the stakeholders to monitor devices per category, monitor devices per zone and monitor online versus offline devices presented in a graph that indicates the percentage when selected.

The third page is the device registration report. This report is meaant illustrate visuals that enable a user to see how many users have registered over a timnespan, how many categories of devices have been created and how many zones contain registered devices on a timeline.

The last page of the report is the filtering page. These filters should be able to be used cross pages and visuals. Slicer visiuals have been utilised to filter the report based on device category, filter the report based on device platform, filter the report based on device zone and filter the report based on device registration date.





