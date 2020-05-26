# Eat-Da-Burger

## Overview

This burger logger application was created with MySQL, Node, Express, Handlebars and a custom ORM. Following the MVC design pattern; I used Node and MySQL to query and route data in my app, and Handlebars to generate my HTML.

Screenshot of deployed site:
![Deployed site](/public/assets/img/burger-site.png)

## Links

* [Github Repo](https://github.com/smithse4/13-burger)

* [Deployed Heroku App](https://stephburger.herokuapp.com/)

## Utility

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the devoured section of the page.

* My app stores every burger in a database, whether devoured or not.

## Installing

To run the app locally, you will first need to git clone the repository to your local machine.

* Cd into repository
* Install dependencies by running 'npm install'
* Start app by running 'node server.js'

#### Directory structure

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
