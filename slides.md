# CACHING IN SINGLE PAGE APPS FOR FUN AND PROFIT
#### @benzittlau
#### http://benzittlau.com
#### http://springlaunched.com
#### http://zittlau.ca
#### http://github.com/benzittlau



# WHAT IS CACHING?
> a cache (/ˈkæʃ/ kash[1]) is a component that stores data so future requests for that data can be served faster
> -- <cite>Wikipedia</cite>



# WHY WOULD WE CACHE?
One block

With two lines

Another block <!-- .element: class="compete"-->



# Sample image slide
![Glenfarclas](img/glenfarclas.jpg)




# LETS CACHE!
## DEMO PROJECT


## Some projects will give you this for free
[Ember Data](https://github.com/emberjs/data)


## Libraries
### Ruby
Sinatra

HTTParty

### JS
Handlebars

Lodash

JQuery

Twitter Bootstrap


## Source
[https://github.com/benzittlau/twitter_caching](https://github.com/benzittlau/twitter_caching)



## What do we need to start caching?


## Identifiers and Payloads
Most caching sytems are "key value stores"

They need a key, and something to store


## Mirroring HTTP
"Uniform resource identifier" (a key)

The returned body is a that resources payload



## Building in model awareness


## Learning about tweets
By making our caching aware of our data model we can improve efficiency.

This comes at a cost of complexity and cache "bleed" into our app.



## Building in persistence


## HTML5 Local Storage
Local storage persists accross reloads

This can be a good thing, but....



## Building in expiration


## We need a way to ignore 'stale' data
There are many strategies to invalid cache

"Time To Live" is a quick and easy one

