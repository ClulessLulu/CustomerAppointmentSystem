Title: Customer Appointment Management System Application [C195: Software 2 - Advanced Java Concepts]

Purpose: This application provide users with access to a pre-existing database, and gives them the ability to schedule appointments for customers.

Application Version: Version 1.0

Date: 07/23/2022

Author: Crystal Lu

Student ID: 001270396

IDE Version: Intellij IDEA Community Edition 2021.1.3 x64
JDK Version: JDK Version 17.0.7
JAVAFX Version: JavaFX Version 17.0.7
MySQL Connector Driver Version Number: mysql-connector-java-8.0.25

Directions: 
1) Launch program. 
2) Enter a vaild username and password into text fields then hit the login button.
3) An upcoming appointments alert will pop up, acknowledge alert to continue.
4) From the main appointments screen, click either Customers, Reports, or Logout to navigate the around the application.

 Main Appointment Menu: Displays all appointments scheduled from the database. The user can add, modify, or delete exisiting appointments.
 - Search by Date: Enter a date to locate customer appointments ofr that date.
 - View All Radio Button: Generates all customer appointments.
 - View by Month Radio Button: Generates all customers appointments for the month. 
 - View by Week Radio Button: Generates all customer appointments for the week.
 - Add Appointment Button: Clicking the add button will take you to the add appointment menu screen where you fill the out the fields provided. If the fields are missing information an error alert will generate. 
	Once fields are completed, clicking save will take you back to the main appointment menu where the table is repopulated with the newly added appointment.
 - Modify Appointment Button: Must select an appointment to modify from table. An alert will pop up if an appointment is not selected. 
	Once an appointment is selected then you will be takened to the modify appointment menu where you can edit the appointment. 
	Information from that modify appointment menu must be filled or an error alert will display to correct error. 
	Clicking save will take you back to the appointment menu and will repopulate the table with the updated appointment information. 
 - Delete Appoimtment Button: Must select an appointment from the table to delete. A confirmation alert will pop up for confirming deletion, once accepting appointment gets deleted and the table repopulate the new information.
 - Logout Button: licking logout will generate a confirmation to confirm log out. Accepting confirmations will then take you back to the login menu.


 Customer Record Menu: Displays all customers the database. The user can add, modify, or delete exisiting customers.
 - Search Customer ID/Name Text Field: Enter customer ID or Name and the table will locate them in the table.
 - Add Customer Button: Clicking the add button will take you to the add customer menu screen where you will fill out the fields provided. If the fields are missing information an error will generate.
	Once the fields are completed, clicking save will take you back to the main customer menu where the table is repopulated with the newly added customers.
 - Modify Customer Button: Must select an customer to modify from table. An alert will pop up if an customer is not selected. 
	Once an custromer is selected then you will be takened to the modify customer menu where you can edit the appointment. 
 - Delete Customer Button: Must select an customer from the table to delete. A confirmation alert will pop up for confirming deletion and inform you that any appointments assigned to customer will also be deleted. 
	Once accepting customer deletion, customer gets deleted and the table repopulates the new information.
 - Logout Button: Clicking logout will generate a confirmation to confirm log out. Accepting confirmations will then take you back to the login menu.
 
 Total Appointments Report: This report generates the total types of appointments and the month they are scheduled in.
 
 Contact Schedule Report: Must select a contact to display report. Once a contact is selected the the table generates a report showing all the appointments for that contact.

 Country Report: This report generates customers by country. You can select the country from the combo box to filter the customers from that country. The report then loads that customers from that country onto the report.
