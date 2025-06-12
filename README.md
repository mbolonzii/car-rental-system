# Elite Car Rental System

 A web-based Car Rental System built with ***Python*** and ***Flask***, designed to simplify the management of car reservations, customers, vehicles, and rental transactions. This application is ideal for small to medium-sized rental agencies looking for an easy-to-use and extensible system.

## Features

- User authentication (Admin and User roles)
- Car inventory management
- Customer profile management
- Booking and rental history tracking
- Real-time availability and return status
- Admin dashboard with analytics
- RESTful API for integration

## Tech Stack

**Backend**: Python, Flask.  
**Frontend**: HTML, CSS, JavaScript.  
**Database**: SQLite

## Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Installation

```bash
git clone https://github.com/yourusername/car-rental-system.git
cd car-rental-system
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt.  
```

### Run the Application

```bash
flask db init
flask db migrate
flask db upgrade
flask run
```
