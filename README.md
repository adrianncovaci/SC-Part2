# SC-Part2

## Technologies
* [Python](https://www.python.org/) programming language
* [Django](https://www.djangoproject.com/) framework
* [Oauth](https://en.wikipedia.org/wiki/OAuth)

# Lab 6: SSO Security

## Objectives
1. Offer user authentication via SSO using at least 3 identity providers (e.g. Facebook, Gmail, Twitter, etc.);  
2. Configure SSO integration to get as much data as possible about the end-user;  
3. Output all data which was provided by the identity providers (e.g. user’s name, age,
gender, email etc.).  

## How to use it
1. Clone this repository using [Git](https://git-scm.com) or download the `.zip` archive.  
2. Install Python [install Python](https://realpython.com/installing-python/) and Django (https://docs.djangoproject.com/en/3.1/topics/install/).
3. Once the repository is cloned on your local PC, move to `project` folder and perform the following:
   1) Migrate database `python3 manage.py migrate`, 
   2) Run the local server `python3 manage.py runserver` and follow the link -  http://127.0.0.1:8000/login.
   

# Lab 7: Database Security

## Objectives
1. Create a MongoDB database which would contain some secured sensitive data (protected via RSA encryption);
2. Create an application which would display the data contained in the database (both common data and the decrypted sensitive data);
3. Make sure that the sensitive data can only be accessed via your application (i.e. it is secure).

## Additional Technologies
* [MongoDB](https://www.mongodb.com/) database

## How to use it
1. Clone this repository using [Git](https://git-scm.com) or download the `.zip` archive.  
2. Install Python [install Python](https://realpython.com/installing-python/) and Django (https://docs.djangoproject.com/en/3.1/topics/install/). 
3. Once the repository is cloned on your local PC, move to `project` folder and perform the following:
   1) Run `python app.py` to start application.  
   

# Lab 8: Email Confirmation

## Objectives
1. Create an application that could register a new user;
2. Perform email confirmation (via a one time password / code or via a link);
3. Output on the screen whether a user confirmed their email or did not confirm it yet.

## How to use it
1. Clone this repository using [Git](https://git-scm.com) or download the `.zip` archive.  
2. Install Python [install Python](https://realpython.com/installing-python/) and Django (https://docs.djangoproject.com/en/3.1/topics/install/).
3. Once the repository is cloned on your local PC, move to `project` folder and perform the following:
   1) Migrate database `python3 manage.py migrate`, 
   2) Run the local server `python3 manage.py runserver` and follow the link -  http://127.0.0.1:8000/login.
   
   
# Lab 9: CSRF Security

## Objectives
1. Create a web application where the user can authenticate;
2. Implement CSRF protection for your web application;
3. Prove the effectiveness of implemented mechanisms (via video).

## How to use it
1. Clone this repository using [Git](https://git-scm.com) or download the `.zip` archive.  
2. Install Python [install Python](https://realpython.com/installing-python/) and Django (https://docs.djangoproject.com/en/3.1/topics/install/).
3. Once the repository is cloned on your local PC, move to `project` folder and perform the following:
   1) Migrate database `python3 manage.py migrate`, 
   2) Run the local server `python3 manage.py runserver` and follow the link -  http://127.0.0.1:8000/login.
