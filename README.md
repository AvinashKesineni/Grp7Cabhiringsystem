# Grp7Cabhiringsystem
TITLE: CAB HIRING SOFTWARE
About the project: 
To develop a Cab Hiring application that will help the users to book a cab or taxi and enables the company to make their services available to the public through the internet and also keep records about their services. 
The purpose of the project is to build an application program to reduce the manual work for managing the Car, Payment, Booking, Customer. It tracks all the details about the Customer, Supplier, Insurance.

Stake Holders:
1) Admin
2) Customers
3) Employee
4) Dealers and suppliers



Modules:
•	 Signup
•	Email verification
•	Welcome page sent through the mail
•	 Customer Login 
•	Employee login
•	 Admin Login
•	 Drivers Information
•	 Car Information
•	 Check Availability of cars
•	 Booking
•	 Booking history
•	 Payment
•	Receipt
•	 Support
•	 Testimonial 
•	 Updating profile
•	Sitemap

Tables:
1.	Users (Master Table): It contains details of all the registered users or customers.
2.	Booking (Transaction Table and Master Table): It contains booking details for each ride by the customer
3.	Vehicles (Transaction Table and Master Table): It contains all the details of vehicles.
4.	Drivers (Transaction Table and Master Table): It contains all the details of drivers who are working.
5.	Testimonial (Transaction Table and Master Table): contains the reviews that are submitted by users
6.	Admin (Master Table): contain all the details of the administrator
7.	Locations (Master Table): contain all the details of locations that current service available.
8.	Payment (Transaction Table and Master Table): contain all the details of locations that current service available.




Reports:
1.	User Report: Contains details of a number of rides by the user.
2.	Employee Report: Contain details of role and salary of the employee.
3.	Booking Report: contains the entire detail of each ride.
4.	Testing Report: Include details of errors of modules that are not working fine.
Assumptions 
1. Admin panel – Administration purpose to control the entire application.
2. Payment gateways – To allow UPI transactions, wallet 
3. Discounts / Coupon codes / Referral codes
4. Show nearby vehicles based on location
5. There is no fine for late-arriving or dropping late for the driver
6. Development of Mobile application.

Requirements
a. User--Customer (Add/Delete/Modify/Update)
1.	Registration
2.	Email verification
3.	Forgot Password
4.	Search Location
5.	Select Vehicle
6.	Book rides
7.	Payment
8.	Receipt
9.	Feedback
10.	Customer Care
b. User – Employee (Add/Delete/Modify/Update)
1.	Registration
2.	Accept / cancel Rides
c. User – Admin (Add/Delete/Modify/Update)
1.	Manage Employee
2.	Manage Booking of Rides
3.	Support Centre
4.	Manage Testimonial 
Software:
Visual Studio, Agile (Jira), Xaamp , PHP My Admin Panel, Android Studio, firebase for back end
Hardware:
PC of 8 GB Ram with i7 processor, server of 16 GB ram, 2 TB storage, and intel 6 core Processor

USER STORIES:
REGISTRATION:-
•	CUSTOMER REGISTRATION
o	As a customer, I would like to have a separate registration form for customers.
Tasks:
1.	Implement PHP  Registeration Form for Customer Registeration
2.	Passwords should be of at least 6 characters with 1 number, 1 uppercase letter, 1 lowercase letter, one special character.
3.	We will implement the details like username, Email ID, DoB, Phone number, password, and confirm the password for registration.
4.	We will implement a function to check if the username entered already exists in the system -error message "Username taken -please enter another username".
5.	Create SQL Scripts to create tables
6.	Create SQL Scripts for Storing Registration Information


•	EMPLOYEE REGISTRATION:
o	As an employee, I would like to have a separate registration form for employees.
Tasks:
1.	Passwords should be of at least 6 characters with 1 number, 1 uppercase letter, 1 lowercase letter, one special character.
2.	We will implement the details like username, Email ID, DoB, Phone number, password, and confirm the password for registration.
3.	We will implement a function to check if the username entered already exists in the system -error message "Username taken -please enter another username".
4.	A warning will be displayed if the password and confirm password do not match.
5.	Driver license will be verified to continue.
6.	There will be a separate UI for driver and customers






•	VALIDATION:
o	As a customer, I want to get notified whenever I entered incorrect details
TASKS:
1.	 Implement JS Validation in such a way that Passwords should be of at least 6 characters with 1 number, 1 uppercase letter, 1 lowercase letter, one special character.
2.	We will implement the details like username, Email ID, DoB, Phone number, password, and confirm the password for registration.
3.	We will implement a function to check if the username entered already exists in the system -error message "Username taken -please enter another username".
4.	A warning will be displayed if the password and confirm password do not match.
5.	We will implement a function in the Password field that calculates and displays the strength of the password.
6.	We will keep all fields as required data fields -an error alert will be shown if the user clicks on Submit with any of the fields left blank " cannot be empty".


•	EMAIL AND MOBILE VERIFICATION:
o	As a customer, I would like to verify my Mobile Number and Email during the registration process 
TASKS:
1.	After a user clicks on a sign-up button then a confirmation email is sent to the email given in the signup form.
2.	And Email should be valid otherwise warning message will be displayed.
3.	Users should confirm their email and click on the activation link to activate the account.
4.	User will get OTP to the number entered.
5.	If a user enters the wrong OTP he can use the resend option.
6.	After verifying both email and phone numbers, the user is directly logged into the website


•	GOOGLE / FACEBOOK REGISTRATION:
o	As a customer, I would like to make my registration easier, by registering through Google or Facebook.
Tasks:
1.	User can register through their google account
2.	User can register through their Facebook account
3.	


LOGIN AUTHENTICATION
ADMIN LOGIN
•	FORGOT PASSWORD:

o	-As a customer, I should be able to change my password if I forgot my old password
                 Tasks:
1.	Implement PHP form for forgot password page and Change password page
2.	Username/email  is taken as input 
3.	Create Sql queries for retrieving information of user email/name	
4.	Link for changing the password is generated through PHP and sent to email
5.	Create SQL Scripts to Update Table and Stored procedures
6.	Implementation of redirecting to login page after password is changed    

		
		VALIDATION
                    Tasks:
1.	Implement PHP form for login page
2.	Create Sql queries for retrieving information of user credentials
3.	Implement PHP code for Validation of credentials whether they are correct or not
4.	implement 
5.	
6.	Implement  redirecting to registration page if mail/username not exists
				
		2 STEP AUTHENTICATION
		       Tasks:
	    1)Implement an input field to enter OTP using  HTML/CSS/JS 	    
	    2) Implement JS Code for  Generating a random 4 digit number  
	    3) Create an SQL query to insert a 4 digit number into a database.
	    4)Implement a PHP code to send OTP using mail.
	    5) ”OTP has been successfully sent” a message should be displayed
	    6)Implement a PHP code to validate the OTP and redirect to home page
      

	LOCK ACCOUNT AFTER TOO MANY FAILED ATTEMPTS
1)Implement PHP code to track no of invalid login attempts.
2)After certain attempts, the login button should be disabled using PHP.
3)” Your account is locked Pls try again after some time” a message should be displayed on top of the page.
4)A timer should be displayed using HTML/CSS.
5)The login button should be enabled after a timeout.
6)After successful login user will be redirected to the Home page

		***EACH TIME AN USER LOGINS AN EMAIL WITH TIMESTAMP AND DATE WILL BE SENT TO MAIL

	USER LOGIN
	FORGOT PASSWORD
	VALIDATION
	2 STEP AUTHENTICATION
LOCK ACCOUNT AFTER TOO MANY FAILED ATTEMPTS

DATE TIMESTAMP THROUGH EMAIL
1)Implement a PHP code to get a timestamp and date.
2)Send an email to the user with a timestamp and date each time they logs in.
3)

BOOKING
	CHECK AVAILABILITY
  Tasks:
		1)Create a SQL query to get all cars based on location 
		2)Display availability of cars based on location and model of cars
		3)Implement google maps api to find available cars based on current user location.
 		4)Users can select from available cars using PHP,google maps api.
 		5)Display Estimated time ,amount,distance by using PHP/HTML/CSS
		6)Notify driver about ride details on successful booking

	CANCEL RIDE
  Tasks:
		1) After successfully booking a timer should be displayed using HTML/CSS .
		2)Until the timeout a cancel button should be displayed using HTML/CSS.
 		3)On clicking cancel button booking should be cancelled and create a SQL query to 		update changes
 		4)Redirect user to check availability page
		5)Notify driver on cancellation of ride
		6)Create a SQL query to update ride details in drivers table

	PICKUP / DROP LOCATION
  Tasks:
		1) Designing a block on the right side which consists of a map using HTML/CSS .
		2)Create a SQL query to get pickup and drop location
 		3)Pickup and drop locations should be shown with Pin icon 
		4)Location of  driver should shown with Car icon		
		5)On hovering the Pin Icon location details should be displayed
		6)On hovering the Car Icon details of car and driver should be displayed

	DRIVER LOCATION
  Tasks:
		1) 
		2)
 		3)
 		4)
		5)
		6)

	AVAILABLE OF RIDES FOR DRIVERS
  Tasks:
		1) 
		2)
 		3)
 		4)
		5)
		6)

TRANSACTION/PAYMENT
	DIFFERENT PAYMENT GATEWAYS
      Tasks:
		1)Implement PHP Form for Payment page 
		2)Implement HTML/CSS input fields for Credit Card 
 		3)Implement HTML/CSS input fields for Debit Card
 		4) Implement HTML/CSS  fields for Wallet payment
		5)Implement HTML/CSS  fields for Upi payment such as buttons  like paytm,Gpay,etc 
		6)create SQL scripts for storing procedures.
	GENERATION OF RECEIPT
		  Tasks:
		1)Creating Sql Scripts for Retrieving booking information
		2) Creating Sql Scripts for Retrieving payment information
 		3) Booking information such as cars, driver and location details should be displayed  
		4) Total payment should be displayed including discounts and waiting charges
		5) Implementation of HTML/CSS page to display receipt after Successful transaction
		6) Implementation of PHP/JS  Code for Sending PDF format of Receipt through Email
		
	SUPPORT
		  Tasks:
		1) Implement HTML/CSS Fields for Support Page
		2) ADD FAQs,Contact us, connect with us options
 		3) Implementation of chat box on FAQs 
 		4) Creating SQL Queries to retrieve Data from Tables
		5) Creating SQL Querires to Store Data to Tables
		6) 

	VALIDATION OF CREDIT/DEBIT CARD CREDENTIALS
	 Tasks:
		1)Implement HTML,CSS Input fields for cards
		2) Cut SVG icons and images for Cards
 		3) Displaying type of card on taking card number
 		4) Validity date dropdown should only give future dates.
		5)Implement JS Code to Validate card Credentials.
		6)create SQL scripts for storing procedures(Card numbers).

	COUPON CODES
		  Tasks:
		1) Create Sql  Tables for storing Coupon codes by admin
		2) Implement HTML/CSS Input fields for Coupon code input
 		3) Creating SQL Queries for Retrieving Codes Information
 		4) Implement JS Code for Validating Coupon Codes
		5) Creating SQL Queries for Updating Tables
		6) Implement HTML/CSS blocks for Describing coupon codes

PROFILE
	DRIVER
		PROFILE UPDATION
		BOOKING HISTORY
		POST A FEEDBACK
		MONTHLY INCOME
		MY FEEDBACK
		SIGN OUT
	USERS
		PROFILE UPDATION
  Tasks:
		1) Creating Sql Queries for retrieving information of profile table
		2) Implement HTML/CSS for displaying retrieved data
 		3) Implement HTML/CSS code for taking input of various fields 
 		4) Implement JS Code for Validation of given input
		5) Display reset and Save changes button for updating information
		6) creating Sql Queries to Update existing tables

		BOOKING HISTORY
  Tasks:
		1) Creating Sql Queries for retrieving booking information 
		2) Creating Sql Queries for retrieving Payment information 
 		3) Implement HTML/CSS For Displaying all list of cars booked
 		4) Rebook option also available to book the same ride
		5) Delete history option available to delete his/her history
		6) latest bookings will visible first

		POST A FEEDBACK
  Tasks:
		1) Implement HTML/CSS Filelds to create star based input field
		2) Implement HTML/CSS Fields to take text input from users
 		3) Creating SQL Queries for storing procedures
 		4) Creating SQL Queries to create Tables
		5) After entering the feedback he/she should press send message button 
		6) After clicking on send feedback will be visible in admin’s panel

		MY FEEDBACK
  Tasks:
		1) Creating SQL Queries for retrieving feedback information 
		2) There will be a separate feedback session where all the feedbacks from all users can be seen implemented using html and sql
 		3)Implement HTML/CSS Fields for displaying list of feedbacks
 		4) Feedbacks will be visible to the admin where admin can read and do changes according to
		5) User can manage his own feedbacks
		6) user can delete his/her own feedbacks using delete option 

		SIGN OUT
  Tasks:
		1) Sign out button implemented using HTML  
		2) And Using PHP user can logout from his account
 		3) And a message will be displayed to the user that successfully logged out.
 		4) And a login button is also displayed where users can login again
		5)
		6)

ADMIN PANEL
Dashboard
  Tasks:
		1) Design a page consists of block for each 1)registered users 2)Listed Cars 3)Total    Booking 4)Listed Brand 5)Feedbacks 
		2)Create a SQL query to get count of each function 
 		3)Using PHP display the count on the respective blocks designed
 		4)On clicking each block detailed information of that feature should be displayed
		5)Search function should be implemented and no of entries should be displayed
		6)Admin can edit the details and it should be updated in database using SQL queries
Manage Booking
  Tasks:
		1) Design a page which shows booking details of all the customers 
		2)For each attribute ascending/descending order should be implemented  
 		3)Search function should be implemented and no of entries should be displayed
 		4)Cancel button for each booking separately should be implemented to cancel    	 booking at any point of time
		5)On clicking vehicle attribute it should redirect to manage vehicle page 
		6)Previous and next buttons should be implemented to navigate entries
		7)Admin can edit the details and it should be updated in database using SQL queries
Manage Feedback
  Tasks:
		1) Design a page which shows booking details of all the customers 
		2)For each attribute ascending/descending order should be implemented  
 		3)Search function should be implemented and no of entries should be displayed
 		4)Active/Inactive button for each feedback separately should be implemented to post only relevant feedbacks
		5)Previous and next buttons should be implemented to navigate entries
		6)Admin can edit the details and it should be updated in database using SQL queries

Registered Users:
  Tasks:
		1) Design a page which shows registered users details.
		2)For each attribute ascending/descending order should be implemented  
 		3)Search function should be implemented and no of entries should be displayed
 		4)A dropdown menu to select no of entries to be displayed
		5)Previous and next buttons should be implemented to navigate entries
		6)Admin can edit the details and it should be updated in database using SQL queries
Reg Drivers
  Tasks:
		1) Design a page which shows registered users details.
		2)For each attribute ascending/descending order should be implemented  
 		3)Search function should be implemented and no of entries should be displayed
 		4)A dropdown menu to select no of entries to be displayed
		5)Previous and next buttons should be implemented to navigate entries
		6)Admin can edit the details and it should be updated in database using SQL queries

Post A Car
  Tasks:
		1)  Design a page to fill the details of the car 
		2)In basic information form Car title,Vehicle overview,Price per km,Model year,Seating capacity
 		3)In basic information Select brand and Select fuel type should be in drop down menu
 		4)In upload image form 5 images of the cars should be uploaded
		5)All the mandatory fields should be marked with red asterisk
		6)In Accessories form all the accessories should be implemented with checkboxes
		7)Save changes and cancel button should be implemented.
		8)After successfully changing a message should be displayed

Add new location
  Tasks:
		1) 
		2)
 		3)
 		4)
		5)
		6)



1.	As a user, I want to register by enrolling in my details.
2.	As a user, I want to log in with my username and password so that the system authenticates the registered and unregistered users.
3.	As a user, I need to have a quick search to show all the nearby cabs in my location.
4.	As a user, I want to know the details of the car and driver.
5.	As a user, I need to get frequent rides while searching.
6.	As a user I want to pay payment using cash, wallet, Credit/Debit cards, UPI gateway, etc;
7.	As a user, I need to get appropriate fares for rides.
8.	As a user, I need to get payments in a specific period (1 month)
9.	As a user, I can cancel the ride within a certain time.
10.	As a user, I need to get the location details of the source and destination of the user.

