# Group8_CSP584_Project

Total Lines of Typescript/Javascript/HTML/CSS/SCSS Code
8,145

Total Lines of Code All Files (including JSON and SQL)
17,142


Features Implemented that are Similar to Assignment Features

	-Assignment #1
		- Customer can schedule services online
		- Service providers can offer different types of services
		- Service providers can add and delete services they offer
		- Customers can schedule, reschedule, and cancel appointments
		- Services have a type and price
		- Customers can create an account
		- The customer pays for services performed using a credit card
		- Customers can schedule multiple services in the same session 
		- Customers can add/remove services from their cart in the same session
		- Customer enters their credit card when checking out. Other customer information needed for the order is retrieved from the database (PostgreSQL).
	
	-Assignment #2
		- All user login information stored in SQL database (PostgreSQL)
		- All transaction information stored in SQL database (PostgreSQL)
		- All services stored in SQL database (PostgreSQL)
		- All cart information stored in SQL database (PostgreSQL)
		- All location information stored in SQL database (PostgreSQL)
		- Appointment additions, updates, and deletions are reflected in SQL database
		- Customers can submit service reviews that have the following attributes: date, service_provider, customer, service, rating, review_text, and response
		- Service reviews are stored in MongoDB
		- Scheduled appointments have the following attributes: dayserviceperformed, servicestarttime, serviceendtime, serviceprovider, customer, servicecost, amountdue, service, streetaddress, city, state, and zipcode
		- Users can see data that includes: highest rated service providers, services with highest number of appointments, and services with highest revenue
	
	-Assignment #3
		- Service providers can see all previously provided services in a table
		- Bar charts are provided for number of pervious appointments per month, number of pervious appointments per service, and revenue per pervious month
		- Service providers can see number of upcoming appointments by day in a table and in a line chart
		- Service providers can view upcoming appointments in a table
		- Bar charts are provided for number of future appointments per month, number of future appointments per service, and revenue per future month
		- Customers can see all previously received services in a table
		- Bar charts are provided for number of pervious appointments per month, number of pervious appointments per service, and cost per pervious month
		- Customers can view upcoming appointments in a table
		- Bar charts are provided for number of future appointments per month, number of future appointments per service, and cost per future month
		- Search auto-completion used for searches for service providers by type on the home screen
		
	-Assignment #4
		- Node.js/Express used for the back-end application server
		- PostgreSQL and MongoDB used to store and retrieve data
		- Google Maps used to plot data for geospatial queries
		- When users search for service providers, they see all service providers within a 15 mile radius that are in the category searched by the user 
		- Angular used to create the front-end application
		- Users search for service providers by category either using a dropdown or a text input field
		- A google map is shown with the service providers in the requested category so users can see where the service providers are located
		- A bar chart is provided for the yelp reviews of the service providers in the searched category

Instructions to Deploy and Run Project
1. Install PostgreSQL if you do not have it (PostgreSQL 13.8 was used in developing this application)
2. Install MongoDB if you do not have it (MongoDB version 5.0.13 was used in developing this application)
3. Install Node.js if you do not have it (Node.js version 16.18.0 was used in developing this application)
4. Install Angular if you do not have it (Angular CLI 14.0.0 was used in developing this application)
5. Check that PostgreSQL server is running in Services
6. Open PG Admin
7. Create Home_Hub_App database in PG Admin
8. Open the tables.sql file in the Home-Hub-App folder and execute it in the Home_Hub_App database in PG Admin
9. Open the table-input.sql file in the Home-Hub-App folder and execute it in the Home_Hub_App database in PG Admin
10. Check that MongoDB server is running in Services
11. Open MongoDBCompass
12. Create Group8_CSP584_Project database in MongoDBCompass
13. Create businessdatas collection in MongoDBCompass
14. Create businessreviews collection in MongoDBCompass
15. Add data from businessdatas JSON file in the Backend-Yelp-Reviews folder to businessdatas collection in MongoDBCompass
16. Add data from businessreviews JSON file in the Backend-Yelp-Reviews folder to businessreviews collection in MongoDBCompass
17. Go to Backend folder in Home-Hub-App in the directory
18. Enter node server
19. Go to Frontend folder in Home-Hub-App in the directory
20. Enter ng serve
21. Go to http://localhost:4200/