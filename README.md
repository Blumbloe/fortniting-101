# **fortniting-101**

The Fortniting-101 site is designed as a responsive website allowing users to access the site on various devices such as mobile phones and desktops. Delivering a fun and entertaining experience for users interested in the game of Fortnite. WIth its engaging descriptions and user friendly interface. The site serves as an enjoyable site for gamers of all levels.

The site is aimed to target people who enjoy gaming and are curious to learn more about the game Fortnite. The various sections on the page allow the user to get an idea of what they are able to experience in the game and its various game modes aswell as be able to get in contact with the sites developer so that if they have any questions about the game or the site they can ask me directly and then I will be able to respond back to them via email.

[The site can be viewed here.](https://blumbloe.github.io/fortniting-101/)

## 1. User Experience
The website is created on behalf of the service provider. The aim is to inform the user in order to get them interested in and eventually play Fortnite.

The site provides information about Fortnite, an explaination as to what the game is aswell as what there is to do in the game and a list and explaination of various game modes.


### User Goals
- User friendly navigation and responsive design
- High quality images and engaging descriptions
- Various game modes displayed in a game modes section
- 404 error page for broken links
- contact me form

### User Stories
- As a user, I want to be able to navigate around the website with ease
- As a user, I want to be able to get in contact with the site owner to inqure more about the game
- As a user, I want to be able to use the website on a range of devices
- As a user, I want the images to be clear and high quality with engaging descriptions
- As a user, I want to be able to learn about the different modes the game has to offer
- As a user, I want a 404 error page to know when the links are broken and to be able to get back to the homepage easily
### Target Audience
- First-Time Visitors
- Casual gamers
- Fortnite Fanatics

I have employed the use of the projects function on my repository to keep track of the user stories so that the user stories are recorded along with the task and acceptance criteria required to meet the goal.
![Project card from github](/assets/documentation/user-story-3.png)

Additionally, each goal has been put in order of importance. There are must haves, should haves and could haves. This enables me to discern which targets I need to work on first so that I can meet the minimum functionality of the site.
![Project Board from github](/assets/documentation/project-board.png)

## 2. Design
###  Colour Scheme
For my colour palette I used [coolors.co](https://coolors.co/) to create the colour palette. I took the colours from an old fortnite logo (#7421A1 and #FFFFFF) and used [paletton.com](https://paletton.com/) to generate additional colours that would match the site.

![Colour palette with hex colour codes and colour names](/assets/documentation/color-palette.png) 

###  Typography
[Google fonts](https://fonts.google.com/) was used to apply the fonts of:

Luckiest Guy - Which is used for the title of the page, as well as the headings.

![Image of Luckiest Guy font with text: Luckiest Guy](/assets/documentation/luckiest-guy-font.png)

Noto Sans - Which is used for large body of text, subheadings and navbar text.

![Image of Noto Sans font with text: Noto Sans](/assets/documentation/noto-sans-font.png)

I used [Font Awesome](https://fontawesome.com/) for the icons in the site such as in the footer.

### Imagery
The images on the site were sourced at [Fortnite Wiki - Fandom](https://fortnite.fandom.com/) as well as gameplay screenshots i took myself.

### Wireframes
I used Balsamiq to create my wireframe so that I can visualise the layout of my website. Versions of the site were created for mobile and desktop.

[Index Page Wireframe (Desktop)](/assets/documentation/home-page-wireframe-desktop.png)

[Index Page Wireframe (Mobile)](/assets/documentation/home-page-wireframe-mobile.png)

[Contact me Page Wireframe (Desktop)](/assets/documentation/contact-me-wireframe-desktop.png)

[Contact me Page Wireframe (Mobile)](/assets/documentation/contact-me-wireframe-mobile.png)

## 3. Features
The website is one continuous page, with each section being accessable from the navigation menu. The main page contains all the general information such as the about section and game modes section. There is also two additional pages, those being the success page that consists of a thank you/ confirmation for when you successfully submit the contact me form and the 404 error page that consists of a warning that the link is broken aswell as a button to return to the homepage that will show up if you click on a broken link.

I have used Bootstrap V5.3 throughout the website and much of the code is implemented.

### General Features
#### Navigation
The webiste contains a responsive navigation bar at the top of the page. I have used Bootstrap to implement the base feature and then proceeded to customise it myself. The left side consists of a logo which is selectable and leads the user to the top of the homepage. The right side of the nav bar contains links to various sections of the homepage.

![Image of navbar in viewport greater than or equal to 992 pixels](/assets/documentation/navbar.png)

For a greater user experience and to prevent overcrowding in the nav bar - on viewports of 991px and less the menu aspect of the navbar is transformed into the 3 horizontal line icon (commonly referred to as the hamburger icon), where you can then access the menu items upon selecting the icon. Furthermore, the navbar is fixed to the top of the page and remains in that position when scrolling up or down throughout any of the pages which prevents users from having to scroll all the way to the top/bottom of the page If theres a specific section they would like to go to enhancing the user experience.

![Image of navbar in viewport less than or equal to 991 pixels](/assets/documentation/navbar-compressed.png)

#### Footer
The footer has two main segments, The first being the social links and the second being a disclaimer to make the user aware that this is not official Epic games content or endorsed by Epic themselves. The icons for the social links have been used as they provide a clean footer and are easily recognisable as the symbols of each social platform. Bootstrap was used to help with the styling of the footer

![Image of the footer](/assets/documentation/footer.png)

The footer is positioned at the bottom of the page and wil only be visible once all of the main content of the page has been viewed.

#### Index Page

The index page holds the main content of the website and is divided into sections. The Contact Me section includes a button to submit the form that sends them to the success page. The button was styled to match the colour palette of the website.

#### Title of Site and Message

The first bit of content you will see on the website consists of a div containing the title of the page along with a short introduction to raise interest and give the user an idea as to what the site is about.

![Image of the title and introduciton](/assets/documentation/title-and-intro.png)

#### Image Carousel

After the title and intro the user is immediately shown a carousel of images of gameplay in the various different game modes.

The carousel is set to autoplay and rotates image every few seconds, there are also navigation arrows so that the user can view all of the images at their own leisure. The carousel is responsive and reduces its size with the size of the viewport.

![Image of the carousel](/assets/documentation/carousel.png)

#### About Section
The about section contains two subheadings each with their own paragraphs one explaining what Fortnite is and the other explaining what you are able to do in the game. This section is responsive and the display changes as the screen size gets smaller so that the content can be viewed without the text overflowing out of the screen.

![Image of the about section](/assets/documentation/about.png)

#### Game Mode Section

The Game Modes section contains a main heading and seven subheadings each with a paragraph and their own image with each image being relevant to the mode that is currently in discussion. The whole section is responsive and at viewport sizes lower than 1200 pixels the images will move below each paragraph to prevent overcrowding and for ease of viewing.

![Image of the gamemodes section in viewport equal to or greater than 1200 pixels](/assets/documentation/gamemodes-over-1200.png)

![Image of the gamemodes section in viewport lesser than 1200 pixels](/assets/documentation/gamemodes-under-1200.png)

#### Contact Me Section

The contact form is located at the bottom of the page but can be accessed within the navigation bar.

The section starts of with a title, and then a form which contains a field for their name, their email and the message they would like to send. There is also a button below that allows the user to submit the form which is styled to stand out to the user while also matching the colour scheme. Users also must complete all the fields before they can submit and a popup will appear, reminding the user, if a field is not filled in.

![Image of the contact me form](/assets/documentation/contact-form.png)



