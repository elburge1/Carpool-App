# carpool-app

This app is being built to allow people to have an easier time finding coworkers or people who work nearby to help them get to and from their jobs and save a little gas/open up extra parking for people.

The general idea is that users will be divided into riders, and drivers. You can register as both when you make an account but only have to register for one or the other. Riders will put in their home/work addresses and the radius from each that they're willing to search for rides within. Drivers will pick a time, and location for when they're leaving and where they're leaving from/where they're headed. The rider will then pick a carpool to join and meet the driver at the designated location.

Drivers will never have access to the address of the rider's home or work, and riders and drivers will be able to rate each other, favorite each other or block each other as necessary.

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js and npm](nodejs.org) Node ^4.2.3, npm ^2.14.7
- [Bower](bower.io) (`npm install --global bower`)
- [Gulp](http://gulpjs.com/) (`npm install --global gulp`)
- [SQLite](https://www.sqlite.org/quickstart.html)

### Developing

1. Run `npm install` to install server dependencies.

2. Run `bower install` to install front-end dependencies.

3. Run `gulp serve` to start the development server. It should automatically open the client in your browser when ready.

## Build & development

Run `grunt build` for building and `grunt serve` for preview.

## Testing

Running `npm test` will run the unit tests with karma.
