# E-Commerce Website in Django
This is a simple e-commerce website built with Django (Python).

I've made this as a "Jewelry Shopping Website".

## Screenshots

![S1](https://github.com/nikhilyadvv/ecommerce_website/assets/74718187/9aa3bb0a-7e47-4a50-a4c5-adceb05a9123)

![S2](https://github.com/nikhilyadvv/ecommerce_website/assets/74718187/26c13003-2bae-4aa5-b638-8e095d3e9234)

![S3](https://github.com/nikhilyadvv/ecommerce_website/assets/74718187/365277fb-ba9b-42c1-9603-358cd4774efc)

![S4](https://github.com/nikhilyadvv/ecommerce_website/assets/74718187/c13b2ed5-2fa1-4c04-925c-32aefdc4ed47)

![S5](https://github.com/nikhilyadvv/ecommerce_website/assets/74718187/f8f203f3-2894-427a-a61e-11b5cd5d5c0b)

## Features of this Project

### A. Admin Users Can
1. Manage Category (Add, Update, Filter and Delete)
2. Manage Products (Add, Update, Filter and Delete)
3. Manage Users (Update, Filter and Delete)
4. Manage Orders (View and Process)

### B. Non-Registered Users Can
1. View Products (Can filter based on category)
2. Explore Product Details and Related Products


### C. Registered Users Can Can
1. All ot Non-Registered Users
2. Add to Cart
3. Process the order using Cash on Delivery mode
4. See the Order Status
5. See Order History
6. Update Profile 
7. Change Password
8. Reset Password

## How to Install and Run this project?

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

```
$  python -m venv venv
```

Activate Virtual Environment

```
$  source venv/scripts/activate
```


**3. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**4. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```


**5. Now Run Server**

```python
$ python manage.py runserver
```


**6. Login Credentials**

Create Super User (Admin)

```
$  python manage.py createsuperuser
```

Then Add Email, Username and Password
