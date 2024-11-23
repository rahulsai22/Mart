# Kabadimart

## Project Overview
**Kabadimart** is a dynamic web application designed to facilitate the selling and management of scrap materials. The platform enables seamless interactions between vendors, customers, and admins, each with tailored modules for specific functionalities. The system provides an easy-to-use interface for scrap management and price listing, enabling vendors to list scraps, customers to purchase, and admins to oversee the entire process.

## Features

- **User Roles**:  
  The platform includes three primary roles, each with its own set of functionalities:
  - **Admin**: Manages users, scrap categories, and oversees the overall system.
  - **Vendor**: Can list scrap materials, manage their listings, and track sales.
  - **Customer**: Can browse and purchase scrap materials from vendors.

- **Dynamic Price Listings**:  
  - The web application supports dynamic pricing for different scrap materials based on categories.
  - Prices can be adjusted by the admin, allowing flexibility in pricing management.

- **Responsive Design**:  
  - The web application is designed to be responsive, offering an optimal user experience on both desktop and mobile devices.

- **User Authentication**:  
  - Users can securely register and log in to access the platform.  
  - Vendors and admins can manage their profiles and listings through the application.

- **Scrap Management**:  
  - Vendors can upload and update scrap listings with prices and availability.
  - Admins have control over scrap categories and prices across the platform.

---

## Technologies Used

- **Frontend**:  
  - HTML5, CSS3, JavaScript (for dynamic content and interactivity)
  - Bootstrap (for responsive design)
  - jQuery (for DOM manipulation)

- **Backend**:  
  - Python with Flask (for web server and APIs)
  - SQLite (for lightweight database storage)

- **Authentication**:  
  - Flask-Login (for user authentication and session management)

- **Deployment**:  
  - Deployed on a cloud platform (e.g., Heroku, DigitalOcean) for real-time access.

---

## Installation

### Prerequisites
- Python 3.x
- pip (Python package installer)
- SQLite (Database for local storage)
- HTML,CSS and Javascript

### Steps to Run the Application Locally

1. **Clone the Repository**:  
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/<your-username>/Kabadimart.git
   cd Kabadimart
