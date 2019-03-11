![The Monkees Logo](https://static1.squarespace.com/static/583863c1e6f2e1216884123c/t/5a26b3f124a694f272e8be3d/1512495829597/Monkees_red.jpg)

# The Monkees
This website is my first Milestone project in Full Stack web developer course run by Code Institute. 
The website is designed to showcase the music of 1960's rock band **'The Monkees'** and publicise their availability to perform at events such as 
weddings and Christmas parties.

## UX
As part of the design process, wireframes were created using *Pencil* software. Pdf format of wireframes can be found in the folder 
**assets > wireframes**

#### User Stories

###### User Story 1
I want to use the website to preview and buy latest albums.

###### User Story 2
As a die-hard fan of the rock band, I would like to know about the upcoming events. I would
also like to follow them on social media.

###### User Story 3
As an event organiser, I am looking for a good rock band who is available to 
perform at events such as weddings, Christmas parties etc.


## Features

#### Existing Features
I have used following features to meet different user needs:
* Media pages - allows User 1 to listen to music, watch video and even enjoy band photos. Moreover, they can make purchases by clicking on *Buy* button which is linked to official *Monkees* website where they can buy albums and much more.
* Tour page - allows User 2 to stay informed about any upcoming band events. They can click on *Buy tickets* button to make purchase from an external website. 
* Social Media icons - allows User 2 to follow the band on Twitter, Facebook and Youtube. By clicking on the icons, users are taken to the official *Monkees* social media webpages.
* Contact Us Page - allows User 3 to fill in the form to make an enquiry about bands availability to perform on an event.

#### Features Left to Implement
* Subscribe to newsletter option can be added for User 2.
* Audio player can be designed better to improve User 1 experience.
* Previous customer testimonials can be added for User 3 interest.

## Technologies Used

The website is designed using following technologies:
- HTML 
     - The project uses HTML for structure and layout of website.
- CSS
     - CSS is used in an external stylesheet **style.css** to customize and override Bootstrap styles.
- [Font Awesome library](https://fontawesome.com/icons)
     - The font awesome was needed to add *social media* icons in the footer and *left quote* icon in slideshow.
- [Bootstrap 4 framework](https://getbootstrap.com/docs/4.0/getting-started/download/)
     - The project uses Bootstrap 4 framework mainly because of its responsive grid system, useful and beautiful HTML & CSS components.   
- [Hover.css library](http://ianlunn.github.io/Hover/)
     - A great resource to create nice hover effects. The project make use of the following two hover effects: 
        - 'Underline From Center' for navigation links
        - 'Icon Float' for social media icons
- [Google fonts](https://fonts.google.com/)
     - The project uses following two Google fonts: 
        - *Open Sans* font is used for body text
        - *Raleway* font is used for headings
- [Coolors.co](https://coolors.co/)
     - Coolors.co website was used to identify colours that would go well together. 
- [Pencil](https://pencil.evolus.vn/)
     - Pencil software was used to create wireframes for the project because it is an *open-source* GUI prototyping tool.


## Testing
All tests were carried out manually. Testing process was as follows:
##### Home Page
###### Navigation
* Hover on a menu item and verify that hover effect 'Underline From Center' works.
* Hover on logo and verify that the opacity changes.
* Click on *Media* and verify that dropdown menu appears with three menu items - *Audio*, *Video* and *Photos*.
* Click on *Home* and *Logo* and verify that no change occurs.
* Click on *About*, *Tour*, *Audio*, *Video*, *Photos*, *Book Us* and verify that page scrolls down to the relevant section.
* Scroll down to the bottom of the page and verify that the navigation bar remains fixed to the top of the page.

###### Buttons
* Hover on *Preview* and *Buy* buttons and verify that colour change happens.
* Click on *Preview* button and verify that page scrolls down to the *Audio* page.
* Click on *Buy* button and verify that *Monkees* official website is open in a new window. 

##### About Page
###### Carousel
* Bootstrap carousel works as expected.
* Click on next or previous icons of carousel and verify that next or previous slides appear respectively.
* Click on any of the four carousel indicators and verify that the respective slide appears.

##### Tour Page
###### Buttons
* Hover on any button except *Sold Out* button and verify that colour change happens.
* Hover on *Sold Out* button and verify that no change occurs.
* Click on any *Buy Tickets* button or *View all Tour Dates* button and verify that an external website opens in a new window .
* Click on *Sold Out* button and verify that button appears to be disabled as no change occurs.

##### Audio Page
###### Audio
* Click on *Play* icon and verify that audio plays.
* Click on *Volume* icon and verify that it works to control sound level.

###### Buttons
* Hover on any button and verify that colour change happens.
* Click on any button and verify that *Monkees* official website is open in a new window. 
    
##### Video Page
###### Video
* Click on *Play* icon and verify that video plays.
* Click on *Volume* icon and verify that it works to control sound level.
* Click on *Full Screen* icon and verify that video plays in full screen mode.
    
##### Book Us Page
###### Contact Form
* Try missing any required field and verify that error message appears to prompt user to fill in the required field.
* Try writing incorrect format of email and verify that error message appears to prompt user to fill in the email address with correct format.

##### Footer
###### Social media icons
* Hover on any icon and verify that 'Icon Float' hover works.
* Click on any icon and verify that the relevant official social media page of the band opens in a new window. 

##### Responsiveness Testing:
Dev Tools, iphone X and iPad were used to test the appearance of website on mobile/tablet screen size.  Following features were verified:
* A *Menu* icon appears on the right corner and all menu items disappear (mobile only).
* On clicking *Menu* icon, dropdown menu with all menu items appear (mobile only).
* Images, headings, text and buttons rearrange responsively (mobile only).
* Images and font size changes responsively.

##### HTML and CSS validator
[HTML](https://validator.w3.org/) and [CSS validators](https://jigsaw.w3.org/css-validator/) were used to validate the code. 
- HTML validator raised warning to add heading to *Home* section. The warning is ignored as the section does not require a main heading.
- CSS validator raised numerous warnings for codes in the external libraries used in this project. These warnings are ignored!
- CSS validator raised numerous 'unknown vendor extension' warnings on code in CSS stylesheet style.css. Prefixes are required for box-shadow, flex and linear-gradient properties to work in old browsers. Hence these warnings are ignored too!

##### Cross Browser Testing
- [CanIuse.com](https://caniuse.com/)
    - CanIuse.com website was used to check browser support for CSS codes and use correct prefixes, where required.

- The website was tested to function as expected on following browsers:
  - Chrome
  - Firefox
  - IE (Monkees logo image appears pixelated and there is a slight glitch in the slideshow for unknown reason)
  - Edge (slight glitch in the slideshow for unknown reason)
  - Safari
  
##### Accessibility / Screen Reader Application Testing

Wherever possible following things were taken into consideration to make website as accessible as possible:
- Aria-hidden = true is used with fonts awesome to hide the fonts from screen readers.
- Form labels are hidden for design purposes but bootstrap class 'sr-only' is used to make it visible for screen readers.
- Alt attribute is used for images.


## Deployment
*Github pages* was used to deploy the project.

## Credits

##### Content
- The text for *About* section  was copied from the [Wikipedia](https://simple.wikipedia.org/wiki/The_Monkees) article.
- Carousel controls color was changed using the code in [Stackoverflow](https://stackoverflow.com/questions/49391266/change-bootstrap-4-carousel-control-colors) website.

##### Media
- The photos used in this site were obtained from Pixabay and Google images.
- Audio and Video files were provided by Code Institute.
 
##### Design inspiration
- [Htmlburger](https://htmlburger.com/#) website inspired me to add carousel for about us page.
- [Wrapbootstrap](http://wrapbootstrap.com/preview/WB059347H) website helped me design landing page.

##### Code by others
- The code in [Stackoverflow](https://stackoverflow.com/questions/49391266/change-bootstrap-4-carousel-control-colors) was used to change carousel controls colour.

#### Acknowledgements
- I would like to thank my tutor Antonija Simic for all her help and support during the development of this project.   
- I would also like to thank other code institute students for sharing their projects which was extremely useful in designing my first website. 


