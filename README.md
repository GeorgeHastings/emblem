# EmblemJS

A small zero dependency plugin for creating text wrapped around a circle.

Demo: http://codepen.io/georgehastings/full/akZxaz/

Usage:

You initialize an emblem by passing a class or ID to the init() function. Let's say I have an element with a class of "emblem" with some text in it.

```
Emblem.init('.emblem');
```

That's it. Emblem will grab the text (has to be a string) and rerender it. 

You can also pass in a string if you don't want to use text from your HTML. 

```
Emblem.init('.emblem', 'Hello World);
```
