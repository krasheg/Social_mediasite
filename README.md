# Social Media Site
![img_1.png](screenshots%2Fimg_1.png)
This is a project for a social media site built with Python and Django. The goal of this project is to create a platform
for users to connect and share content with each other.

## Features
Some of the features of this social media site include:

User authentication and authorization![img_2.png](screenshots%2Fimg_2.png)

Creating and following Groups![img_4.png](screenshots%2Fimg_4.png)

Posting functionality in groups![img_3.png](screenshots%2Fimg_3.png)

Following and unfollowing other groups![img_5.png](screenshots%2Fimg_5.png)



### Installation
To run this project locally, follow these steps:

Clone this repository to your local machine

Install the necessary dependencies by running `pip install -r requirements.txt`

Create a new PostgreSQL database

Set the following environment variables:

`SECRET_KEY: Django secret key`

`DEBUG: True or False` depending on if you want to run in debug mode

`DATABASE_URL: URL` for your PostgreSQL database

Run the Django migrations by running `python manage.py migrate`

Start the development server by running `python manage.py runserver`
