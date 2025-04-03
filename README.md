# ToolBox - E-commerce Web Application

ToolBox is an e-commerce web application built to provide users with an online platform for buying tools and related products. It allows users to browse products, manage orders, and perform administrative functions. Admins can manage products, categories, companies, and orders.

## Features

- **User Management**: Admins can view, manage, and update user roles and statuses.
- **Product Listing**: Users can browse tools like drills, hammers, saws, and more. They can also view detailed information and add products to their cart.
- **Order Management**: Users can place orders, and admins can manage the status of orders (pending, completed, etc.).
- **Payment Integration**: Stripe is integrated for processing payments.
- **Admin Portal**: Admins can manage products, categories, users, companies, and orders.

## Technologies Used

- **Languages**: C#, HTML, CSS, JavaScript
- **Frameworks**: ASP.NET, Bootstrap v5
- **Database**: MySQL
- **Tools**: 
  - Microsoft Visual Studio
  - XAMPP (for local development)
  - Canva (for design)
  
## Setup Instructions

### Prerequisites

- **.NET SDK**: [Install .NET](https://dotnet.microsoft.com/download)
- **XAMPP**: [Install XAMPP](https://www.apachefriends.org/index.html)
- **MySQL Database**: Set up your MySQL server.

### Clone the Repository

```bash
git clone https://github.com/yourusername/ToolBox.git
cd ToolBox
Set up the Database
Open XAMPP and start MySQL.

Create a new database toolbox_db in MySQL.

Configure the Application
Open the solution in Visual Studio.

Update appsettings.json to configure your database connection.

json
Copy
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=toolbox_db;User=root;Password=;"
  }
}
Build and run the application in Visual Studio.

Running the Application
Start the application from Visual Studio and open it in a browser at http://localhost:5000.

Features
User Section
View Products: Browse through different tools and products available for purchase.

Add to Cart: Add selected products to the cart.

Order Summary: View an order summary and make a payment using Stripe.

Account Management: Users can register, login, and view their orders.

Admin Section
User Management: View, update or delete users and modify their roles.

Product Management: Add, update, or remove products.

Category Management: Add or edit categories for tools.

Order Management: View and update order statuses.

Screenshots




Contributing
Fork the repository

Create your feature branch (git checkout -b feature-name)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature-name)

Open a pull request

License
This project is licensed under the MIT License - see the LICENSE file for details.

Team Members
Adibul Haque - 20200204029

Yousuf Ali - 20200204037


csharp
Copy

### How to Use:
- Replace the placeholder repository URL `https://github.com/yourusername/ToolBox.git` with the actual URL of your GitHub repository.
- Add the images or replace the paths under the "Screenshots" section with the appropriate ones.
  
This README provides a clean, concise overview of your project, setup instructions, and how users or developers can
