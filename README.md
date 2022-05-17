## Expense Reimbursement System-ERS


## Executive Summary
The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

## Technical Requirements
The back-end system shall use JDBC to connect to a Postgres database. The middle tier shall use Javalin technology for dynamic Web application development. The front-end view shall use HTML/CSS/JavaScript to make an application that can call server-side components in a generally RESTful manner. The middle tier shall follow proper layered architecture, and have EITHER 10 JUnit tests or 10 logs. Webpages shall be styled to be functional and readable.

* Stretch Goals:

Managers can:

* View all users
* Edit user information
* Delete users
* Add new users
* View all reimbursement requests
* Approve or deny a request

Users can:
* All users can login using their username and password


## Environment / Technologies Used

* Java version 1.8
* JDBC 
* SQL(Postgres) version 42.3.3
* CSS/HTML 5
* Bootstrap 
* JavaScript 
* JUnit version 4.12
* Log4J version 2.17.1
* Javalin version 4.4.0


## Features
List of features ready and TODOs for future development:

* Users can login and be redirected to a employee or manager homepage based on credentials.
* Postgres Database shall be hosted remotely on an AWS RDS.
* Employees must select the type of reimbursement as: LODGING, TRAVEL, FOOD, or OTHER.
* Managers can view employee reimbursement requests by employee ID or by request status(pending/resolved)
* Managers can approve or decline employee reimburement requests

To-do list:

* Provide additional CSS formatting for improved look (Boostrap).
* User can upload a reciept for review.

## Getting Started

* Git Clone ---> https://github.com/melbmar/Expense-Reimbursement-System.git
* To get started use the provided SQL Script to populate your RDS with the appropriate tables and information.


## Usage / Web Home Login

The starting view for the application should be the login page and with the link similar to http://localhost:8081/employeereimbursementsystem.html dependent on the local host port and look like the following.

Use the information from the "Users" Table to sign in as an Employee(role_id = 1) or as a Manager(role_id = 2). After successful login the top navigation bar is used to navigate between views and features.

Web Home Login
<img width="1160" alt="Screen Shot 2022-05-12 at 7 08 49 PM" src="https://user-images.githubusercontent.com/102433425/168192943-c3dfbd29-9d7d-43cf-8448-1000221657e3.png">


## Contributors
In order to see this project in action, you will need a few things:
* Be sure to have Spring ToolsSuiote4 installed.
* Be sure to have the Java 8 runtime environment installed.
* DBeaver (Postgres)
* All maven dependecies installed.
* Visual Code Installed.

## License
This project uses the following license: Melba Sanchez (me!) <https://github.com/melbmar> for Revature <https://revature.com/>


