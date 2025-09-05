# Amigos Cars Showroom

Amigos Cars Showroom is a web-based management system built in Python for efficiently handling the operations of a car showroom. The platform allows customers to explore a curated collection of available vehicles, filter cars by brand, color, fuel type, and other specifications, and complete purchases securely. Administrators benefit from robust tools for managing vehicle inventory, tracking sales, and overseeing employee information.

## Features

- **Vehicle Browsing & Filtering:** Customers can browse the complete inventory, filter cars by brand, model, color, petrol type, doors, transmission, and year, and view detailed car information including features and options.
- **Car Purchase Workflow:** Secure purchase flow with customizable payment methods. Transaction details, including the customer and employee involved, are recorded.
- **Admin Dashboard:**
  - Add, update, or remove vehicles from the showroom.
  - View and manage all cars, including status (available, sold, not available).
  - Track and view sold cars, including customer and transaction details.
  - Duplicate vehicle entries and update car statuses.
  - Manage employee records and statuses.
- **Customer Management:** Stores and displays customer information linked to each sale.
- **Security:** Login and admin access control to sensitive routes and actions.
- **Database Integration:** Uses MySQL for robust data storage and querying.

## Technologies Used

- Python (Flask)
- MySQL
- HTML/CSS/JavaScript (Bootstrap for UI)
- Jinja2 Templating

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ahmad-K-Hamdan/Amigos-Cars-Showroom.git
   cd Amigos-Cars-Showroom
   ```
2. **Set up the virtual environment and dependencies.**
3. **Configure your MySQL database** using the provided schema and connection settings.
4. **Run the application:**
   ```bash
   python app.py
   ```

## Screenshots

- Homepage with luxury vehicle highlights and search.
- Inventory and sold cars management dashboards.
- Detailed car purchase and payment flow.
