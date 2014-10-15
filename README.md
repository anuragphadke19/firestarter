# Void

A starter boilerplate app template for [Meteor](http://meteor.com) using the following packages: 
[IronRouter](https://github.com/EventedMind/iron-router)
[font-awesome](https://atmospherejs.com/natestrauser/font-awesome)
[collection2](https://atmospherejs.com/aldeed/collection2)
[autoform](https://atmospherejs.com/aldeed/autoform)
[bootstrap-3](https://atmospherejs.com/mizzao/bootstrap-3)
[spin](https://atmospherejs.com/sacha/spin)

Void is based on [Telescope](http://telesc.pe) (an open-source social news app) and is bought to you by the [Discover Meteor](https://www.discovermeteor.com) team. 

## Installation

If you already have Meteor, Void is ready to go. Just clone it locally, run it with `meteor`, and start coding!

If not, here are the full instructions:

```
curl https://install.meteor.com | /bin/sh
git clone https://github.com/anuragphadke19/Void.git myApp
cd myApp
meteor
```

## Features

- Client-side routing
- Publications/subscriptions
- Basic permissions
- Common templates

## Principles

Void adopts a modular approach, where code is broken down in different files rather than all kept in one place. It also uses the “template/mapper” pattern, where the `item.html` template has a similarly named `item.js` JavaScript file that holds its helper code.

Void uses the `Items` collection as an example, but you would probably replace this with your own collection name (`Posts`, `Sales`, `Projects`, etc.) and change the file and variables names accordingly. 

## File Structure

- **client**
	- **CSS**
	- **helpers**
		- handlebars.js
		- router.js
	- **views**
		- **common**
			- footer.html
			- header.html
			- layout.html
			- loading.html
			- notFound.html
		- **items**
			- item.html
			- item.js
			- items.html
		- **pages**
			- homepage.html
	- main.html
	- main.js
- **collections**
	- items.js
- **lib**
	- helpers.js
	- permissions.js
- **packages**
	- iron-router
	- sample-package
- **public**
- **server**
	- fixtures.js
	- publications.js

## Other Boilerplates

- [meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) by matteodem
- [meteor-jw-opinionated-skeleton](https://github.com/jamesdwilson/meteor-jw-opinionated-skeleton) by jamesdwilson (CoffeeScript)
- [meteor-boilerplate](https://github.com/BeDifferential/meteor-boilerplate) by BeDifferential (CoffeeScript)
