IndianBazaar: E-commerce Platform

Description
Developed IndianBazaar, a comprehensive e-commerce platform with Angular and .NET Core, featuring product filtering, user authentication, and secure payment processing.

Installation Instructions
1. Clone the Repository:
	git clone https://github.com/yourusername/indianbazaar.git

2. Navigate to the Project Directory:
	cd indianbazaar

3. Install Backend Dependencies:
	cd backend
	dotnet restore

4. Install Frontend Dependencies:
	cd ../frontend
	npm install

5. Setup the Database:
Ensure MSSQL Server is running.
Update the connection string in appsettings.json.
Run migrations:
	cd backend
	dotnet ef database update

6. Run the Application:
Start the backend:
	cd backend
	dotnet run

Start the frontend:
	cd ../frontend
	ng serve

Usage
1. Access the Application:
	Open a browser and navigate to http://localhost:4200.

2. User Authentication:
	Register or log in to access the platform.

3. Browse Products:
	Use the filters and pagination to explore products.

4. Shopping:
	Add products to the basket, proceed to checkout, and complete the payment using Stripe.

Technologies Used
Frontend:
Angular
Bootstrap
TypeScript

Backend:
.NET Core
ASP.NET Core Web API
Entity Framework Core
MSSQL Server

Tools:
Visual Studio Code
Postman
Swagger

Features
Product listings with pagination
Filtering by brand/type
Basket and checkout system
Stripe payment integration
Admin dashboard for order management

Contributing Guidelines
1. Fork the Repository:
Click the Fork button in the repository's GitHub page.

2. Clone the Forked Repository:
	git clone https://github.com/yourusername/indianbazaar.git

3. Create a New Branch:
	git checkout -b feature/your-feature-name

4. Make Your Changes:
Implement your changes and commit them:
	git add .
	git commit -m "Detailed commit message"

5. Push the Changes:
	git push origin feature/your-feature-name

6. Open a Pull Request:
	Go to the original repository on GitHub and click on "New Pull Request".

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact Information
For any inquiries or feedback, please contact:
Sagar Hatagale
Email: sagar.hatagale.dev@gmail.com
GitHub: sagar-greatprogrammer
