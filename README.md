# Neobis_DjangoGirls_Project

This is a web application created as part of the Django Girls tutorial, which is designed to teach beginners how to build a simple web application using Django.
## Features

    - A homepage that displays a list of blog posts
    - An "About" page that provides more information about the website
    - A "Contact" page that allows users to send messages to the website's administrators
    - A "New Post" page that allows authenticated users to create new blog posts

## Installation

To install and run this project locally, follow these steps:

Clone the repository:

    $ git clone https://github.com/MIA1kl/Neobis_DjangoGirls_Project.git

Navigate into the project directory:

    $ cd mysite

Create and activate a virtual environment:

    $ python3 -m venv env
    $ source env/bin/activate

Install the project dependencies:

    $ pip install -r requirements.txt

Set up the database:

    $ python manage.py migrate

Start the development server:

    $ python manage.py runserver

***Access the application at http://localhost:8000/***

## Usage

To use this application, follow these steps:

    - Navigate to the homepage at http://localhost:8000/.
    - Browse the list of blog posts.
    - Click on a blog post to view its details.
    - Click on the "New Post" button to create a new blog post (you must be authenticated).
    - Fill in the form with the required information and click "Save".
    - Navigate back to the homepage to see your new post.

## Deployment

To deploy this project to a production environment, you will need to configure your own server and database. Some popular hosting options for Django applications include Heroku, AWS, and DigitalOcean.
