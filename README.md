# To Do There

A simple location-based to do list manager. Currently beta quality.

Demo: http://dave1010.github.com/to-do-there/

© 2011 David Hulbert. MIT license. No warranty.

## Features

* See a list of places
* Manually switch between active places
* See a list of tasks associated with a place
* Add/delete tasks
* Add/edit/delete places
* Places are stored with the current geolocation
* Automatically switch places based on geolocation
* Controls for geolocation (toggle)
* Fast

## To Do

* HTML5 application cache manifest (make it offline)
* Controls for geolocation (update interval)
* Show geolocation info (maybe on hover)
* Remove jQuery dependency
* Package as W3C widget (`make widget`)
* Update an existing place to the current geolocation

## Ideas

* Undo delete task
* Show a dynamic / static Google map
* Optional due date / start date for tasks
* Optional tags / hierachy for tasks (use # or /)
* Grouping places (e.g. so places called "Superstore" have the same tasks)

## Design Goals

* UI should be easy to understand
* Should be quick to add tasks
* Should be very quick to delete tasks (use case: shopping list)
* Should look ok
* Should be a single page HTML document
* Work offline & without any server-side technology
* Should be usable as a mobile / desktop widget

## Non-goals

* Login or syncing between devices
* IE support
* Kitchen sink

## About

Developed partly on a Nokia N900, using the `python -m SimpleHTTPServer` for testing.

Type `make` to build.

Pull requests / patches welcome.
