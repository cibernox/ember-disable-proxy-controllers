# Ember-disable-proxy-controllers

Ember.ObjectController and Ember.ArrayController have been deprecated for a while and will be gone in
ember 2.0, but for autogenerated controllers will still be of those types for backwards compatibility.

This addon reexports Ember.Controller as App.ObjectController and App.ArrayController, so you can
stop using them right now and make your migration to the future Ember 2.0 easier.

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
