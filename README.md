# College Student Registration System

This interactive Website is a free customized course registration system for college. It is written in PHP, HTML, CSS. The back-end database management system is implemented using MySQL. There are two different login portals for students and administration staff separately. Users can simply log in and get all the related information they need.


## Features

* Account Register
* User Authentication with Pincode
* Notifications
* User Login
* User sign out
* User logs
* Customized Photo Upload
* Confirmation receipt
* Insert/Delete/Search Class Information
* Insert/Delete/Search Student Information
* Password changes


## Front-end & Back-end Setup

* PHP
    1. Clone or download repository as a zip file.
    2. Install the latest version of PHP.
    3. It requires version 7.1 or better to run the program.
    4. You can check the version by typing php -v using the command line.

* MySQL Database
    1. Install the latest version of MySQL database.
    2. Create specific data as a .SQL format.
    3. Import your own .SQL file to the file.
    4. Connect the database via PHPMyAdmin.

* Xampp
    1. Install the latest version of Xampp.
    2. Create the localhost server for your own MySQL database
    3. Connect to your localhost server. (http://localhost/project])
    4. For the complete installation guide, please check (https://www.apachefriends.org/download.html).

## Tech Stack Used

* [PHP](https://www.php.net/downloads)
* [MySQL](https://www.mysql.com/) - For back-end database management
* [phpMyAdmin](https://www.phpmyadmin.net/) - Handle the adminstration of MySQL over the web.
* [Xampp](https://www.apachefriends.org/index.html) - Install Apache web server with PHP.
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Render elements on screen across web browser.
* [HTML](https://html.com/) - Create interactive web pages.
* [Bootstrap](https://getbootstrap.com/) - Implement powerful front-end components.

## MySQL Database Schema

### `course`

| column name     |  data type   | details |
| --------------- | :----------: | ------: |
| `id`            |    Number    |         |
| `courseName`    |     Text     |         |
| `courseCode`    |     Text     |         |
| `creationDate`  |  Date/time   |         |
| `courseUnit`    | Reference_id |         |

### `student`

| column name     |  data type   | details |
| --------------- | :----------: | ------: |
| `id`            |    Number    |         |
| `username`      |     Text     |         |
| `password`      |     Text     |         |
| `created_at`    |  Date/time   |         |
| `user`          | Reference_id |         |

[reference]

https://www.php.net/docs.php

https://dev.mysql.com/doc