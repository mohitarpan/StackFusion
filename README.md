# StackFusion
Developing a user  form  using node js 
This is a simple user form that allows users to enter their name, date of birth, email, and phone number. The form performs basic front-end validation on the name, email, and age to ensure that the data entered by the user is valid. The phone number validation happens at the backend using Django-Rest-Framework.

Installation
To run this code, you need to have a web server installed on your machine. You can use Apache or Nginx, or any other web server of your choice.

You also need to have Django and Django-Rest-Framework installed. You can install them using pip:

bash
Copy code
pip install django djangorestframework
Usage
Clone this repository to your local machine.
Navigate to the project directory.
Run the following command to start the Django development server:
bash
Copy code
python manage.py runserver
Open your web browser and navigate to http://localhost:8000/ to access the user form.

Fill in the form and submit it. The form will perform basic front-end validation on the name, email, and age to ensure that the data entered by the user is valid. The phone number validation happens at the backend using Django-Rest-Framework.

After the form is submitted, the data will be saved in the database and an email will be sent to the form submitter.

After the form is submitted, you will be redirected to a page where all the submitted forms are displayed.

License
This project is licensed under the MIT License. See the LICENSE file for more information.
