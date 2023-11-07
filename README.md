# vfdatabase

This is a website that will allow VF employees to create new records for audits, upload PDF files, monitor the expiration dates of those files and export the PDFs.

## Planning and Requirements Gathering

Define the specific requirements for the audit records, including the date fields to be captured.

Determine the tech stack for the website

## Set Up Environment

Acquire web hosting and a domain name

Set up a secure HTTPS connection for data transmission

## Front-End Development

Design the UI for the website, including forms to create new audit records

Implement user registration and login functionality

## Back-End Development

Build the server-side app using chosen tech stack -- NAME OF STACK

Implement a database to store audit records, user information, uploaded PDFs and expiration dates

## Audit Record Creation

Develop forms to allow users to create new audit records

store the audit record data in the database, associating it with the user who created it and timestamp

## File Upload & Storage

Implement a file upload system, ensuring the PDF files are securely stored to the server

Associate the uploaded PDFs with specific audit records in the database

## Expiration Monitoring

Create a mechanism to regularly check the expiration dates of uploaded PDFs

Implement notifications to alert users when a PDF is about to expire -- 90, 60, 30, 15 day notifications

## User Perimissions 

Define user roles and permissions -- admin or regular user

Admin users may have the ability to create records and set expiration rules - regular users can upload or download PDFs and view the audit records

## Export Functionality

Develop an export feature that allows users to select audit records, export them as PDFs or excel documents, and download them

Optionally, allow users to select specific PDFs attached to audit records for export

## Security

Implement security measures to protect user data, audit records, and files

Use authentication and authorization to control access to the system - duo mobile and passwords

## User Interface Enhancements 

Enhance the UI for user-friendly navigation and a positive user experience

## Testing

Thoroughly test website to identify any issues

## Deployment 

Deploy website on the chosen hosting service and set up a production environment 

## Maintenance 

Regularly update and maintain website to ensure it remains secure and functional

Continuously monitor expiration dates -- send daily reports 

## Documentation & Support

Provide user documentation or tutorials to guide users how to use website

Office support channels for users who encounter issues or have questions -- issue ticket to Taylor
