diaspora-hub
============

(Unofficial) statistics hub for The Federation (diaspora*, Friendica and Redmatrix).

Note: The Federation is NOT an official term from any of these projects. Credit about where it was first used coming.. :)

Check information and how to add your instance: http://the-federation.info

Database creation
=================

Something like this (MariaDB/MySQL example):

    create database diasporahub;
    create user diasporahub@localhost identified by 'putnicepasswordhere';
    grant all on diasporahub.* to diasporahub@localhost;

Copy config.js.example to config.js and edit proper values there.

Installation
============

Node stuff;

    npm install
    
Python stuff (2.x required);

    sudo pip install MySQL-python

Author
======

[Jason Robinson](https://github.com/jaywink)

[Me on diaspora*](https://iliketoast.net/u/jaywink)

Like this?
==========

Please donate via the options at the end of [the hub page](http://the-federation.info).

License
=======

AGPLv3
