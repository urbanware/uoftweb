# README #

Projects for the satisfaction of completion of SCS_2679_019 Mobile Compatible Web Programming, University of Toronto, by Walter Spicer. 

### List of Projects ###

* Assignment One
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### Links ###

* website: https://limitless-depths-28791.herokuapp.com
* git clone https[://github.com/urbanware/uoftweb.git]() 
* git clone https[://bitbucket.org/urbanware/uoftweb.git]()

### Setup Heroku Notes ###

* make sure heroku logged in and account setup (see heroku docs)
* cd into project directory
* git init, create project on laptop
* heroku create, to generate subdomain
* heroku git:remote -a put-subdomain-here
* Make an index.html file
* echo '{}' < composer.json
* Make index.php file containing 
```php
<?php include_once("index.html") ?>
```
* git add . 
* git commit -m "Initial commit"
* git push heroku master
