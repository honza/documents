Backbone.js
===========

Pros
----

* Less than a 1000 lines of code. You can read it in 30 mins.
* Thorough documentation
* Active community (it's blogged about, discussed, there are guides, etc)
* High-profile implementations:
    * LinkedIn
    * Foursquare
    * Posterous
    * Basecamp Mobile
    * Pandora
    * Groupon
* Depends only on jQuery and Underscore.js which we love to use already.
* Easily organized over multiple files
* All data-related code is contained in the Model
* All DOM-related code is container in the View
* Encourages good structure to your application
* Models, Views, Collections can be subclassed and extended.
* Doesn't impose *a true way* of doing things
    * References between Models and Views
* Allows for easy loading of bootstrapped models & collections
* An API for custom events
* Automatic binding of event handlers in Views
* Testable with Jasmine and Sinon. [More][1]
* Baked-in support for
    * routing
    * pushState
    * LocalStorage
    * templating
* Benefits over GWT
    * Pure Javascript (no compilation step during development)
    * It makes more sense to invest in learning Javascript over Java.
    * Easier debugging
    * A lot less code
    * jQuery eco-system
    * Editor agnostic
    * GWT & Django?
    * It's not magic
    * Basic GWT stock watcher tutorial ~13,000 words
    * Backbone annotated source code ~5,000 words

Cons
----

* Makes assumptions about your backend URL structure. (But can be overriden)
* Doing anything custom in terms of ajax can be a pain
* Can be a little hard to wrap your head around at first

Links
-----

* [Backbone fundamentals][2]
* [Backbone tastypie for Django][3]
* [Backbone docs][4]


[1]: http://tinnedfruit.com/2011/03/03/testing-backbone-apps-with-jasmine-sinon.html
[2]: https://github.com/addyosmani/backbone-fundamentals
[3]: https://github.com/PaulUithol/backbone-tastypie
[4]: http://documentcloud.github.com/backbone/
