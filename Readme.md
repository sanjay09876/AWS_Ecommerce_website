# GreatKart-Django Ecommerce App - Using AWS


GreatKart is an E-commerce Application built using the Python Django 3.1 and AWS

Available Features

- [x] Lists products and categories.
- [x] Filter products based on different categories.
- [x] Functionality to search for items by name.
- [x] Multiple sort features based on rating, price, etc.
- [x] Adding products to the Shopping Cart
- [x] Mail Integration using Twilio SendGrid, Django Backend Email
- [x] Secure Payment Gateway (Paypal,Credit)
- [x] Package application in an AWS Elastic Beanstalk (https://ca-central-1.console.aws.amazon.com/elasticbeanstalk/home?region=ca-central-1#/environment/dashboard?environmentId=e-qiwzsbhasc)
- [x] AWS Deployment  [View App](https://www.ecommercecloudcart.com/)

Technology Used:
* Backend - Python, Javascript,  Django, Django REST API, DbSQLite, Ngnix, Gunicorn.
* Frontend - HTML, CSS, Bootstrap, Javascript
* Cloud Services - AWS Elastic Beanstalk, EC2, S3, RDS, ACM, Route53, VPC, Load Balancer. 

Cloud Service Integrations

- [x] In this project we have implemented various cloud service strategies such as mainly the Elastic Beanstalk where we deployed our code using AWS EbCLI interface and deployed the code with all the configurations set up.
- [x] Secondly we created the Amazon RDS(Relational Database) for storing and manipulating all our data and integrated it with along with our beanstalk where we created an EC2 instance for it aswell. For local deployment we used DbSQLite with PostgreSQL
- [x] However, to get all the static and media files we used AWS S3 bucket for storing the images,css,js and other static files
- [x] Then to have a custom domain and to enhance the security of our website we used Amazon Route53 to integrate a custom domain along with SSL certificates(with help of Amazon Certificates Manager(ACM)) to secure our website and host it on HTTPs
- [x] Also to increase the network traffic and to maintain the scalability of our website we used Amazon Load Balancer along with VPC to ensure high maintainability and performance traffic . 
- [x] We used code deployment platform such as Github and bash to run the code and deploy them dynamically in the server
- [x] For payment gateway we have integrated the Paypal sandbox accounts for payments
- [x] Finally, for sending email regarding order confirmations we used Sendgrid along with Django Email backends


Running this app on your local machine in development will work as
well by following the steps below:


```
mkdir greatkart-course-main
cd greatkart-course-main
git clone https://github.com/sanjay09876/AWS_Ecommerce_website.git
```

Open the Project in Visual Studio Code and create virtual environment

```
source ~/eb-virt/bin/activate 
pip install -r requirements.txt
```
Create Superuser as admin with username and password
```
python manage.py createsuperuser
```

Now run the server using below command
```
python manage.py runserver
```

Starting development server at http://127.0.0.1:8000/



Products can be added to the database using http://127.0.0.1:8000/securelogin


## Licensing

This library is BSD-licensed.

