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
