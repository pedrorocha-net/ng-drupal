ng-drupal:services feature
=========

# Overview

Drupal feature that installs: 
1. Services

2. CORS

3. Full path file info

And then configures a REST endpoint at /api along with a CORS configuration that allow for cross domain communications.

# Installation

Starting from server root dir: 

> drush dl drupal --drupal-project-rename=project-name

> cd project-name

> drush si --db-url="mysql://dbuser:dbpass2localhost/dbname" --site-name=sitename 

> cd sites/all/modules

> git clone --branch feature https://github.com/alexpsi/ng-drupal

> drush en services_and_cors -y
