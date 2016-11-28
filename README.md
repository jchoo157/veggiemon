# Veggiemon-Grow

Veggiemon-Grow is an app that promotes kids to eat healthier and get them involved in outdoor activities. Kids can scan barcodes of healthy items in a store and potentially find a Veggiemon to battle! If they spend time at a local park or farmers market, they can earn more points to upgrade their Veggiemon. It was meant to be viewed on mobile devices.

You can check out the live version [here] (http://veggiemongrow2016.herokuapp.com/).

![chat] (https://github.com/kenikall/veggiemon/blob/dev/app/assets/images/veg.gif)

### Battling Veggiemon

![search] (https://github.com/kenikall/veggiemon/blob/dev/app/assets/images/veggiemon.gif)

### Google Maps to view local Farmers Markets and Parks

![chat] (https://github.com/kenikall/veggiemon/blob/dev/app/assets/images/veggiemon_maps.gif)

### Backpack that shows items and Veggiemon collected

![chat] (https://github.com/kenikall/veggiemon/blob/dev/app/assets/images/veggiemon_backpack.gif)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
ruby 2.3.1
bundler 1.12.5
rails 5.0.0
```

### Installing
From the command terminal, clone the repository to your local directory...
```
$ git clone https://github.com/kenikall/veggiemon
$ cd veggiemon
```

Then run bundle command to install all dependencies and run the server.

```
$ bundle install
$ rails server
```

## Deployment

You must have Heroku CLI installed and be logged in to Heroku in order to deploy live via Heroku servers
(Please see the [documentation](https://devcenter.heroku.com) to get set up with Heroku)

Then, after installation and login, via the command line...
```
$ heroku create
$ git push heroku master
$ heroku open
```
## Tech Used

* [Ruby on Rails](http://api.rubyonrails.org/) - Backend API framework used
* [jQuery](https://jquery.com/) - Write less, do more with jQuery
* [Ajax](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started) -The use of the XMLHttpRequest object to communicate with server-side scripts.
* [Google Api](https://console.developers.google.com/?pli=1) - Google API Console lets you discover and use Google APIs, such as Google Maps and YouTube.
* [Yelp Api](https://www.yelp.com/developers/documentation/v2/overview) -Search for businesses by location, keyword and category
gmail-like-chat-application-in-ruby-on-rails
* [HTTParty](https://github.com/jnunemaker/httparty) - Library used for making HTTP requests

## Authors

* **Johnny Choo** - [Github](https://github.com/jchoo157)
* **Erinç Emer** - [Github](https://github.com/erinc35)
* **Mannah Kallon** - [Github](https://github.com/kenikall)
* **Chistopher Johnson** - [Github](https://github.com/Koala-t)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

