# Questions

**With a partner**, answer these questions as completely as possible. Feel free to look at past lecture notes, the web, anything. 

Take the time to explain it to each other. 

The power of this exercise is in the act of _formulating_ and _explaining_ the concepts to someone else (your teammate).

## One

Run the app. Write out the steps, the _pseudo code_, required to create this app. It doesn't have to be totally accurate, or in the right order.

Only move on to the next question when you have enough detail that you would be able to start coding it yourself.

```
// Answer here
Make the the ejs pages/partials. style them. 
Link the back end to handle form actions of the to do list
send the input back to the ejs file where it will be rendered in a different section

```

## Two - `server.js`

Take a look at the `server.js` file.

We have a new module in there, `body-parser` that is required on line `4`. What is it for? What is its use-case? What other lines are related to this module?

_The NPM site might be a good place to start. Feel free to provide links as relevant._

```
// Answer here

to parse the json of req.body

```

## Three - `server.js`

Look at lines `23` and `24`. Explain the methods used. How are they different? What are the usecases for each?

```
// Answer here

23 is just telling the server to render a certain page 
24 is actually sending new data to the server to be stored or checked etc...

```

## Four - `server.js`

Line `6`. That's new. What do you think it's for?

```
// Answer here

We're storing the handlers in a different page and importing them so it's less messy

```

## Five - `handlers.js`

Explain line `1`. Where, why and how is `items` being used?

```
// Answer here

Items is the array that new to-do list items are being pushed to and it's being re-rendered on the front-end

```

## Six - `handlers.js`

Why is there `redirect` on line `11`;

```
// Answer here  

it's redirecting the default submit url, sort of acting as a event.preventDefault()

``` 

## Seven - `handlers.js`

The `handle404` function is a more complex than we've seen thus far, what is the extra functionality for?

```
// Answer here

It's handling both endpoint and data errors

```

## Eight - `ejs`

Take a look at `homepage.ejs` and `todoInput.ejs`. What is happening in there? Explain line-by-line...

```
// Answer here

homepage is the page being rendered that includes the partials. todoInput is the actual form partial being included in homepage
```

## Nine - `styles.scss`

What are lines `2` to `7` for this file? Where are these values being used? Take a look at `_homepage.scss` as well? What do you notice?

```
// Answer here

They are setting global styles for the scss to be used frequently

```

## Ten - `_homepage.scss`

Line `16`. See if by searching the Sass documentation, you can determine what _exactly_ is going on here. That `#{}` notation very specific to this use-case. Why?

```
// Answer here

it's setting the global content width to 60px less for this particular element

```







