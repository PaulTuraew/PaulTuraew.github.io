---
layout: post
title: Bootstrap v.3 Basics
---
Summary: Getting acclimated with Bootstrap setup so you can run and play with it.

**What is Bootstrap?**

Bootstrap is a responsive design framework that is mobile first. Basically, you download the files, incorporate them into your project and use what you need, how you need.  

Bootstrap can best be thought of as a middle of the road front-end solution... in between a using a pre-built (out of the box) template and making a website from scratch.

*Positives*: You can create a responsive site without having to know too much HTML or CSS if you're a back-end dev. Font icons that are now vector graphics can be re-sized and colored unlike the .png files of old.

*Negatives*: You will have to learn someone else's code (Bootstrap's). You will get a bloated code base that may require more writing than a custom job.

**Getting Started**

After downloading the files from http://getbootstrap.com/getting-started/ you will really only need 3 files which are located in the "dist" folder: "css", "js", and "fonts."

Don't worry about the .min files (within the css and js folders), these are simply condensed versions of the other css files. It's good to link to them but look at the larger (spaced out / un-minified) files for reference.

To truley make best use of Bootstrap, you will also want to download and link to jQuery and Respond.js in your HTML file.

**Setting up the HTML page**

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>RI Turaew's Professional Site</title>
    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/custom.css" rel="stylesheet">
    <script src="js/respond.js"></script>
  </head>

  <body>
    <h1>Hello, world!</h1>

    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
  ```
  *For Respond.js*: Go to the Respond.js Github page, copy the *.min* source code, create a new file in your project's JS folder called "respond.js" and save. Linking src belongs in head and not body per Respond's instructions.
  
**The Grid System**

Basically, there are 4 class prefixes that will dictate whether the grid cells remain horizontal or move into vertical allignment:
 
*  .col-xs-#: will never move into vertical allignment, no matter how small the window;
*  .col-sm-#: will move into vertical allignment at 750px;
*  .col-md-#: will move into vertical allignment at 970px;
*  .col-lg-#: will move into vertical allignment at 1170px.

The *#* corresponds to numbers 1-12 depending on how wide you want that grid cell to be.

*!Important* You must start your HTML section (in which you want to use the grid system) with `<div class="row">`.

 






  