# PortfolioCornholio

## User Story

AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

## Acceptance Criteria

GIVEN I need to sample a potential employee's previous work 
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport


## New CSS and HTML Tricks I learned along the way creating this website:

# WHAT I LEARNED IN CODING SCHOOL WAAAAAAAAAAAS

### Icon Creation
This allowed me to change the icon with the title in the tab of the HTML similar to how YouTube has the red play button:
<pre>
"link rel="icon" 
      type="image/jpg" 
      href="./images/stars.jpg";
</pre> 
- Please Note: Be sure to have the symbols < and > at the beginning and the end similar to the way you link stylesheets.
      
### Font Color Changed to Image Background
This allowed me to create my own type of font color using an image as the background of the text:
<pre>
-webkit-background-clip: text;
background-clip: image;
-webkit-text-fill-color: transparent; 
background-image: url(https://e0.pxfuel.com/wallpapers/456/219/desktop-wallpaper-the-universe-supernova-explosion-star-nebula-thumbnail.jpg);
</pre>

### Layers
This allowed me to move shift the layers of the containers so that I could stack my articles on top of my image:
<pre> 
z-index: 2;
z-index: 1;
</pre>
- Please Note: The lower the number, the further back it will be. For instance, if the number is 1, it will sit behind a different image or      container with the z-index value of 2 or greater!


     
