# Login-System 

I've updated the login-System more security.
1) allow multiple user login
2) get user password as hash password
3) check user for the verification status


A simple Login System:

User can register an account, before login user need to verify his/her account. user will received a OTP code send by PHPMailer.

User can reset his/her password, user will received a new url link send by PHPMailer to reset his/her new password.

How to use this source code:
requirement:
1) install xampp
here is the link to install xampp
apachefriends.org/index.html

First step:
1) download this repo 
2) create a folder name as login-System -> extract to your xampp folder -> htdocs -> on folder login-System
3) go to phpmyadmin -> create database loginsystem
4) copy all the query command from login.sql -> paste it under the database loginsystem sql.
5) copy the path of index.html -> paste the link -> before C:\xampp\htdocs\login-System\login-system-main\index.php -> modify to http://localhost/login-System/login-system-main/index.php
6) on the less secure on your email account which use to send out the email.
7) modify the account and password under two file -> recover_psw.php and register.php
8) now you are ready to run your login system project !
9) Happy Coding

More details refer to this youtube video with clear explanation
https://youtu.be/-1SJPDL-9o8
