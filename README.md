## 📖 Project Overview
This repository houses the Loan Application Automation process designed using UiPath RPA to streamline and automate the loan application process at UiBank. The solution automates several critical steps in the process, which include handling emails, reading loan application data from CSV/Excel files, entering loan details into a banking application, generating unique Loan IDs, and sending confirmation responses to the business team. By leveraging RPA, this automation significantly reduces the manual intervention required, making the entire loan application process faster, more efficient, and error-free.

---

## 🎬 Demo Video
Watch the demo video to see the entire process:
[Loan Application Automation - Demo](https://github.com/Raxeira/loan-application-automation/blob/main/Loan%20Application%20Automation%20-%20Demo.mp4)

---

## 🔄 Process Flow 
The process starts once an email containing a loan application is received, and the automation follows a series of steps:
1. **Email Reception**: The automation checks for incoming loan application emails.
2. **Attachment Download**: The loan application file (usually in CSV or Excel format) is downloaded from the email.
3. **Data Extraction**: The data from the downloaded file is extracted and validated for completeness and correctness.
4. **Data Entry into UI Bank**: Extracted data is entered into the UI Bank application for processing.
5. **Loan ID Generation**: Once the data is entered, the system generates a unique Loan ID for the application.
6. **Excel Update**: The generated Loan ID is saved back into the Excel file for record-keeping.
7. **Confirmation Email**: A confirmation email with the Loan ID is sent to the business team to notify them of the successful processing.
