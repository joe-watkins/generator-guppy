# generator-guppy

## gulp + Yeoman = guppy

A webapp generator for [Yeoman](http://yeoman.io) that leverages the [gulp streaming build system](http://gulpjs.com/).

This is my first Yeoman generator so it was mostly built so I could learn more about writing generators. I'm also interested in learning more about gulp!

This simple generator allows a user to quickly scaffold an app and begin using the gulpfile immediately. The app runs on a *very* simple connect server. I hope it's at least enough to put devs a little closer to a Yeoman webapp workflow using gulp. Much cleanup and improvements forthcoming...

## Getting Started

1. Install the generator:

  ```
  $ npm install -g generator-guppy
  ```

2. Navigate to the folder where you'd like to scaffold your project and run the generator:

  ```
  $ yo guppy
  ```

3. Run gulp's default task which launches the server.

  ```
  $ gulp
  ```

## Other Tasks

Guppy also includes a **gulp build** task which:

  - Runs JSHint
  - Minifies & concats JS 
  - minifies CSS
  - More to come soon :)

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
