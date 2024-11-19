HUNGO is a web app developed to help users analyze their buffer calories (food) intake and advise them to replace those extra calories with healthier options and in a way achieving Our mission is to "save a bread" for a "NEEDY". We are aiming to use Google Vision to analyze the calories and buffer nutrients in the food. We also provide users with HUNGO rewards, which encourage them to donate good quality food and get quality checks done to gain more rewards that can be further redeemed.
Additionally , we focus on "DONATING BEFORE EATING" and maintaining the best quality of food.

Tech Stack
HUNGO is developed using Python and Django on the backend
and HTML, CSS, and Bootstrap on the frontend.
We also use APIs and asgi_application to support our app's functionalities.


Installation
To run HUNGO on your local computer, you need to install the following requirements:

1. Python: HUNGO is developed using Python, so you need to have Python installed on your computer. You can download Python from the official website.
2. VS Code: VS Code is a lightweight and powerful code editor that supports Python development. You can download VS Code from the official website.


Here are the steps to run HUNGO on your local computer using a virtual environment:

A virtual environment is an isolated Python environment that allows you to install packages and dependencies without affecting the global Python installation. To create a virtual environment, open your terminal and run the following command:

1. Activate the virtual environment:

To activate the virtual environment, run the following command in your terminal:

.\venv\Scripts\activate
This will activate the virtual environment and you should see the name of the virtual environment in your terminal prompt.

2. Install Django:
Django is a Python web framework that is used to develop HUNGO. To install Django, run the following command in your terminal:

pip install django


3. Install requests:

Requests is a Python library that is used to make API requests. To install requests, run the following command in your terminal:
pip install requests


4.Install mathfilters:

Mathfilters is a Django library that provides math functions and filters for templates. To install mathfilters, run the following command in your terminal:

pip install django-mathfilters

5. Run Database Migrations
Django requires database migrations to set up its database structure:
python manage.py migrate

**6.  Start the Development Server**
Launch the Django development server:
python manage.py runserver




If you have any questions or feedback, please feel free to contact us at prakhar.px@gmail.com. Thank you for using HUNGO!
