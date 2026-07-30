# Library Management System
1. Requirements Solved Using Flow
Automatically set the Issue Date when a new Book Issue record is created.
Send an email notification to the librarian when a book is issued.
Automatically create a Fine record for overdue book returns.
________________________________________________________________________
2. Requirements Solved Using Validation Rules
Prevent Issue Date from being after Due Date.
Prevent Return Date from being before Issue Date.
Ensure mandatory fields are not left blank.
Prevent Available Copies from being less than zero.
________________________________________________________________________
3. Requirements That Needed Apex
Prevent issuing a book when no copies are available.
Handle complex business logic and future enhancements, such as advanced fine calculations or integrations.
________________________________________________________________________
4. Why These Solutions Were Chosen
Flow was used to automate repetitive business processes without writing code.
Validation Rules were used to maintain data quality by preventing invalid records from being saved.
Apex was chosen for scenarios requiring complex logic and greater flexibility beyond declarative automation.
