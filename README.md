# CMPG-323-Project-4---30332338 README FILE
 ![uipath](https://github.com/Madzivhandila/CMPG-323-Project-4---30332338/assets/75025282/03f65575-8b45-485a-b62b-3756486f34f5)


## Overview
**************************************************************************************************
Testing is a critical aspect of any solution, and it can be approached from various perspectives, including internal development team testing and business user acceptance testing (UAT). User Acceptance Testing, often referred to as UAT, plays a pivotal role in most development lifecycles as it serves as the ultimate 'go/no-go' decision point. UAT is primarily concerned with ensuring that the input provided to a solution yields the expected output. If the solution does not produce the desired output, it must be adjusted and retested before it can proceed to production.

Robotic Process Automation (RPA) involves using technology to replicate human tasks, particularly those related to front-end or User Interface (UI) automation. RPA is commonly used to automate repetitive and time-consuming tasks, freeing up human resources to focus on more complex and creative tasks.

In the context of the web application developed in Project 3, before deploying it to production, it must undergo UAT. During UAT, a team of testers works with a test dataset containing input and expected output data. Testers input each dataset record into the web application's fields and verify that the expected output is generated. In this case, the expected output would be a new record displayed on the web application after adding the item. Automating this highly repetitive process with RPA is both efficient and recommended.


![0_MdUM-Qm-sDSH_B6o](https://github.com/Madzivhandila/CMPG-323-Project-4---30332338/assets/75025282/7e1a81fe-18e0-436d-8e9e-fb2ad70fee29)


**************************************************************************************************
## Requirements
**************************************************************************************************
### Functional Requirements
Functional requirements define the specific functionality a system must possess and how those functions should be executed.

### Non-Functional Requirements
Non-functional requirements encompass aspects of a solution that impact the system's quality attributes or platform. These requirements support the implementation of functional requirements in line with good software practices.
**************************************************************************************************
## Project Tasks

### GitHub Administration
**************************************************************************************************
- **Create and Configure GitHub Repository**
  - Create a repository named 'CMPG 323 Project 4 - <add your student number>'
  - Create a ReadME.md file to describe the project and guide stakeholders on how to use the report.

- **Project Progress**
  - Ensure that the solution is committed and pushed to source control throughout the project.
  - Update the GitHub project iteratively to demonstrate project progress.
**************************************************************************************************
### Project Setup
**************************************************************************************************
- **Create the Project**
  - Clone your GitHub repository.
  - Install UiPath Studio.
  - Create a new UiPath process named 'Connected Office Web Application – User Acceptance Testing.'
**************************************************************************************************
### User Acceptance Testing
**************************************************************************************************
- **Read the input data**
  - Read data from Excel into a data table in UiPath.
  - Verify that the data is correctly readable and iterable in UiPath.

- **UI Automation**
  - For each record in the data table, navigate to the URL in the browser where data can be entered to create a new record.
  - Populate the web application fields with data from each record to create a new record on the web application.
  - Click the 'submit' button on the web application to create a new record.
  - Navigate to the URL to view the newly created record on the web application.

- **Record Results**
  - If the item was created successfully, update the data table record to indicate a successful test.
  - If the item was not created, update the data table to depict a failed test.
  - Update the Excel spreadsheet with the testing results in the 'Test Results' column (update with TRUE or FALSE).
**************************************************************************************************
### Project Close-out
**************************************************************************************************
- **Deploy Solution**
  - Publish the UiPath solution to the UiPath Orchestrator.
**************************************************************************************************
![NWU](https://github.com/Madzivhandila/CMPG-323-Project-4---30332338/assets/75025282/95f091f2-987a-44c4-9d42-772ea226f896)

