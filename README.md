#cesi ( Centralized Supervisor Interface )

cesi is a web interface provides manage [supervizors][1] from same interface.

## Dependencies

* Python
* Flask
* sqlite3

## Installation

    $sudo apt-get install sqlite3 python python-flask

    $git clone https://github.com/zqctest/test

    $cd cesi

    $sqlite3 path/to/userinfo.db < userinfo.sql

## Configuration

Fill cesi.conf

    #cp cesi.conf /etc/cesi.conf

## Run Project

    $python web.py

## First Login

Please change password after first login!

Username : admin

Password : admin

## Mailing list

zqc0512@gmail.com

cesi-commit@googlegroups.com

cesi-devel@googlegroups.com


## Screenshots

![Dashboard](https://github.com/zqctest/test/blob/master/screenshots/image2)


![Showall](https://github.com/zqctest/test/blob/master/screenshots/image1)

## Blog

[Usage][2]


[1]: http://supervisord.org/

