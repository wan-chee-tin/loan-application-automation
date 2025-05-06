## 📖 Project Overview
This repository houses the Loan Application Automation process designed using UiPath RPA to streamline and automate the loan application process at UiBank. The solution automates several critical steps in the process, which include handling emails, reading loan application data from CSV/Excel files, entering loan details into a banking application, generating unique Loan IDs, and sending confirmation responses to the business team. By leveraging RPA, this automation significantly reduces the manual intervention required, making the entire loan application process faster, more efficient, and error-free.

## 🚀 How to Run
Before running the automation, ensure that you have the following tools and software installed:
1. **UiPath Studio**: The primary tool for creating and executing the RPA workflows. You can download it from the official [UiPath website](https://www.uipath.com/).
2. **Microsoft Excel**: Used for reading and updating loan application data.

To get this project up and running on your local machine, follow these steps:
1. Download the project as a ZIP file from [this link](https://github.com/Raxeira/loan-application-automation/archive/refs/heads/main.zip).
2. Unzip the downloaded file to a directory of your choice.
4. Navigate to the Loan Processing Automation/Data folder and open the Config.xlsx file. This file contains configuration settings required for the automation to run.
5. Open the project in UiPath Studio.
6. Once you've opened the project in UiPath Studio, navigate through the following steps to configure your email authentication:
- Locate the search bar at the top of the UiPath Studio.
- Type the email activity you need to configure `Get Email List`, `Download Attachment`, and `Send Email`.
- Click on the activity in the search results to navigate to it within the workflow.
- In the Properties panel, modify the email connection settings based on your email provider.
7. Run the automation in UiPath Studio to process the loan application automatically.

## 🔄 Process Flow 
The process starts once an email containing a loan application is received, and the automation follows a series of steps:
1. Email Reception: The automation checks for incoming loan application emails.
2. Attachment Download: The loan application file (usually in CSV or Excel format) is downloaded from the email.
3. Data Extraction: The data from the downloaded file is extracted and validated for completeness and correctness.
4. Data Entry into UI Bank: Extracted data is entered into the UI Bank application for processing.
5. Loan ID Generation: Once the data is entered, the system generates a unique Loan ID for the application.
6. Excel Update: The generated Loan ID is saved back into the Excel file for record-keeping.
7. Confirmation Email: A confirmation email with the Loan ID is sent to the business team to notify them of the successful processing.

## 🛠️ Technologies Used 
- UiPath: The primary tool used to build and deploy this robotic process automation (RPA) solution.
- MS Excel: Used for reading and updating loan application data.
- UI Bank Application: The banking application where loan details are entered, and loan IDs are generated.
