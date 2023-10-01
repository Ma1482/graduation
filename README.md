
# Erb Management System 

The Coffee Management System API is a comprehensive backend system that handles various aspects of coffee shop management. This API is designed to support four main industries within the coffee business:

1. **Authentication**: Manage user authentication, user roles, and provide JWT (JSON Web Tokens) for secure access.

2. **Financials**: Keep track of costs, benefits, calculate net profit, manage shift benefits, and update order total prices on benefits for users.

3. **Human Resources**: Handle employee management, including worker details, salaries, deductions, attendance, and leaving records. Track shift start and end times, as well as customer data.

4. **Sales**: Manage orders, order items, menus, categories, and table assignments to streamline the coffee shop's daily operations.

## Features

### Authentication

- **User Management**: Create and manage user accounts with different roles, such as admin, staff, and manager.
- **JWT Authentication**: Securely authenticate users and generate JWT tokens for API access.
- **User Roles**: Assign specific permissions and access levels based on user roles.
   - #### Roles included in our project: Admin, User.  

### Financials

- **Cost Tracking**: Record and manage various costs incurred in the coffee shop allow user to add costs during his shift.
- **Benefits Management**: Monitor benefits and profits over time bt calculating ptofits, costs and net profits.
- **Net Profit Calculation**: Automatically calculate net profits by subtracting costs from benefits.
- **Shift Benefits**: Track benefits specific to each shift by adding the benefits oll orders processed in that shift.
- **Order Total Updates**: Automatically update order total prices based on menu items and quantities.

### Human Resources

- **Employee Management**: Maintain employee records, including personal information, salary and contact details.
   - #### Note that we provied some epmloyees with user accounts, only the ones respnsible for shifts. 
- **Salary Management**: Record and manage employee salaries, and deductions.
- **Attendance Records**: Keep track of employee attendance and leaves times.
- **Shift Management**: Record user shift start and end times for employees.
- **Customer Data**: Store customer information and preferences for better service.

### Sales

- **Order Management**: Create and manage customer orders.
- **Order Items**: List and customize order items, including menu items, quantities, and prices.
- **Menu and Categories**: Organize menu items into categories for easy access.
- **Table Management**: Assign tables to orders for efficient service.

## Entity Relationship diagram 
[![cafe-ERD.png](https://i.postimg.cc/VNDsKpp0/cafe-ERD.png)](https://postimg.cc/JyHWn61R)Here is a diagram that illustrates the overall system architecture of the Coffee Management System API.


### Technologies Used

**Backend:**
- Django: The backend framework used for building the API.
- Django Rest Framework (DRF): An extension for Django that simplifies building RESTful APIs.
- JWT Authentication: JSON Web Tokens are used for secure user authentication.
- PostgreSQL: The relational database management system used to store data.
- Python: The programming language in which the application is developed.
- Git Terminal: Version control system for tracking changes in the project.
- ngrok
- Postman

**Frontend:**
- Vue3
- Tailwind CSS: A utility-first CSS framework for designing user interfaces.
- Axios: A promise-based HTTP client for making API requests.
---
## Contributors

**Backend:**
-Meanna allah Mahmoud 20-00689
-Nansy saad  20-01336
~Arwa Sayed 20-01485
-Mahmoud Abd Alghany 20-01274
-Hassan Abo Elghet 20-01197

**Frontend:**
- Marwan Maher 20-02008
- Nada Hamada  20-00684 GPA :2.97
---
