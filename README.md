# PHP Frameworks Battle

## Objective

A Small Web Project will be implemented in various PHP Frameworks.
The implemented solutions will be evaluated and compared   

1. Code Readability
1. Learning Curve
1. Website Performance
1. Website Security

## Application

Applcation scope, as a start, is to create an application that provides functionality for the following (current onomatopoiia was influenced by the theme of "battle"):

1. Creation of users, dubbed "warriors"
1. Basic profile editing for the warriors
1. Warriors can create a one-way connection with another Warrior, dubbed an "alliance"
1. Warrior can post Commands limited text-only content to application
1. Warriors get notified for the content their allies post

Application name, as a convention, is "Battle".

### Entities Described
The following Entities are required. 
The names of the fields (id, created_at, modified_at) can be changed if needed by the framework's conventions.  

#### Warrior
* id
* name
* email
* password
* created_at
* modified_at


#### WarriorAlly
* id
* warrior_id
* ally_id
* created_at
* modified_at



#### Command
* id
* warrior_id
* text
* posted_at
* created_at
* modified_at


## Event Invitation
Use your favorite PHP Framework to implement a small web project and convince the rest why they should use it!

Don't use one or want to try something new? Join a team!


A small web project will be given with a basic set of features.

Teams will be formed to implement the project.

Each team should choose a specific PHP Framework for the implementation.


The project will be split in the following milestones. In parenthesis is what will be evaluated

1. Home page and Contact Page (Html Integration/Form Creation/Routing)
1. A SignUp Form (Database ORM/Form Validation)
1. Administration Area (User Management)
1. Translatable routes and content (Translations)
1. Controller and Model Tests (Unit Testing)


All the code written will be publicly accessible in github.

This is a two days event:
Saturday 12/10 from 11am-7pm Sunday 13/10 from 11am-7pm


## Social

* Event is held in [HackerSpace.gr](http://hackerspace.gr/wiki/PHP_Frameworks_Hackathon)
* Follow us on [twitter](https://twitter.com/php_fw_battle)
