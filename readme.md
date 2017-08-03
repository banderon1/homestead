## Introduction

Laravel Homestead is an official, pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

Homestead runs on any Windows, Mac, or Linux system, and includes the Nginx web server, PHP 7.1, MySQL, Postgres, Redis, Memcached, Node, and all of the other goodies you need to develop amazing Laravel applications.

Official documentation [is located here](https://laravel.com/docs/homestead).

## Local Setup
Modify `/etc/hosts` file:
```
192.168.10.10  homestead.app
aa.bb.cc.dd ape.homestead.app
aa.bb.cc.dd 0.ape.homestead.app
aa.bb.cc.dd 1.ape.homestead.app
aa.bb.cc.dd 2.ape.homestead.app
aa.bb.cc.dd 3.ape.homestead.app
aa.bb.cc.dd 4.ape.homestead.app
aa.bb.cc.dd 5.ape.homestead.app
aa.bb.cc.dd 6.ape.homestead.app
aa.bb.cc.dd 7.ape.homestead.app
aa.bb.cc.dd 8.ape.homestead.app
aa.bb.cc.dd 9.ape.homestead.app
aa.bb.cc.dd 10.ape.homestead.app
```

## Usage
The laravel application that uses these homestead settings can be found here:

https://github.com/odmarkj/neo-laravel
