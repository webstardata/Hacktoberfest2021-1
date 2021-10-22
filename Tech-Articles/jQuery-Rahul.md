
=======================================================

Article Title: jQuery
Author Name: Rahul Vishwakarma
Author Profile: https://github.com/rahulv2001
Date: 22-oct-2021

=======================================================

jQuery is the “Write Less, Do More” JavaScript library. It is not a programming language, but rather a tool used to make writing common JavaScript tasks more concise. jQuery has the added benefit of being cross-browser compatible, meaning you can be certain the output of your code will render as intended in any modern browser.

By comparing a simple “Hello, World!” program in both JavaScript and jQuery, we can see the difference of how they’re both written.

JavaScript
document.getElementById("demo").innerHTML = "Hello, World!";
 
jQuery
$("#demo").html("Hello, World!");
 
This short example demonstrates how jQuery can achieve the same end result as plain JavaScript in a succinct manner.


Linking jQuery

Link to the jQuery CDN right before the closing </body> tag, followed by your own custom JavaScript file, scripts.js.

index.html
<!doctype html>
<html lang="en">

<head>
  <title>jQuery Demo</title>
  <link rel="stylesheet" href="css/style.css">
</head>

<body>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="js/scripts.js"></script>
</body>

</html>
 
Your JavaScript file (scripts.js) must be included below the jQuery library in the document or it will not work.



Selectors

Selectors are how we tell jQuery which elements we want to work on. Most jQuery selectors are the same as what you’re familiar with in CSS, with a few jQuery-specific additions. You can view the full list of jQuery selectors on their official documentation pages.

To access a selector, use the jQuery symbol $, followed by parentheses ().

$("selector")
 
Double-quoted strings are preferred by the jQuery style guide, though single-quoted strings are often used as well.

Below is a brief overview of some of the most commonly used selectors.

$("*") - Wildcard: selects every element on the page.
$(this) - Current: selects the current element being operated on within a function.
$("p") - Tag: selects every instance of the <p> tag.
$(".example") - Class: selects every element that has the example class applied to it.
$("#example") - Id: selects a single instance of the unique example id.
$("[type='text']") - Attribute: selects any element with text applied to the type attribute.
$("p:first-of-type") - Pseudo Element: selects the first <p>.


Conclusion
In this guide, we learned how to select and manipulate elements with jQuery, and how events and effects work together to make an interactive web experience for the user.


