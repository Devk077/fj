# Django Expense Tracker

A web application for tracking expenses, built with Django.

## Environment Variables

This project uses environment variables to securely store configuration. You need to create a `.env` file in the root directory with the following variables:

```
DEBUG=True  # Set to False in production
SECRET_KEY=your_secret_key
DATABASE_URL=your_database_url
GOOGLE_OAUTH_CLIENT_ID=your_google_client_id
GOOGLE_OAUTH_SECRET=your_google_secret
```

## Setup

1. Clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Create `.env` file with required variables (see above)
6. Run migrations: `python manage.py migrate`
7. Start the development server: `python manage.py runserver`

## Features

- Expense tracking and management
- User authentication and authorization
- REST API endpoints
- Google OAuth integration
- Responsive design 