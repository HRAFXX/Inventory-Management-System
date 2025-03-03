(important read 6.Installation and Setup)
1. Project Overview
The Inventory Management System is a web-based application designed to help businesses manage their inventory efficiently. It allows users to add, edit, delete, and view products, track transactions, and generate reports. The system is built using Flask (Python) for the backend, MongoDB for the database, and Bootstrap for the frontend.

2. Key Features
The system provides the following features:
2.1 Product Management
•	Add Product: Users can add new products with details such as name, quantity, price, and category.
•	Edit Product: Users can update product details.
•	Delete Product: Users can remove products from the inventory.
•	View Products: Users can view a list of all products in the inventory.
2.2 Client Management
•	Add Client: Users can add new clients with details such as name, email, phone, and address.
•	Edit Client: Users can update client details.
•	Delete Client: Users can remove clients from the system.
•	View Clients: Users can view a list of all clients.
2.3 Order Management
•	Add Order: Users can create new orders with details such as supplier name, product ID, quantity, order date, and status (Pending/Delivered).
•	Edit Order: Users can update order details.
•	Delete Order: Users can remove orders from the system.
•	View Orders: Users can view a list of all orders.
2.4 Reporting
Users can generate a Product Report in PDF format, which includes details of all products in the inventory.
2.5 User Authentication
Admin login functionality is implemented to restrict access to authorized users only.

3. Technologies Used
Frontend
•	HTML5: For structuring the web pages.
•	CSS3: For styling the application (custom styles and Bootstrap).
•	Bootstrap: For responsive design and pre-built components.
Backend
•	Flask (Python): For handling server-side logic and routing.
•	MongoDB: For storing product and transaction data.
•	FPDF: For generating PDF reports.

4. Project Structure
Frontend Files
•	index.html: Dashboard page with navigation links.
•	add_product.html: Form to add new products.
•	edit_product.html: Form to edit existing products.
•	view_products.html: Displays a list of products with search functionality.
•	add_client.html: Form to add new clients.
•	edit_client.html: Form to edit existing clients.
•	view_clients.html: Displays a list of clients.
•	add_order.html: Form to add new orders.
•	edit_order.html: Form to edit existing orders.
•	view_orders.html: Displays a list of orders.
•	search_product.html: Displays search results for products.
•	landing.html: Landing page with a "Get Started" button.
•	login.html: Admin login page.

Backend Files
•	app.py: Flask application with routes for handling requests (e.g., adding products, editing products, generating reports).

Database
MongoDB Collections:
•	products: Stores product details (name, quantity, price, category).
•	clients: Stores client details (name, email, phone, address).
•	orders: Stores order details (supplier name, product ID, quantity, order date, status).
•	admins: Stores admin credentials (username and password).
•	suppliers: Stores supplier details (name, contact information, address, etc.).

5. How It Works Admin Login
Admins log in using their credentials (username: admin, password: admin123).
Unauthorized users are redirected to the login page.
Dashboard
•	After logging in, admins are directed to the dashboard, where they can:
•	Add, view, edit, and delete products.
•	Add, view, edit, and delete clients.
•	Add, view, edit, and delete orders.
•	Generate product reports.

Product Management
•	Admins can add, edit, or delete products.
•	Products are stored in the products collection in MongoDB.
Client Management
•	Admins can add, edit, or delete clients.
•	Clients are stored in the clients collection in MongoDB.
Order Management
•	Admins can add, edit, or delete orders.
•	Orders are stored in the orders collection in MongoDB.
Search Functionality
•	Admins can search for products by name in the View Products page.
Reporting
•	Admins can generate a PDF report of all products in the inventory.

6. Installation and Setup
To run the project locally, follow these steps:
Install Dependencies:
pip install Flask pymongo fpdf
Set Up MongoDB:
Install MongoDB and start the MongoDB server.
Create a database named inventory_db.
Run the Application:
python app.py
Access the Application:
Open your browser and navigate to http://localhost:5002.




