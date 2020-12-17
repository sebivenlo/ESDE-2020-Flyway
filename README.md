# ESDE-2020-Flyway
The slides for this workshop will be available on this repo after the workshop ends. The demo will focus on creating a basic environment on you own machine.

Flyway is an open-source, java based tool used for managing database migrations. Basically, it provides version control for your database

## Prerequisites
To complete this guide, you need to:

 * Download the flyway Command-line tool 

 		https://flywaydb.org/documentation/usage/commandline/#download-and-installation

 * Edit the "conf/flyway.conf" configuration file with the appropriate details where necessary(and example of an already complete configuration file can be find into samples at the bottom, further details will be provided during the live demo)

 * Create your own database

 		Note: We'll  be using remotemysql, so we recommend using that one. Dont't forget to save your credentials, we'll be needing them later

 * a text editor
 
## Demo

* During the demo part of our workshop we will start by giving an introduction to the flyway command line tool.

* Next we'll build a simple database using flyway migration as well as inserting mock-ul data.

* We will make use of version and repeatable/ undo migrations.

* Finally we will test how Flyway handles migrations from different machines in paralel 
