# What is jasmine\_assets\_enabler?

This is a minimal Rails application with support for the asset pipeline
bundled with the Jasmine specs runner. This branch also provides integration
with the [oojs](http://github.com/rosenfeld/oojs) gem.

There are some examples bundled with this app. Just copy these files to
your (non-Rails) project root and run:

    rake jasmine:spec_helper
    rake jasmine:spec -- --name=shopping_cart
    rake jasmine:serve

Then browse to http://localhost:5000 and start coding your specs in Jasmine.

Take a look at [this oojs enabled Grails sample application](https://github.com/rosenfeld/grails-oojs).

Happy coding! :)
