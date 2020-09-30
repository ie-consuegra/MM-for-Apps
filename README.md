
# MM for Apps theme

Modern Materialize for Apps is a theme based on [Materialize](https://materializecss.com/). It is focused on provide an up to date interface equal to the well known web and mobile apps of the "big G".

## How to use it

Until now, the theme is just a CSS file. So, just add the reference to the CSS file after that to the Materialize one.

      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">  
      <link rel="stylesheet" href="css/mmforapps.css">

### The sidenav and the "brand" class
The **"brand"** class replaces the **"user-view"** one on the regular Materialize sidenav.
Add it to the first < li  > tag on the sidenav to wrap your Logo and Name of the app, which are defined inside and < a > tag too.


     <li class="brand">
           <a href="">
              <img src="img/appicon.jpg" alt="">
              <span class="name">My Web App</span>
           </a>
     </li>

## Current issues
* Distances between the icon and the name.
* Main search input behaviour, size on large screens and background color

## Future features
* Sidenav on large screens must be capable of having one more behavior equal to the side menu of Gmail, which keeps the icons visible after hiding the panel.
* Capability of showing (circular) buttons, dropdown menus and the user profile picture on the right side of the navbar.
* On large screen: Capability to show an "action button" (like the compose button of Gmail or the Create one of Calendar) on the sidenav.