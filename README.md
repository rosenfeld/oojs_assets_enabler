# What is jasmine\_assets\_enabler?

This is a minimal Rails application with support for the asset pipeline
bundled with the Jasmine specs runner. This branch also provides integration
with the [oojs](http://github.com/rosenfeld/oojs) gem.

Just copy these files to your (non-Rails) project root and run:

    rake jasmine:spec_helper
    rake jasmine:spec -- --name=shopping_cart
    rake jasmine:serve

Then browse to http://localhost:5000 and see your specs passing.

Take a look at [this oojs enabled Grails sample application](https://github.com/rosenfeld/grails-oojs).

Happy coding! :)
