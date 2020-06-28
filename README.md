# Game on - Final Project

change debug to flase
## Overview G4M3 ON
The idea behind this project is aimed toward the gaming world industry, 
with and ecommerce side to it along with an login function. The idea is 
that you can buy items from the site like clothing and other items game
related.

## Languages used:
- html5
- css / bootstrap
- python/ flask
- django
- javascript 


### accounts
Within this app the accounts app holds the login function to the app,
with a login, register, logout and forgotten password for the user

### checkout
The checkout app has the stripe functionality linked up fo rthe ease of 
of purchasing any items in the site

### basket
With the basket app the user can add multiple item to the basket and then
checkout

### templates
Using the templates ability of django I created the base.html page and
then used the extends function to keep the rest of the site the same just using 
small amounts of code on each page

### settings.py
Used for the setting up of the enironments and secret keys, the naming of the app
that are to be approved in the site. linking in the static.

### urls.py
In these file the urls for each page was created and them in the main urls.py were 
all linked in using the include() function along with the path call. Makes creating the link for pages a
lot easier for naming using the {% url '< name here>' %}

### installed packages for the project
installs
django
pillow
stripe
django-crispy-forms
npm install -g heroku