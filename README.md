ignitespeak
===========

System for collecting Ignite speaker proposals.

Build Status
============
* TODO add some public CI build status graphics a la http://docs.travis-ci.com/user/status-images/

Requirements
============
Ruby 2.0

Setup Instructions
==================

``` cp sample.env .env ```  
You can edit this file to have your own secret token and login information.

Open config/database.yml and configure  
```username: subelsky```  
to be the username in your environment

Setup the database in your environment
```rake db:setup```

Add a proposal to the database
```rake db:seed```

To get your own ignitespeak app up and running, click the button  
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Contributors
============
* Original coding by [Mike Subelsky](http://www.subelsky.com/)
