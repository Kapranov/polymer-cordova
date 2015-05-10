# Ember + Polymer Treasure-Hunt

This app demonstrates an experimental integration between ember.js routing and Polymer's core-animated-pages component to create beautiful inter-state animated transitions.

This is also a hybrid Cordova app that utilizes iOS8's new WKWebView and runs in landscape mode on iPads.

There has not been any effort yet put into performance optimizations, and the original ideas was to trigger state transitions based on proximity to BLE iBeacons. That will hopefully be implemented soon along with a number of other fun things! 😁 

![](https://github.com/blangslet/treasure-hunt/blob/master/public/img/app-screenshot.jpg)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Ember.js - Mobile Animations and Gestures demo app

[Check out the demo on Heroku](http://ember-mobile-animations.herokuapp.com)

[1) Basic animations/gestures tutorial](http://blangslet.com/post/55590279372/ember-js-mobile-animations-and-touch-gestures)

[2) Touch-driven real-time graph tutorial](http://blangslet.com/post/56963258001/ember-js-sparkline-touch-driven-real-time-graph)

[3) Facebook-style push-menu tutorial](http://blangslet.com/post/56963208586/ember-js-mobile-responsive-swipe-push-menu-navigation)

[4) Source Code](https://github.com/blangslet/ember.js-mobile-animations-gestures.git)

![Screen shot](https://raw.github.com/blangslet/ember.js-mobile-animations-gestures/master/doc/screen-shot.png)


To get this demo running:

1. clone or download

2. `cd /app and bundle install`

3. `rake db:migrate`

4. `rake db:seed`

5. `rails s`

#### 10 May 2015 Oleg G.Kapranov
