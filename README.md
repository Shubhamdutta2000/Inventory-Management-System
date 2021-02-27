# Inventory Management System

[![GitHub](https://img.shields.io/github/license/kryptonb/inventory-management-system.svg?style=popout)](https://choosealicense.com/licenses/mit/)

A simple PHP web system for managing an inventory.

Screenshots:

![Sale details](https://github.com/KryptonB/inventory-management-system/blob/master/screenshots/sale.PNG)  
![Search details](https://github.com/KryptonB/inventory-management-system/blob/master/screenshots/search.PNG)

## HOW TO USE LOCALLY

- Download XAMPP
  - Link: https://www.apachefriends.org/download.html
- Clone the repository
  - git clone https://github.com/KryptonB/inventory-management-system.git
- Move the root folder to the htdocs folder of xampp. Location is "C:\xampp\htdocs".
- Start XAMPP and Turn On Apache and MySQL on your Application Server Control Panel.
- Click on Admin part of MySQL module.
- Create a blank DB called shop_inventory.
- Create a new user called 'inventoryUser' with a password as 'password' and give full permission to that user.
- Load the sql dump to the newly created shop_inventory database
  - Click shop_inventory database in left side (which you have created)
  - Choose Import > From SQL Dump… from the File menu.
  - This will bring up a page, select the file on from root project (C:\xampp\htdocs\inventory-management-system\inc\config\shop_inventory.sql).
  - Click Go
  - Your database (shop_inventory) will now be updated.
- Change the root url of your website in constants.php file
  - Location : C:\xampp\htdocs\inventory-management-system\inc\config\constants.php
- Your system show be found on http://localhost/inventory-management-system/ (write this in your browser).

## Requirements

- PHP
- MySQL
- Apache
- Google Chrome web browser (JavaScript enabled)
- Internet connection with a reasonable speed

## Usage

- Access the login.php file from via browser and give _guest_ as username and _1234_ as password

## Built With

- PHP - Scripting language
- MySQL - Database management system
- [HTML5](https://en.wikipedia.org/wiki/HTML5) - Basic markup
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Basic styling
- [Bootstrap 4.1.1](https://getbootstrap.com/) - Responsive framework
- [jQuery 3.3.1](https://jquery.com/) - JS framework

## Acknowledgments

- Inspired by many similar projects online
