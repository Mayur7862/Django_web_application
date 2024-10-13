# Django_web_application

This a Django application project to manage service requests for a gas utility company.

# Gas Utility Service Request Management

This Django application allows customers of a gas utility company to submit and manage service requests online. It provides a user-friendly interface for customers to track their requests and for customer support representatives to manage and resolve them effectively.

## Features

- User Authentication: Secure login and registration for customers and support staff.
- Service Requests: Customers can submit various types of service requests with details and file attachments.
- Request Tracking: Users can track the status of their submitted requests.
- Customer Support Dashboard: Tools for support staff to manage and resolve customer requests.
- Email Notifications: Customers receive updates on the status of their requests (to be implemented).

## Getting Started

### Installation

1. Clone the repository:

   git clone https://github.com/yourusername/gas-utility-service.git
   cd gas-utility-service

2. Create a virtual environment:

   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install the required Packages:

   pip install Django

4. Apply migrations:

   python manage.py makemigrations
   python manage.py migrate

5. Create a superuser:

   python manage.py createsuperuser

6. Run the development server:

   python manage.py runserver


Login: Use the credentials you created to log in.
Submit a Request: Navigate to the "Submit Request" page to create a new service request.
View Requests: Go to the "View Requests" page to track the status of your submitted requests.
