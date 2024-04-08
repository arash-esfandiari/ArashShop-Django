# ArashShop E-commerce Webapp

This documentation included an introduction to ArashShop webapp, the languages
and frameworks used in the project, and a brief walkthrough of the application.

## About

ArashShop webapp has been written as a base e-commerce React-Django template. It has been
modified and used as the base of 3 e-commerce websites so far and has proven very effective,
robust, scalable, and highly secure.

## Deployment

-   Deployed on Sales Force's Heroku
-   PostgreSQL securely deployed on AWS RDS

## Frameworks

This project is written on top of Django Python, state management using Redux, and frontend using React and JavaScript.

### Installed libraries:

    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',

    'rest_framework',
    'corsheaders',
    'storages',

    'base.apps.BaseConfig',

### Security

    JWT,
    rest_framework_simplejwt.authentication.JWTAuthentication,
    django.middleware.security.SecurityMiddleware,

    and more...

## Features

-   Product catalogue
-   Account creation
-   Secure login using JSON Web Tokens
-   Admin user panel - control users, add and remove porducts, and more...
-   Save user data on account
-   Secure checkout and payment options (Paypal, Visa, Mastercard)
-   Check the status of your order on account
-   Comment on products
-   Write a review on products
