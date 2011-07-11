# Sinatra Boilerplate

A great place to start with [Sinatra](http://www.sinatrarb.com/), [HTML5 Boilerplate](http://html5boilerplate.com/) and [Compass](http://compass-style.org/) all cooked together.

## HTML5 Boilerplate

sinatra-boilerplate uses *some* of the utter uber-hawtness that is the [HTML5 Boilerplate](http://html5boilerplate.com/) but *not all*. I opted not to use the build script stuff because I feel like it adds an extra layer of trouble when working with Sinatra.

The base layout file is pretty compliant with what the Boilerplate puts out but I've added in `Modernizr.load` instead of putting all the JS at the bottom and a few other minor tweaks. Most of the comments have been left in place though.

## Compass

Because CSS sucks.

## Extra Hawt Sauce

I've added a bunch of modules and helper functions that I use all the time to this to (hopefully) make your life easier when you're getting your app first setup. Some of the helpers methods I've added include:

* **form tag helpers**
  * stuff like `input_for` and `select_for` to make form construction easier
* **asset tag helpers**
  * stuff like `jit` and `slt`
* **run later**
  * for real, true after filters
* **core extensions**
  * extended Hash class with some useful methods for the web
* **Sinatra extensions**
  * a better `erb` method so you don't have to do crap like `erb :"folder/file"` anymore


## Acknowledgements

All the stuff used here is either open source or donation ware. This little starter package wouldn't be possible without the awesome work these guys have done and their generosity in sharing their code with the rest of us.