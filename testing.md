## Testing

### Testing User Stories
#### Testing User Goals
| Goal                                                | Result  | Comment                                                                                                              |
|-----------------------------------------------------|---------|----------------------------------------------------------------------------------------------------------------------|
| User friendly navigation and responsive design      | Success | The site is fully responsive across various devices and screen sizes                                                 |
| High quality images and engaging descriptions       | Success | The site has engaging descriptions of the game and images, displayed clearly and concisely within the sites content. |
| Various game modes displayed on a game mode seciton | Success | The site contains a responsive game modes featuring the most popular modes and their relevant details.               |
| An 404 error page for broken links                  | Success | The site contains a 404 error page featuring a warning and a way back to the homepage.                               |
| A contact me form                                   | Success | The site contains a contact form for users to fill out.                                                              |

### Bugs

Throughout the development of the site I have been consistently checking for bugs or issues in the code some of those issues are as followed:

- The carousel was not interactable and the solution I found was to rename the ID and classes which gave the carousel its interactivity.

- When clicking on the navbar buttons to go to the different sections of the page the navbar would overlap the section heading. To remedy this I added some padding to the top of the sections so that the navbar would not cover up the headings

- I also had issues with the images in the gamemode section appearing under the images respective text on large screen sizes when they were supposed to be beside one another. To solve this issue I added a div with a class of "row" to each of the divs containing the images and text so that the image would be on the same level as the text.



### Manual Testing 

#### Functionality testing

- The testing was completed on the following devices:

- Personal Computer
- Iphone 16e

The browsers used to test the site include:

- Google Chrome
- Safari
- Microsoft Edge

### Lighthouse
I have used the "lighthouse" feature within Chrome dev tools to test the sites performance, accessibility and best practices. I have checked both mobile and desktop device types.
![image of Lighthouse performance for desktop](/assets/documentation/lighthouse-pc.png)
![image of Lighthouse performance for mobile](/assets/documentation/lighthouse-mobile.png)

![image of Lighthouse diagnostics](/assets/documentation/lighthouse-diagnostic.png)

On initial checks the desktop's performance was satisfactory however the mobiles performance had room to improve. I saw that the biggest issue was the images in the carousel being too big for the smaller screen sizes so I took those larger images and reduced their size to about 45%, which also reduced the file size and then conveted them from jpegs to webp files and then proceeded to use the picture tag to set the default image to the smaller mobile size version of the image and set a minimum width of 465 pixels so that if the screen size is over that amount the larger version of the image is used.

On final checks the scores are greatly improved for both desktop and mobile versions.

![image of Lighthouse performance for desktop after changes](/assets/documentation/lighthouse-pc-final.png)
![image of Lighthouse performance for mobile after changes](/assets/documentation/lighthouse-mobile-final.png)

### Validation

[W3C](https://validator.w3.org/) validator has been used to check the HTML for all the pages 

[W3C](https://jigsaw.w3.org/css-validator/) jigsaw has been used to check the CSS stylesheet 

#### HTML
The initial check in the index.html file came up with a few issues which have since been resolved.

![index.html validation errors](/assets/documentation/index-validation.png)

On final check no issues remain.

The validation check on success.html came up with no errors.

![validation for success page](/assets/documentation/success-validation.png)

The validation check on 404.html came up with no errors.

![validation for 404 error page](/assets/documentation/success-validation.png)

#### CSS


The validation check on the CSS stylesheet came up with no errors.

![validation for css stylesheet](/assets/documentation/css-validation.png)





