# Basic Meteor Boilerplate

Aim of this project is to provide a very basic boilerplate for new Meteor applications.

## Directory structure

```
client/                 # Client-side (browser) code/assets
    stylesheets/        # LESS files
    views/              # Template HTML and Javascript files
        fragments/      # Template fragments (headers, footers, etc.)
        pages/          # Module templates
lib/                    # Code shared between server and client
    collections/        # Collection definitions, schemas and methods
    router/             # Definitions for routing
public/                 # Static resources (images, etc.)
server/                 # Server-side code
tests/                  # Application tests
```

## Packages

Following packages are added to the project to jump-start development:

* [iron-router](https://github.com/iron-meteor/iron-router) - Official Meteor routing solution
* [accounts-password](https://github.com/meteor/meteor/tree/devel/packages/accounts-password) - Official Meteor user management solution
* [alanning:roles](https://github.com/alanning/meteor-roles) - Adds role support to user management system
* [aldeed:collection2](https://github.com/aldeed/meteor-collection2) - Extends Collection class to add support for schemas and validation
* [twbs:bootstrap](https://github.com/twbs/bootstrap) - Twitter Bootstrap 3 - Modern HTML & CSS framework
* [momentjs:moment](https://github.com/moment/moment) - Date & Time manipulation library
* [underscore](https://github.com/meteor/meteor/tree/devel/packages/underscore) - Various utility functions for processing arrays, objects and functions
* [underscorestring:underscore.string](https://github.com/epeli/underscore.string) - String manipulation methods
* [fastclick](https://github.com/meteor/meteor/tree/devel/packages/fastclick) - Reduce 300ms delay for inputs on touch devices
* [meteorhacks:fast-render](https://github.com/meteorhacks/fast-render) - Reduce initial page load time by combining data in first request
* [raix:handlebar-helpers](https://github.com/raix/Meteor-handlebar-helpers) - Helpers extending Blaze with some utility methods
* [sacha:spin](https://github.com/SachaG/meteor-spin) - Easily create a nice, animated spinner for loading pages
* [mike:mocha](https://github.com/mad-eye/meteor-mocha-web) - Testing solution for Meteor; includes [Velocity](https://github.com/meteor-velocity/velocity) testing framework 
* [less](https://github.com/less/less.js.git) - CSS precompiler

Also, for security reasons, two default packages are removed by default: `autopublish` (which publishes your whole databse to the client without restrictions) and `insecure` (which allows everyone to make changes to the database from the client).

## License

You can use this work under the `MIT` license terms.
