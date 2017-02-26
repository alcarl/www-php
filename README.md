# www-php
The website of AlphaReign

Before we get started.  This was a down and dirty setup.  I have not had the time to go back and clean things up, so, be prepared for the mess if you dive in.


##Installation

You need to have a good working knowledge of how PHP webservers work.  If not, then learn.  Issues about installation will be closed if they pertain to the webserver, installation of modules, etc.

Required PHP Packages:

* php7.0-fpm
* php7.0-sqlite
* php7.0-curl

Install Composer and then run a composer install

Other Packages:

* ElasticSearch
* MySQL / MariaDB

Settings for the database are in the index.php file

If ElasticSearch is not local, you will need to change middleware/es.php


All webrequests should be redirected to /index.php by your webserver