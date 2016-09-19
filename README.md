# Emblem

A small zero dependency plugin for creating text wrapped around a circle.

Demo: http://codepen.io/georgehastings/full/akZxaz/

##Usage:

Let's say I have an element with a class of "emblem" and some text in it.

```html
<div class="emblem">Hello World</div>
```



You initialize an emblem by passing a class or ID to the init() function. If using a class, make sure only one instance exists on the page.

```javascript
Emblem.init('.emblem');
```



That's it. Emblem will grab the text (has to be a string) and rerender it. 

You can also pass in a string if you don't want to use text from your HTML. 

```javascript
Emblem.init('.emblem', 'Hello World');
```

*Not working? Make sure to check out the css in the demo.
