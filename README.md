# jQuery placeholderTypewriter 

![jQuery placeholderTypewriter Demo](http://assets.bdiekert.com/jquery-placeholderTypewriter/demo.gif)

Typing effect for placeholder of input fields to engage interaction. 

## How to use

You need one input field to display the placeholder animation in:

```html
<input type="text" name="search" id="search">
```

After that you define the text that will run across the placeholder in a loop. Than you hook the placeholderTypewriter up to your text field.

```js
var placeholderText = [
    "Where would you like to go?",
    "Amsterdam?", 
    "Paris?", 
    "Berlin?", 
    "London?", 
    "New York?", 
    "San Francisco?"
  ];

$('#search').placeholderTypewriter({text: placeholderText});
```

## Parameters

| **Option** | **Values**                                      | **Default** |
|------------|-------------------------------------------------|--------------|
| delay      | delay in ms between character typing / deleting | 50ms         |
| pause      | delay between single texts                      | 1000ms       |
| text       | array with strings to display                   | no default   |

## jQuery versions & browser support

jQuery Version 1, 2 and 3 are supported at the moment. 

If placeholders are support from the browser, this should work fine.

## License

This thing is released under the unlicensed license. Please do what ever you like and tell me about it!

## Author

![Bjoern Diekert](http://assets.bdiekert.com/bd_hero.jpg)

I'm Bjoern Diekert, living in Berlin and working on some projects with my company [Borkenstein Plus](http://www.borkenstein-plus.com/). For most of my time I'm tinkering around with HTML, CSS, JavaScript and PHP.