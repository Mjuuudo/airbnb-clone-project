# **airbnb-clone-project**

###  🚀 Project Descreption

<!-- Little Introduction for the project -->

<pre>
    <code>
        Airbnb Clone Project is a backend project based on how  the backend developper
        Control the flow of the data and how he handle the requests from the server side
        and the management of the database and users actions .
    </code>
</pre>

<hr>

### 🏆 Tasks To be realised

✅ User System
* Register, login, logout

* Host vs Guest (user roles or flags)

* Profile page

✅ Property Listings
* Model for Place (e.g. name, description, address, price, owner)

* Image upload (optional or later)

✅ Search & Filtering
* Filter by location, price, or number of guests

* View individual property details

✅ Booking System
* Book a place with dates

* Prevent double booking

* Show user's current and past bookings

✅ Reviews & Ratings
* Add a review to a stay

* Show average rating

✅ Admin Panel

* Superuser can manage users, listings, bookings, etc.

<hr>

### Technology Stack

> Python 3
<br>

> Django
<br>

> Django ORM
<br>

> SQLite (default) / PostgreSQL (advanced) 
<br>

> HTML5
<br>

> CSS3
<br>

> Docker/ Jenkins / GraphQL


### Team Roles 

### Feature Breakdown

> <mark>  Abdelmajid Ait ouaziz Tasks </mark>
<br>

>> User System [ ]
<br>

>> Booking System [ ]
<br>

>> Admin Panel [ ]
<br>

> <mark> Sara Sattar  Tasks</mark> 
<br>

>> Reviews & Ratings [ ]
<br>

>> Databases Designing && Deploying [ ]
<br>

>> Property Listings [ ]

### Database Design

* Users
    1. Full Name
    2. Phonenumber
    3. Email Adresse
* Properties
    1. Location
    2. Price
    3. Owner
* Bookings
    1. Id
    2. Client
    3. Amount
* Reviews
    1. Username
    2. Comment
    3. Date
* Payments
    1. Owner
    2. Amount
    3. Date


### API Security

Application Programming Interface is a gateway for another application to access and  use data<br>
Normally Communication Between Api's  is made by using JSON Files Formats, So yes other app's<br>
can access other api's data, thats why we need to make it protected ! How ??
* Checking Users Roles && Rights
* Crypting Passwords
* Limiting access to concerned Users

and more of the reasons


### CI/CD Pipeline

Is A Methodolgy that allow us automate the process of modify, test deploy our code <br>
For this we need a Platform like Github or Gitlab Which are Great for Developement <br>
Jenkins or docker and python for conternarization and and for unit testing<br>
then Deploying New Feautures With ability to fast rollback in case of somthing fails <br>





