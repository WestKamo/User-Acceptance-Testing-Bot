# CMPG 323 Project 4 - User Acceptance Testing Bot

# Overview

This project involves creating a bot using UiPath to automate the User Acceptance Testing (UAT) process for a web application. UAT is a critical step in the software development lifecycle where testers verify that the input data generates the expected output. In this case, the bot automates the repetitive tasks involved in UAT, such as data entry and validation, allowing testers to focus on more complex tasks.

# Prerequisites

Before you begin, ensure you have the following:
- A [UiPath Automation Cloud](https://cloud.uipath.com/) account.
- The [UiPath Studio Community Edition](https://www.uipath.com/start-trial) installed on your computer.
- Access to the web application for which UI automation will be performed. Use the following link for this project: [Tech Trends Telemetry Portal](https://techtrendstelemetryportal.azurewebsites.net).
- An Excel file containing the test data for automation.

## Implementation Steps

# 1. Project Setup

- Clone the Repository: Clone the GitHub repository named `CMPG 323 Project 4 - <your student number>` to your local machine.
- Install UiPath Studio: Ensure you have UiPath Studio installed and configured.
- Create a UiPath Process: Open UiPath Studio and create a new process named `NWU Tech Trends Telemetry Portal - User Acceptance Testing`.

# 2. User Acceptance Testing Automation

- Read Input Data: Use UiPath to read data from the Excel file into a data table.
- UI Automation:
  - Navigate to the URL in a web browser to enter data.
  - Insert the data from each record into the respective fields on the web application.
  - Click the ‘Submit’ button to create a new record.
  - Verify the newly created record.
- Record Results: Update the Excel spreadsheet with testing results indicating whether each test passed or failed.

# 3. Project Close-Out

- Deploy Solution: Publish the UiPath solution to UiPath Orchestrator.
- Documentation: Ensure the README.md file is updated with usage instructions and other relevant details.

# Usage Instructions

1. Clone the Repository: Use the `git clone` command to clone the repository to your local machine.
2. Open the UiPath Project: Launch UiPath Studio and open the `NWU Tech Trends Telemetry Portal - User Acceptance Testing` project.
3. Run the Automation: Execute the automation to perform UAT on the web application. The bot will read the input data from Excel, perform the required actions on the web application, and update the Excel file with test results.
4. View Results: Check the Excel file to view which tests passed or failed.

# Reference List
https://github.com/WestKamo/CMPG-323-Project-4-38924846/blob/main/ReferenceList.docx

# Additional Resources

- [UiPath Academy](https://academy.uipath.com/) for further training and certification.
- [UiPath Community](https://community.uipath.com/) for community engagement and support.
