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

* cd into project directory
* git init, create project on laptop
* make sure heroku logged in and account setup (see heroku docs)
* heroku create, to generate subdomain
* heroku git:remote -a put-subdomain-here
* echo '{}' < composer.json
* Make index.php file containing <?php include\\_once("index.html") ?>
* git add .
* git commit -am "Initial commit"
* git push heroku master
