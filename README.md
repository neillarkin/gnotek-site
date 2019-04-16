# Milestone Project 1 – User Centric Development.
# Gnotek Mock Artist Website

## Overview
This project presents a mock website for a fictitious electronic music artist named Gntoek. 
The site is built using the Boostrap 4 grid system, JQuery and Parallax frameworks. 
The website is intended to be added to my portfolio website as a demonstration of my knowledge of those frame works as well as CSS3 and HTML5.

The website is currently hosted on GitHub Pages and is available here: https://neillarkin.github.io/gnotek-site/

## UX Design
The site is intended to look like that of a creative artistic type by having unusual colours and font type. 
A positive user experience is maintained by designing a simple site to be a one scrolling page of five sections; Landing, About, Music, Tour dates table and a Contact form. 
Each section is accessible by scrolling or via a floating navigation bar. The functional goal of the site is to be a central location where fans can access all of the artists work, social channels, tour dates and newsletters.

## Technologies
HTML5, CSS3, Bootstrap 4 JQuery, Parallax and Hover.

## Use case scenarios
A fan of the artist can get the information about who the artist is, download their music, read the latest tour dates and subscribe to the newsletter. 
There is also links to official social media platforms. The web site is will give the audience an overall sense and feel of what the artist is about and what style of music they create.
Purchasing music – functionality could be developed to allow users to purchase music from the artist by redirecting users to other music content services such as Bandcamp or Soundcloud.

## Testing
Testing was carried out on the latest versions of Chrome, Firefox and Edge. Responsive testing was performed on Android (Chrome)and iOS(Safari).
Testing was carried out using Responsinator.com and Chromes' dev tools views.
The site was developed with a mobile to desktop approach where changes and feature additions were  constantly viewed and tested on both mobile and screen sizes. This approach helped discover any potential design issues early on. 
For example the navigation bar logo had to become hidden on mobile view.

### Bugs and  Performance issues
#### Loading:
the background image is quite large and so degrades performance when loading on slow connections.
#### Parallax:
Parallax scrolling appears to jitter slightly on FireFox. Parallax does not work on iOS. This is a known issue with Parallax and there are some workarounds that could be implemented in future version of this site.

#### Landing Page - on mobile view there is a large space after the jumbotron. The space is create by the row on the About section. For the moment the 'Read More' button works around this, but this a primary bug  that would need to be addressed on the next update.


#### Navigation bar:
1) Clicking a menu item will scroll to that section. If the user then scrolls to another section; the highlighted menu item will not reflect that new section. This could be rectified perhaps by implementing some JavaScript or JQuery to tie the ‘div id’ to the menu items CSS attribute.
2) Hoizontal view on smartphone- the navabar does not toggle to a hamburger menu. This would be a primary issue that needs to be fixed but for the moment users can still access all areas by scrolling.
3) In mobile mode, the navigation bar collapses to a hamburger menu. When expanded the   three horizontal lines move to the left rather than staying aligned right. According to Bootstrap documentation, the menu positions itself left or right depending on where the ‘navbar-brand’  element is placed;  before or after the "<button>" elements. Placing elements correctly did not rectify the issue.
4) Each menu items background colour changes to #000 once selected. This also happened on hover but was changed to a Hover.js effect because hovering to #000 near an item that was already #000 may confuse the user experience.


#### Contact form:
The Contact form is present for cosmetic purposes and is non-functional.

#### Deployment
The sites was built on the Cloud9 IDE with GitHub used to backup milestones in development. The latest version is hosted on GitHub Pages ans is available here.

#### Credits and Sources

##### Text
The Landing Page blurb is taken from a Wikipedia entry on Dub Techno:
https://en.wikipedia.org/wiki/Dub_techno

The artist 'About' blurb is taken from Resident Advisors' biographical on Anders Ilar:
https://www.residentadvisor.net/dj/andersilar/biography

##### Media
###### Images:
The images play a major role on this website and so a colour scheme of ‘orange and teel’  and ‘dark city’ were used as search parameters when sourcing images. All images were sourced from Pexels and Pixabay from photographers Irina Iriser, Mudassir Ali, and Elti Meshau. 

###### Album covers:
Album covers were sourced from the Tresor and Warp Records websites.

###### Music:
Music was taken from Harold Faltermeyer, Boards of Canada and Vangelis.

###### Video:
The video was sourced from YouTube of a live performance of the artist Aphex Twin.

##### Acknowledgements
######
The website took inspiration from the Enjoy art gallery site in New Zealand called (enjoy.org.nz)
###### CSS:
The box shadow on the navigation bar was created using CSSmatic and inspired from a CSSTricks article. https://css-tricks.com/books/volume-i/abusing-box-shadow-fun-visual-effects/ 


###### JavaScript:
The one page scroll code was sourced from W3Schools: https://www.w3schools.com/howto/howto_css_smooth_scroll.asp

The active menu items was sourced from Stackoverflow and edited to fit the site
https://stackoverflow.com/questions/10646775/active-menu-highlight-css 

