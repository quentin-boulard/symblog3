# symblog tutorial - Creating a blog in Symfony3

## Introduction

This project is the documentation source for the symblog tutorial located at
http://tutorial.symblog.co.uk and adapted for using symfony3

Full details of this project can be found at the
[symblog tutorial](http://tutorial.symblog.co.uk) site.

The demo site for this project can be found at 

## Installing

 1. Clone the repository
 2. Rename 'app/config/parameters.ini.dist' to 'app/config/parameters.ini'
 3. Run composer install
 4. Install the assets with 'php bin/console assets:install web'
 5. Create the database with 'php bin/console doctrine:database:create'
 6. Update schema with 'php bin/console doctrine:schema:create'
 7. Load fixtures with 'php bin/console doctrine:fixtures:load'