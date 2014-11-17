notify.js
=========

An Ubuntu-inspired lightweight notification system, powered by Font Awesome.

# Requirements

* [jQuery](https://github.com/FortAwesome/Font-Awesome)
* [Font Awesome](https://github.com/FortAwesome/Font-Awesome)

# Bower

```sh
$ bower install notify-fa
```

# Example

![Example](examples/example1.jpg?raw=true "Example")

# Usage

To use notify.js, you don't have to modify any files to make it work in your project. Just include notify.js and notify.css in your HTML file like this:

```html
<!DOCTYPE html>
<html>
  <head>
    <link href="css/notify.css" rel="stylesheet" />
    <script src="js/notify.js"></script>
  </head>
  <body></body>
<html>
```

A notification can be produced with the following code:

```javascript
var message = 'Hello World!'
var seconds = 5;
var type = 'info' // ... or 'error'

notify(message, seconds, type);
```
The result will be:

![Example](examples/example2.jpg?raw=true "Example")

That's it! Have fun! :-)
