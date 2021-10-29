
=======================================================

Article Title: Bootstrap in css
Author Name: Rahul Vishwakarma
Author Profile: https://github.com/rahulv2001
Date: 29-10-2021

=======================================================

What is bootstrap?
Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS- and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.
Bootstrap is a powerful toolkit - a collection of HTML, CSS, and JavaScript tools for creating and building web pages and web applications. It is a free and open source project, hosted on GitHub, and originally created by (and for) Twitter.

Getting Started with Bootstrap Basics
Bootstrap is available in two forms; as a precompiled version, and as a source code version. The source code version uses the Less CSS preprocessor, but if you are more into Sass, there is an official Sass port of Bootstrap also available. To make it easier to make use of CSS vendor prefixes, Bootstrap uses Autoprefixer.

File Structure
We’ll focus on the precompiled version, which can be downloaded here. When you download the zip archive and uncompress it, the basic file structure looks like this:

bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   └── bootstrap-theme.min.css
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2

Basic Bootstrap HTML Template
A basic Bootstrap HTML template should look something like this:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap Template</title>
    <link href="css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <h1>Hello, world!</h1>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
It is important to start any HTML with a HTML 5 Doctype declaration, so that browsers know what kind of a document they can expect.

Conclusion
This covers only a few of the great Bootstrap components that puts Bootstrap ahead of similar frameworks, libraries, and toolkits. With Bootstrap, just a few simple CSS classes are all it takes to build a fully responsive and beautiful front end, fast and easily. It’s a great starting point for your next big project or startup.


