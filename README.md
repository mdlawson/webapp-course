webapp-course
=============

A crash course in web development for a friend of mine. 

# Sessions

## 0 - In which we meet and greet Node.JS

A quick introduction to what node is, when its useful, when it isnt. A runthough of the structure of a webapp, and an explaination of the HTTP verbs that make it work. Going on to what REST means and why you should use it. Finish off with building a quick REST API exposing an array of objects to the world. 

## 1 - In which we put on makeup on a pig

Our API from before is functional, but its not suitable for users. Here we enhance our API, so that it can also generate HTML web pages for people to interact with. We learn about templating, and why its a good idea. We touch on the MVC pattern, and ajust our structure so that we can use it and allow both the html pages based app and the raw API to be used simultaneously.

## 2 - In which we learn jQuery and how to make a mess

Our app works, but those full page reloads sure do suck. Wouldnt it be awesome if we could replace just bits of our pages, and make requests on demand witout page changes? jQuery lets us do this. We cover the DOM, DOM selectors, modification and events,  AJAX, callbacks, and promices

## 3 - In which we straighten up our slouchy app

jQuery sure made things slick, but we ended up with pretty complex frontend code, even for our small app. Worse still, theres no structure at all, and no clear way to add one, which will be a nightmare in the future. Enter Backbone.JS, which implements MVC to help clean up our code (by starting again!). We learn the basics of backbone, and client side templating.

## 4 & 5 - In which we explore other options

Backbone was pretty cool, but requires a bit of manual labour. We rebuild our app in Angular and Ember, two large frameworks with lot of different opinions.

## 6 - In which we add more makeup

So far we havent acctualy styled our app at all! We look at the basics of css, the more complex stuff, some common tricks, responsive design and media querys, some frameworks to help us and the fancy stuff in css3.

## 7 - In which we start using build systems and preprocessors.

So far we've just been using a lot of files and script tags and writing spaghetti css. We'll look at a couple of build systems, grunt and brunch, and how they can help us out with our app structure. This gives us some options for writing css in a more maintainable fasion, in the form of LESS and Stylus. We'll look at those, as well as replacing HTML with Jade, and a quick look at coffeescript.

## 8 - In which we go back to the backend

We've covered frontend stuff pretty extensively now, but our backends feeling abandoned. We look at SQL and NoSQL databases, experimenting with using both in our backend, as well as looking at the advantages and disadvantages of using ORMS to help us out.

## 9 - In which we authenticate ourselves

We cover cookies, sessions, and middleware and implement authentication into our app.

## 10 - In which we communicate in real time

We look at the websocket protocol, first using it directly, then with socket.io to make things easier. We look at adding real time features to our app.


