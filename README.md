#  Udacity Catalog Project 
-  Bhanu Singh 
# To Run
##  About

- This is the fourth project for the Udacity Full Stack Nanodegree. The Item Catalog project consists of developing an application that provides a list of items within a variety of categories, as well as provide a user registration and authentication system. This project uses persistent data storage to create a RESTful web application that allows users to perform Create, Read, Update, and Delete operations.
- A user does not need to be logged in in order to read the categories or items uploaded. However, users who created an item are the only users allowed to update or delete the item that they created.

- This program uses third-party auth with Google or Facebook. Some of the technologies used to build this application include Flask, Bootsrap, Jinja2, and SQLite.

## Skills used for this project

- [Python](https://www.python.org/downloads/)
- [HTML](https://www.w3schools.com/html/)
- [CSS](https://www.w3schools.com/css/default.asp)
- [Bootstrap](http://getbootstrap.com/)
- [Flask](http://flask.pocoo.org/)
- [Jinja2](http://jinja.pocoo.org/)
- [SQLAchemy](https://www.sqlalchemy.org/download.html)
- [OAuth](https://developers.google.com/identity/protocols/OAuth2)
- [Facebook](https://developers.facebook.com/docs/facebook-login/web)  / Google Login 
- Some things you might need

1. [Vagrant](https://www.vagrantup.com/)
2. [Udacity Vagrantfile](https://github.com/udacity/fullstack-nanodegree-vm)
3. [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

# Getting Started

Install Vagrant and VirtualBox
Clone the Vagrantfile from the Udacity Repo
Clone this repo into the catlog/ directory found in the Vagrant directory
Run vagrant up to run the virtual machine, then vagrant ssh to login to the VM
from the main directory run sudo pip install -r requirements
run application with python application.py from within its directory
go to http://localhost/categories to access the application

# OR

* if first time running, you must add a category before adding an item

## You will need:
  - [Subkime Text](https://www.sublimetext.com/)
  - [Python3](https://www.python.org/downloads/)
  - [Vagrant](https://www.vagrantup.com/downloads.html)
  - [VirtualBox](https://www.virtualbox.org/)
  - Setup all these
  - Install Vagrant,VirtualBox,Sublime Text and Python3 or 2.7' in to Machine  

## Go to GitHUb
   > [Clone this repository](https://github.com/Benn9211/Full-stack-Vangrant-repos)
   - To Run
   - Launch Vagrant VM by running vagrant up, you can the log in with vagrant ssh
   
  # OR
   - You can run Putty on windows in order run vagrant file. [Click Here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)

## The database includes three tables:

   - To execute the program, run python3 or python2.7 application.py from the command line useing Vagrent Terminal.
#### Launch Project
  1. Launch the Vagrant VM using command:
  
  ```
    $ vagrant up
  ```
  2. Run your application within the VM
  
  ```
    $ python /vagrant/fn/application.py
    
  ```
   3. Access and test your application by visiting  http://localhost:5000.
