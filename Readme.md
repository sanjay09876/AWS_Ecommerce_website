# GreatKart-Django Ecommerce App - Using AWS

Video Demo : https://youtu.be/Rr4EOIpiMnM

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

