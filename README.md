# PORTFOLIO PROJECT - 1 #

# Take a Hike #

## Goals for this project 
Take a Hike is a website designed to introduce local people to the hiking club which provides an outlet for any age groups, any gender and caters for all levels of experience. The hiking group was set up during the pandemic to encourage people to move more, meet new people, explore more, and maybe for some, to take up a new activity. The website provides information about the club, information about the benefits of hiking, the club's upcoming events, they are organised by difficulty level to show a potential member the options available when joining the group. The site also allows the person to make contact with the club easily through social media links or directly via the contact form on the site.

* [Here is a link to the final project](https://lynnemcgrail.github.io/take-a-hike/) 

## Final Design 
![Final project image home page](assets/readme-docs/testing:am-i-responsive.png)

## Initial Idea Concept
My initial idea for the project was to create an informative and welcoming website about the activity of hiking in Ireland. My target audience is anyone who is interested in the activity itself or seeking to benefit their health and well-being, whilst meeting new people and establishing social connections.
This site can be any age group, any gender and any experience level. The site is safe for all age ranges from children to adults who want to learn about hiking in Ireland. I chose to make the site bright to display the information clearly and so people could navigate it easily.

* The Features I wanted the project to have are:
    * To make the site easy to read.
    * To have a light colour scheme (white background, dark text colour and complimenting bright colours throughout to represent nature which also tie in with the colours in the hero image).
    * To have an easy to navigate "Nav Bar".
    * Look fun and inviting with images, and to be educational on the health benefits associated with hiking.
    * To feature a map embedded to highlight where the Hiking Club's locality is based.
    * To be easy to make contact with the club through social media or the contact form on the site.


#
## Table of Contents
- [UX/UI](#uxui)
    * [SITE GOALS](#site-goals)
    * [USERSTORIES](#user-stories)
    * [REQUIREMENTS](#requirements)
    * [EXPECTATIONS](#expectations)
- [WIREFRAMES](#wireframes)
  * [FEATURES](#features)
  * [DESIGN](#design)
- [TECHNOLOGIES USED](#technologies-used)
  * [PROGRAMMES USED](#programmes-used)
- [TESTING](#testing)
  * [VALIDATION AND ACCESSIBILITY](#validation-and-accessibility)
  * [LIGHTHOUSE](#lighthouse)
  * [ACCESSIBILITY](#accessibility)
  * [CSS](#css)
  * [HTML](#html)
  * [FUNCTIONALITY](#functionality)
- [BUGS AND ERRORS](#bugs-and-errors)
  * [SOLVED BUGS AND ERRORS](#solved-bugs-and-errors)
  * [UNSOLVED BUGS AND ERRORS](#unsolved-bugs-and-errors)
- [DEPLOYMENT](#deployment)
  * [REMOTE](#remote-deployment)
  * [HOW TO FORK A REPOSITORY](#how-to-fork-a-repository)
  * [HOW TO CLONE A REPOSITORY](#how-to-clone-a-repository)
  * [HOW TO MAKE A LOCAL CLONE](#how-to-make-a-local-clone)
- [CREDITS](#credits-and-references)
  * [IMAGES AND INFORMATION](#images-and-information-sources)
  * [CODE](#code-sources)
- [ACKNOWLEDGEMENTS](#acknowledgements)

#
# UX/UI
* This website was created to demonstrate my knowledge of HTML and CSS and to provide users with visual and educational content.
* The website should be easy to navigate.
* The website should be easy to read, and images should be clear without becoming stretched or squashed.

#
## Site Goals
* To showccase my skills in HTML and CSS.
* To provide users with an easy to understand and easy to navigate website.
* To provide users with enough information to decide if they'd like to join the club.
* To make the site easily accessible for all users.

#
## User Stories 
* As a user, I want to understand the main purpose of the website.
* As a user, know that the club is well established.
* As a user, I want the website to give me the health benefits of hiking.
* As a user, I want to be able to navigate the site with an easy to see and read nav bar.
* As a user, I want the site to be attractive.
* As a user, I want to know what events are taking place.
* As a user, I want to see images related to the hiking group.
* As a user, I want to be able to easily contact the club.

#
## Requirements ##
- Easy to navigate on various screen sizes.
- Clear information on the services provided.
- Keep the user interested with small bits of information to make them want to engage with the club.
- Simple methods of contacting the club.
- Visually inviting and readable, so users do not leave.

#
## Expectations ##
- I expect to know if a form has been submitted properly and if items are not filled in, to be prompted -e.g. error message if email address required and not input properly.
- I expect all links to social media sites to be opened in a new tab.
- I expect all navigation links to work correctly and open in the same tab, but navigate to the section selected in the nav bar.
- I expect screen size not to affect the quality of the website.
- I expect all information to be correct and accurate.

#
## Wireframes 
* I used [Balsamic](https://balsamiq.com/) to develop my wireframes for my website. I initially created the mobile version, and then scalled it up for both tablet and desktop. Because one of my requirement is to give quality information to the user to make them want to engage with the club, a one-page website is used. This guides the user through the content and quickly to the contact form and details via scrolling or directly via the navigation bar.

The wireframes can be viewed [here](assets/readme-docs/wireframes.pdf)

#
## Features 
* The site consists of:
    * 5 main sections on one page, `HOME, ABOUT, UPCOMING EVENTS, GALLERY, CONTACT US`
    * The page contains a `HEADER (TITLE)`, `NAVBAR`, `MAIN CONTENT (TEXT AND IMAGES)` and `FOOTER (SOCIAL MEDIA ICONS/LINKS`
* Navigation bar:
    * The navigation bar is fully responsive to allow for various screen sizes. It includes links to maneuver through the site easily with each menu option navigating to it's particular section.<br>
    <img src="assets/readme-docs/testing:navigation-menu.png" width=400><br>
    * On mobile and tablet screen sizes you can see the hamburger menu option appears, highlighting the responsiveness of the site across device sizes<br>
    <img src="assets/readme-docs/testing:hamburger-menu.png" width=400><br>
    <img src="assets/readme-docs/testing:hamburger-menu-drawer.png" width=200>

* Footer:<br>
<img src="assets/readme-docs/testing:footer.png" width=400>

* Layout and content:
    * The Header section will have some introductory text and a landing image.
    * The About section follows with an introduction to the club and a 'Why Join Us' section which provides valuable information to the user about the benefits of hiking. 
    * The Gallery will have multiple images of the club's members, to encourage the site user to join.
    * The Contact Us section will have a form to include first name, last name, email address and a submit button
    * The thank-you page will have some thank-you text and a link back to the Home page.

* Hover effect on links and social media icons:
    * The blue shade indicates to the user the location of the mouse and selection that will be made, whilst navigating the menu
    <img src="assets/readme-docs/testing:hover effect on menu.png" width=400>

* Contact Form:
    * Form validation requests the user to input the correct information in the input fields, this avoids the user sending illegible text/email.
    * Input the use of radio buttons to demonstrate the skills I have learned to date through the course so far.
    * I added a thank you page for submitting the form so that the user is reassured that their message has been sent.
    * <img src="assets/readme-docs/testing:contact form.png" width=400>

#
## Design
* Color Scheme:
    * With being a website that is both informative and fun, the color scheme chosen were colourful and bright to reflect nature and being outdoors. Bright background colours were used and then colourful elements to make sections 'pop' on the site to provide an appealing user experience. The colours chosen for the text and images will be clear against the background so that the site is readable. (See hex colours below)
    * #C9F4F4 - This colour will be used as a background colour for the navigation menu when items are hovered over.
    * Colour choices explained:
    * #13FFFF - This colour will be used as a background colour for text sections overlaying images with an appropriate text colour for readability.
    * #F39D75 - This colour will be used on the contact form for added styling.
    * #E36D50 - This colour will be used for styling the icons in the footer section 
    * #282828 - This colour will be used as a text colour and in any styling background where required. I chose a dark charcoal grey so it was readable but not as dark as black for the reader.<br>
    <img src="assets/readme-docs/testing:coolors-palette.png" width=350>

## Landing Page 
* The landing page image chosen gives the user instant association that the club is about hiking, and with added zoom animation, immediately grabs their attention to the site.
* The image and text gives the user instant recognition as to what the club and site is about.<br>
<img src="assets/readme-docs/testing:landing-page-readme.png" width=400>


## About Section 
* This section welcomes the site user and gives an insight into what the club ethos is, so the potential member gets a feel for the group they would be joining. 

## Images
* I sourced images for the hero image, upcoming events and members gallery from the following sources, Pexels and Unsplash.
* There are a total of 14 images across the site.
* All images have been compressed through `Tinypng.com`
* None of the images used have been pushed past the pixel limit in order to prevent image distortion

## Typography
* In order to move away from basic fonts available, I have used [Google Fonts](https://fonts.google.com/) on my site to find a font that best suits the feel of my website. The fonts I chose are [Assistant](https://fonts.google.com/specimen/Assistant?query=assistant) and a backup of [Sans Serif](https://fonts.google.com/knowledge/glossary/sans_serif), which were imported into my code, from [Google Fonts](https://fonts.google.com/).

## Icons 
* I chose the icons for my website from the [Font Awesome library](https://fontawesome.com/icons). These icons will only be used where there is no explanation needed to their meaning, social media links, contact links and a hamburger for navigational links on smaller devices. All icons used will be styled in keeping with the appearance of the website.

## Structure 
* When building my website, I wanted it the styling to be responsive from desktop screen size to mobile screen size. The responsive media queries guidance used was [W3Schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)

#
## Technologies used
* [HTML](https://en.wikipedia.org/wiki/HTML5)
* [CSS](https://en.wikipedia.org/wiki/CSS#CSS_3)

## Programmes Used
* GIT
  * For version control, committing and pushing to github. 
* GITPOD 
  * The IDE used to code this website.
* GITHUB
  * Used to create and store repositories, files and images pushed from gitpod.
* Am I Responsive
  * Used to test the responsiveness of the website at different screen sizes 
* CHROME Developer Tools 
  * For checking compatibility, troubleshooting and editing code live to see what changes needed to be made. 
* Font Awesome 
  * Used for the logo, section titles and social media link icons in the footer of each page. The font awesome script is also linked in the HTML file for these to be visible on the site. 

#
# Testing
## Features to be Implemented
* For the contact form to send a message to Take a Hike, instead of leading to a dummy 'thank-you' page.
* Display and add links to club sponsors websites.
* Add a shop for club branded clothing to be purchased.
* Add a self-guided hiking route feature with downloadable offline maps for members to select and navigate themselves at any time, rather than only being able to join any of the groups upcoming organised hikes and pre set locations.
\
&nbsp;

## Validation and Accessibility
#
## Lighthouse
### **Lighthouse Report:**
* All pages of the app were tested using the lighthouse function built in to the Google Chrome browser on incognito mode.
  
  <img width="400" src="assets/readme-docs/testing:lighthouse-homepage.png">
  
  <img width="400" src="assets/readme-docs/testing:lighthouse-gallery.png">
  
  <img width="400" src="assets/readme-docs/testing:lighthouse-thankyoupage.png">

## Accessibility
### **WAVE Webaim Accessibility test report:**

* The WAVE tool was used to test all pages on the site.
  One minor error remains for accessiblilty testing relating to the hamburger menu, this is due to the hidden label element being empty and cannot be changed as this will affect the functionality of the menu
  As before a summary of results is shown as well as links to the individual results.  
    
  * [Link to home page WAVE result](https://wave.webaim.org/report#/https://lynnemcgrail.github.io/take-a-hike/index.html)  
  * [Link to gallery page WAVE result](https://wave.webaim.org/report#/https://lynnemcgrail.github.io/take-a-hike/gallery.html)  
  * [Link to thank-you page WAVE result](https://wave.webaim.org/report#/https://lynnemcgrail.github.io/take-a-hike/thankyou.html?first_name=Lynne&last_name=McGrail&email_address=lynne.mcgrail%40gmail.com&what-style=both) 

## CSS
**CSS Validator results:**
  Only the custom CSS file was tested<br>
  **Style.css**<br>
  <img width="600" src="assets/readme-docs/CSSValidator.png">

## HTML
**HTML Validator results:**
  All HTML was passed through the validator retreived from the source code within devtools on Chrome.<br>

  **Index.html:**<br>
  <img width="600" src="assets/readme-docs/HTMLValidator-Index.png">

  **Gallery.html:**<br>
  <img width="600" src="assets/readme-docs/HTMLValidator-Gallery.png">

  **Thankyou.html:**<br>
  <img width="600" src="assets/readme-docs/HTMLValidator-Thankyou.png">

### **Functionality**
* All links have been hovered over and clicked on to ensure accessibility
* All Social media links work correctly and open in a new tab
* Pages all load correctly on all device screen sizes
* All images load on each page as intended

#
# Bugs and errors

## Solved bugs and errors
In my opinion, the site has hit the goals required by all users. The site responds nicely across all different screen sizes, the images look clean and sharp on all device sizes, with very little, large blank spaces. It allows the user to navigate around easily and aslo make contact with the club via the contact form or social media icon links. The content is simple and to the point and the site is not overcrowded as to put the user off.
\
&nbsp;

I have encountered several issues during testing.

* I initially decided to create the site with a minimum width of 992px as my largest styling, however the site just did not look right so added an x-large screen size.
* One of the errors highlighted in the HTML validator was within my 'events' section, I learned from this error that instead of using an ID which I had done initially, using a class worked better and gave me more control over the divs highlighting each upcoming event to the site user. 
* Originally I had planned one style of navigtaion menu, however on testing my site across different device screen sizes, I implemented a hamburger menu (see code credited below). The hamburger menu works much better across smaller screeen sizes such as mobile and tablet. 
* I had issues with the navigation menu, when it was styled in the fixed position to allow for the user to scroll on the site whilst maintaining the navigation menu in sight, it overlapped the page content, particularly the landing page image and gallery page images, I fixed this by adjusting the margin-top in the css styling.
* I created a hover effect within the hamburger menu so the user can see which navigation they are selecting, when hovering over each selection the text turns white which is distinctive in contrast to the background colour. 
* The hamburger menu initially did not close on selection, however I fixed this bug and it now operates fully opening and closing so that the drawer disappears and the user can navigate the site easily. I removed some navigation elements from the hamburger menu, i.e. when the user is active on the gallery page, the hamburger menu then only shows the Home navigation option. This was because on testing, some of the other links didn't respond so I removed them to avoid non-functional links. I did the same for the thank-you page hamburger navigation links, where the user can navigate to Home or Gallery.
* The contact form initially did not require a name or email when interacted with. This was a minor error which I fixed, and prompted me to include a thank you page when the user submits a request through the contact form. I also input the use of radio buttons to demonstrate my skills within the contact form section. 
* On testing the gallery across all device sizes, I noticed the pictures were distorted on a smaller screen and very squished. To fix this, I implemented a column count within the media queries to suit differen screen sizes. This has allowed for easier navigation and enhanced user experience when viewing on smaller devices.
* I embedded a map as a feature to allow for user control, and for users to be able to interact with the site. Initially the map was displaying incorrectly on mobile devices, a minor error I was able to test and fix within the CSS styling, particularly within the margin, and now the map is responsive across all device screen sizes. 
* A console error notified me that the favicon was not loading in the live site, this was an error within the relative file path, which was a minor issue and is now working correctly.

## Unsolved bugs and errors
* There is one occasion where I have used 'floats' in my project, I was unable to control the section to respond the way I had intended it to, by using flexbox. However I have used flexbox successfully elsewhere, and I hope by demonstrating both methods in my project, it highlights the skills that I have learned so far. I know there is still a lot for me to learn, and I hope as I develop my skillset as a Software Developer, that I can streamline some of the methods I have used in this project in my future projects and as eventually as a qualified developer in the coding industry. 

#
# Deployment
  ## Remote Deployment
  (Assuming you have already cloned or forked)
* Following writing the code, then committing and pushing to GitHub, this project was deployed using GitHub through the following the steps:

1. Navigate to the repository on GitHub and click on the `Settings` icon at the top of page in the navigation bar
2. Scroll down until you see `Github Pages` on the side navigation
3. Choose the branch in the drop down box, in this case `Main`
4. Choose the directory in the next drop down box, in this case `Root`
5. Then click `Save`
6. It may take a few moments for the site to publish, but once live, the box at the top of the page with the site name will turn green and have a `Green` tick to the left of the link to the live site
7. Another way to find the live site is to navigate to settings, on the left menu click on `pages` and this will get you to the same point.
8. Now the website is now live on https://lynnemcgrail.github.io/take-a-hike/
9. If any changes are required, they can be done, commited and pushed to GitHub and the changes will be updated.

## Git Commands Used
The following commands were used for version control during project:

* git add `example filename` - to add files before committing.
* git commit -m `"example message"` - to commit changes to the local repository.
* git push - to push all committed changes to the GitHub repository.
* git status to display the working area to see which changes have been staged and which haven't. 

#
## HOW TO FORK A REPOSITORY:

If you need to "FORK" a repository:

1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/LynneMcGrail/take-a-hike
2. In the top right corner, click `Fork`
3. The next page will be the forked version of https://github.com/LynneMcGrail/take-a-hike but in your own repository

#
## HOW TO CLONE A REPOSITORY:

If you need to make a clone of this repository:

1. Fork the repository https://github.com/LynneMcGrail/take-a-hike using the steps above
2. Above the file list, click `Code` (Usually green at the top right of the code window)
3. Choose if you want to clone using HTTPS, SSH or GitHub CLI, then click the copy button to the right
4. Open Git Bash
5. Change the directory to where you want your clone to go (your own github)
6. Type `git clone` and then paste the URL you copied in step 4
7. Press `Enter` to create your clone

#
## HOW TO MAKE A LOCAL CLONE

If you need to make a local clone:

1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/LynneMcGrail/take-a-hike
2. Under the repository name, above the list of files, click `Code`
3. Here you will have two options, `Clone` or `Download` the repository
4. You should close the repository using HTTPS, clicking on the icon to copy the link
5. At this point, you can launch the `Gitpod workspace` or choose your own directory
5. Open Git Bash
6. Change the current working directory to the new location of where you want the cloned directory to be
7. Type git clone and then paste the URL you copied in step 4
8. Press Enter, to create your local clone to your chosen directory

#
## Credits and References

### Images and Information Sources

* [The Hike Life](https://thehike.life/) for inspiration and information. 
* [Hike It Baby](https://hikeitbaby.com/) for ideas to inspire my project development.
* [Wikipedia](https://en.wikipedia.org/wiki/Hiking/) for information.
* Background image and Gallery images were from multiple sources. [Pexels](https://www.pexels.com/search/hiking/) and [Unsplash](https://unsplash.com/s/photos/hiking)

### Code Sources

* Kevin Powell on [Youtube](https://www.youtube.com/kepowob) for CSS tutorials on GRID and FLEXBOX
* Responsive Design tutorials on [Youtube](https://www.youtube.com/) for responsive code in CSS - Kevin Powell, and Web Dev Simplified were particularly helpful to me. 
* Help creating responsive navigation with no JS was [Kevin Powell Youtube](https://www.youtube.com/watch?v=8QKOaTYvYUA&ab_channel=KevinPowell)
* The community on slack for feedback, and pointing me to [W3Schools](https://www.w3schools.com/) for more indepth guides to the uses of HTML and CSS. 
* Responsive media queries guidance was [W3Schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
* The guidance for the `hamburger menu` using CSS code was [unused-css.com](https://unused-css.com/blog/css-only-hamburger-menu/)

# 

## ACKNOWLEDGEMENTS:

- Code institute for the Mentors and Tutors on the course. Especially our Facilitator and Masterclass mentor [Simen Daehlin](https://github.com/Eventyret) and particularly his patience, and help with the use of flexbox, and understanding and correcting the html and css validation error fixes.
- My Mentor [Jubril Akolade](https://www.linkedin.com/in/jubrillionaire/) for guiding me in the right direction and helping me establish good coding practice. Also for his guidance and advice on developing a more responsive website.
- My fellow classmates for their ideas and enthusiasm on our facilitator sessions and masterclasses, and also their support on Slack.
- The Slack community for tips, advice, quick fixes and kind words. Especially [Chris Williams](https://github.com/Chr15w1986) who gave me great advice and pointed me in the right direction for better coding practice.
- My family for their support and patience.

#### RETURN TO THE [TOP](#take-a-hike)