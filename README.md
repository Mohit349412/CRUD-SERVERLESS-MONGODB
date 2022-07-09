# CRUD-SERVERLESS-MONGODB
Dishes app with Azure Functions and MongoDB

Please follow this document to create Dishes application with Azure Functions and integrated with MongoDB and Node.js

# Dependencies - 
	• Install Azure Functions Core Tools package -  
	This will allow you  to create and test this app locally your machine from a terminal or command prompt.
	• **Tools used program used.**
		○ Visual Studio Code
		○ Node.js – LTS
		○ Azure Functions Core Tools
		○ Postman
		○ MongoDB Community Server
	• **File Structure and Significance - **
		○ Package.json - dependency management
		○ Shared/mongodb -  connection to mongo DB
		○ **Azure functions** - 
			○ **CreateDish**
				○ function.json: for routes and endpoint methods.
				○ index.json: for endpoint logic.
			○ **GetAllDishes**
				○ function.json: for routes and endpoint methods.
				○ index.json: for endpoint logic.
			○ **getAllDishesByID**
				○ function.json: for routes and endpoint methods.
				○ index.json: for endpoint logic.
			○ **updateDishbyid**
				○ function.json: for routes and endpoint methods.
				○ index.json: for endpoint logic.
			○ **DeleteDishById**
				○ function.json: for routes and endpoint methods.
				○ index.json: for endpoint logic.
# Steps to reproduce -
**npm install -g azure-functions-core-tools **
**Install node dependency - npm install **
** Start the server - func host start**
![image](https://user-images.githubusercontent.com/81349135/178112917-ddc541f5-8dc6-486a-b68a-0d8a5d0622f4.png)

