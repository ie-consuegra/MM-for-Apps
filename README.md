
# MM for Apps theme

Modern Materialize for Apps is a theme based on [Materialize](https://materializecss.com/). It is focused on provide an up to date interface equal to the well known web and mobile apps of the "big G".

The theme is just a CSS file. So, just add the reference to the CSS file after that to the Materialize one.

      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">  
      <link rel="stylesheet" href="css/mmforapps.css">

## Features
- Nav default background color set to white
- Navbar is not only responsive but it gets the appearance of one of a mobile app or a desktop web app.
- Cards with rounded corners

### Create a sidenav with MM for apps
MM for apps uses the **"brand"** class to replace the **"user-view"** one on the regular Materialize sidenav.
Add it to the first < li  > tag on the sidenav to wrap your Logo and Name of the app, which are defined inside and < a > tag too.


     <li class="brand">
           <a href="">
              <img src="img/appicon.jpg" alt="">
              <span class="name">My Web App</span>
           </a>
     </li>

### Narrow class for tables
Materialize has 4 table variations by default: striped, highlight, centered and responsive. MM for apps adds one more, the narrow class.

The narrow class simply makes a table more compact vertically. It can be combined with any other materialize class.

## Current issues
* Distances between the icon and the name of the app.
* Main search input behaviour, size on large screens and background color

## Todo
* Sidenav on large screens must be capable of having one more behavior equal to the side menu of Gmail, which keeps the icons visible after hiding the panel.
* Capability of showing (circular) buttons, dropdown menus and the user profile picture on the right side of the navbar.
* On large screen: Capability to show an "action button" (like the compose button of Gmail or the Create one of Calendar) on the sidenav.