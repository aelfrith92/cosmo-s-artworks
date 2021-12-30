![Site Logo](docs/readmeImages/hairstyle-readme.png)
## Table of Contents
* [Purpose](#Purpose)
* [User Experience Design (UX)](#User-Experience-Design)
  * [User stories](#User-Stories)
    * [First Time Visitor Goals](#First-Time-Visitor-Goals)
    * [Returning Visitor Goals](#Returning-Visitor-Goals)
  * [Structure](#Structure)
  * [Design](#Design)
    * [Colour Scheme](#Colour-Scheme)
    * [Typography](#Typography)
    * [Imagery](#Imagery)
    * [Wireframes](#Wireframes)
    * [Differences to Design](Differences-to-Design)
* [Limitations](#Limitations)
- [Features](#Features)
    * [Existing Features](#Existing-Features)
    * [Future Features](#Features-Left-to-Implement)
* [Technologies](#Technologies)
* [Testing](#Testing)
    * [Test Strategy](#Test-Strategy)
      * [Summary](#Summary)
      * [High Level Test Cases](#High-Level-Test-Cases)
      * [Out of Scope](#Out-of-Scope)
    * [Test Results](#Test-Results)
    * [Testing Issues](#Issues-and-Resolutions-to-issues-found-during-testing)
* [Deployment](#Deployment)
    * [Project Creation](#Project-Creation)
    * [GitHub Pages](#Using-Github-Pages)
    * [Locally](Run-Locally)
* [Credits](#Credits)
  * [Content](#Content)
  * [Media](#Media)
  * [Acknowledgements](#Acknowledgements)
  * [Comments](#Comments)

# Milestone Project 1
## Purpose
The website is meant to present and show off my father's craftsmanship to everybody. At the same time, it has been created for the sole purpose of completing the first Milestone Project for the Code Institute's Full Stack Developer course.
The knowledge gained from the HTML, CSS, and User Centric Design modules played a key role in developing the web page, even though a full list of the employed technologies can be found in the technologies section of this document.

The live website can be found [here](https://aelfrith92.github.io/cosmo-s-artworks/).

## Cosmo's Drawing - Responsive Website

![Website Mock Up](docs/readmeImages/multi-device-mockup.jpg)

My father - Cosimino Morieri, the client - always wished he had a personal website, to showcase his works to friends and acquaintances. As I had already developed fully responsive websites in the past, I started coding bearing the responsiveness in mind. There is no profit purpose behind this web page. The website will provide an essential overview about his works (what he does) and his background. 

*** 
## User Experience Design

### User stories
#### First Time Visitor Goals
* As a First Time user, I want to easily understand the main purpose of the site and learn more about the artist.
* As a First Time user, I want to be able to easily navigate throughout the site to find content.
* As a First Time user, I want to view the website and content clearly on my mobile device.
* As a First Time user, I want to find ways to follow Cosimino's activities on different social media platforms.
#### Returning and Frequent Visitor Goals
* As a Returning and Frequent user, I want to share the content with friends and have a look at the gallery.
* As a Returning user, I want to contact Cosimino, so I can request more information.

### Structure
The site contains just one single page for the time being. A gallery page will be added in the future, as the visual resources need a format conversion, in order to optimize data streaming and performance.

The Navigation Menu allows users to easily navigate the different sections of the web page, even on smaller devices thanks to the responsive and collapsable version of the same. It contains the icon chosen as website logo, retrieved by flaticon.com and fully licensed. Visit the folder "flaticon_licenses" within the root for further details. Same applies to the Burger Menu icon (further details about it in the following paragraphs), the wood icon, the iron icon, the email icon. No attribution is required.

The purpose of this is to fulfill the aforementioned user's story:
> As a First Time user, I want to be able to easily navigate throughout the site to find content.

The Home Page contains a brief overview about Cosimino's background and crafted works.
The purpose of this is to fulfill the aforementioned user's story:
> As a First Time user, I want to easily understand the main purpose of the site and learn more about the artist.

Custom CSS and Bootstrap 5.1.3 will be employed to make the Website responsive by the use of media queries, the Boostrap Grid system, and flexboxes CSS properties. All sections contain code that overrides Bootstrap pre-set style.

The main page (as well as the future gallery page) will be responsive. There is just one chosen layout breakpoint, which triggers the alternative views of contents, namely, 768px as maximum width. 
Images have been converted, scaled, and included in the code so that they are accessible and light, in terms of data streaming and performance. A minimum height and a responsive width have been set, so that they are still visible even at narrow viewport widths.
The purpose of this is to fulfill the aforementioned user's story:
> As a First Time user, I want to view the website and content clearly on my mobile device.

The main page will contain a Contact Us section, which will allow the user to reach out to Cosimino in an easy and straightforward way. All form elements are required, to submit a clear and comprehensive enquiry.
The purpose of this is to fulfill the aforementioned user's story:
> As a Returning user, I want to contact Cosimino, so I can request more information.

All pages will contain a Footer Element with Social Media Icons. The icons used will be
from font-awesome. These are referenced below in the Frameworks-Libraries-and-Programs-Used section of this document. 
The aim of the Footer elements are to fulfill the aforementioned user's story:
> As a First Time user, I want to find ways to follow Cosimino's activities on different social media platforms.<br>

The Gallery Page (to be developed) will contain a rich number of Cosimino's artworks, all designed by following the flexbox responsiveness layout showed [here](https://www.w3schools.com/css/css3_flexbox_responsive.asp).
The purpose of this is to fulfill the aforementioned user's story:
> As a Returning and Frequent user, I want to share the content with friends and have a look at the gallery.

### Design
#### Colour Palette
The main colours used have been mainly inspired by the Bootstrap [Warning theme](https://getbootstrap.com/docs/5.1/customize/color/), alongside a related color palette retrieved on colorhunt.co [here](https://colorhunt.co/palette/ffcc1d0b4619116530e8e8cc). Following my mentor's advice, I have replaced the color #116530 with a darker shade, to improve the contrast rate of text-background and - consequently - the experience for visually impaired users.
#### Typography
The headers on all pages throughout the Website are using:
- the **Montserrat** font as a global parameter;
- the **Roboto Condensed** font applied to h1, h2, and h3 tags;
- the **Ubuntu Condensed** font applied to the text next to the logo, to give it a unique and minimal style within the page.<br>
Fonts have been imported from Google Fonts website, using the @import instruction at the top of the custom style.css file.
#### Imagery
The Brand icon is fictional. I have employed an icon downloaded by flaticon.com which would have resembled my father's look somehow, namely, depicting a moustache. However, I am not the only one having the exclusive right to employ such an icon as a resource on one's website. I have chosen the svg format, as it renders an excellent quality with a minimal memory allocation.

As mentioned above and except for the social media icons in the footer which come from fontawesome, these icons have been downloaded from flaticon.com and are fully licensed.

Other pictures within the web page have been converted into a webp format, to optimize data streaming and performance.

#### Wireframes
![wireframe](docs/readmeImages/wireframing.jpg)<br>
I have drafted sections and content on a paper sheet and then I have developed the actual content by employing the following layout stratgies:
- [Bootstrap grid](https://getbootstrap.com/docs/5.1/layout/grid/);
- Custom CSS;
- [Flexbox responsivness](https://www.w3schools.com/css/css3_flexbox_responsive.asp).

Before adding content in each section, I firstly use to assigning different background colours to the containers, to see their behaviour. Once they meet my expectations, I add the content.

#### Differences to Design
In the original design, multiple pages had been projected. After the second session witht the mentor, we came to the conclusion that a single page could have met all needs. The bottom part of the page was not completely clear in the wireframing step, so it may differ from the one depicted.
### Limitations
Due to no JavaScript functionality, apart from Bootstraps(JS/JQuery), the contact form will not store data or send email requests. Due to other reasons, the gallery page has been postponed, as a hundred of photos need to be converted and scaled. Initially, a Bootstrap carousel had to be inmplemented, but it is now a pending feature.
***
## Features
 
### Existing Features
- The Welcome picture is linked to an animation
- Each section is responsive
- The contact form lets the user reach out to Cosimino with any queries they may have

### Features Left to Implement
- A gellery page can definitely complete the user experience, given the countless works that Cosimino have created
- A carousel within the main page
- A "Back to the top" button to let the user navigate faster within the contents of the same page
- An embedded google maps frame (showing a fictional location)
- clearer and more concise/catchy language
***
## Technologies

* HTML
  - This project uses HTML as the main language used to complete the structure of the Website.
* CSS
  - This project uses custom written CSS to style the Website.
* [Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/) 5.1.3
  - Given the past experience with Bootstrap, I have used it as main technology to define a responsive behaviour among the several sections. The Bootstrap Grid system and the navigation bar have been easily designed thanks to the pre-set features coming from bootstrap, even though most of time both layout and style have been overridden by custom CSS code. I am in fact fully aware of the underlying Bootstrap features. Please, notice the responsive sections manually designed with custom CSS and flexboxes.
* [Font Awesome](https://fontawesome.com/)
  - Font awesome Icons are used for the Social media links contained in the Footer section of the website.
* [Google Fonts](https://fonts.google.com/)
  - Google fonts are used throughout the project to import the aforementioned fonts, with specific font-sizes, through the @import instruction at the top of the custom CSS file.
* [Replit](https://replit.com/@FredM2)
  - ** Replit is the Integrated Development Environment used to develop the Website. After the first commit via gitHub, the following ones have been triggered via Replit shell. As for permissions, gitHub only required to generate a token to push, which I have stored locally in the "Secrets (Environmental Variables)" area. FredM2 is my username and Replit signature. **
* [GitHub](https://github.com/aelfrith92)
  - GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
  - Past personal projects have been used to get inspiration for the current milestone project. 
* [Git](https://git-scm.com/)
  - Git is used as version control software to commit and push code to the GitHub repository via Replit, where the source code is stored.
* [GIMP](https://www.gimp.org/)
  - Gimp is used to convert, scale, and reduce the file sizes of images before being deployed to reduce storage and bandwidth.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
  - Google chrome built-in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles. In particular, it came handy when troubleshooting layout and boxes.
* [CSS Generator](https://cssgenerator.org/rgba-and-hex-color-generator.html)
  - This was used to convert the RGBA colour for the site to Hex. 
* [Flaticon](https://www.flaticon.com/)
  - Flaticon has been used as main icon repository.
* [Colorhunt.co](https://colorhunt.co/)
  - Colorhunt has been used to identify the best color palettes and shades
* [Wood-database](https://www.wood-database.com/)
  - Wood-database has been used to retrieve part of the wood textures implemented in the categories sections.
* [Mentor's read.me template](https://github.com/Daisy-McG/MilestoneProject-1/blob/master/README.md)
  - This read.me file has been drafted following the advice returned by the mentor, as well as following suggestions released on the course modules.
***
## Testing

### Test Strategy 

#### Summary 

Testing is required on MilestoneProject-1 – Cosmo's Drawing.

- As this project is static and contains no back-end functionality, the testing performed will be on the visual effects and layout of the Website. Testing to be done on at least three web browsers (Google Chrome, Apple Safari, Mozilla Firefox) and all screen sizes.

- No elements should overlap another container div.

- All nav links should direct to the correct html relative references within the page, as per their names.

- All links to external websites must open in a new browser.

- Testing of form validation will also be required to ensure the correct inputs are taken and that all fields are required.

- Code validation tools for [HTML](https://validator.w3.org/) and [CSS](https://jigsaw.w3.org/css-validator/)

- [Lighthouse](https://developers.google.com/web/tools/lighthouse) tool by Google Chrome

- [Waive](https://wave.webaim.org/) - Google Chrome plug-in to test common code errors and warnings, which encompass accessibility features and best practices.

- The live Project can be found [here](https://aelfrith92.github.io/cosmo-s-artworks/).

### Test Results
- The animation, links, images, Bootstrap layouts, custom layouts of containers behaved as expected on 3 different browsers.
- No overlapping detected.
- Nav links and external links behave as expected.
- Form validation returns all variables correctly assigned to each HTML "name" attributes
- Code validation returned no errors 
- Lighthouse returned the following outcome
    ![lighthouse](docs/readmeImages/lighthouse.jpg)

  

### Issues and Resolutions to issues found during testing
indentation
radio inputs align
lighthouse

* Clicking the logo doesn't redirect to home page. This was resolved by updating the href on all Pages.
* Photo alignment issue on Home Page, this was fixed by adding bootstrap classes d-flex align-items-center and img-fluid.
* YouTube video on Events page was causing overlapping on small screens due to having a fixed size. This was resolved by removing fixed width and height and setting img-fluid in the div.
* Navigation menu items were being covered on smaller screens due to amount of items and text not shrinking. This was resolved by adding a media query between min width 576px and max width 654px that changes to a smaller font size.
* Spelling mistakes were found when proof reading, these were corrected.
* About page Meet the member section photos and text were overlapping on medium and below screens. This was fixed by correcting column sizes and adding class member-alignment with corresponding css styling.
* On extra wide screens content was being stretched across the entire width of the screen. This was fixed by changing container-fluid to container.
* Modal Booking form was accepting any inputs in fields. This was resolved by adding the required attribute to all fields.
* Carousel on Events page was expanding the full width of the screen, this was causing the images to be distorted and strected. This was resolved by by adding a maximum height and width to the containing div.
* On the Gallery page, the HR was sitting beside the title on large and medium screen sizes. This was resolved by wrapping the titles into a a div and assigning col-12 class.
***
## Deployment

### Project Creation
The project was started by navigating to the [template](https://github.com/Code-Institute-Org/gitpod-full-template) and clicking 'Use this template'. Under Repository name I input MilestoneProject-1 and checked the Include all branches checkbox. I then navigated to the new [repository](https://github.com/Daisy-McG/MilestoneProject-1). I then clicked the Code drop down and selected HTTPS and copied the link to the clipboard.

Opening a bash terminal in Visual studio code I then typed git clone [link from clipboard](https://github.com/Daisy-McG/MilestoneProject-1.git) followed by open folder and navigating to the newly created local repository. The following commands were used throughout the project:

* git add filename - This command was used to add fils to the staging area before commiting.
* git commit -m *commit message explaining the updates* - This command was used to to commit changes to the local repository.
* git push - This command is used to push all commited changes to the GitHub repository. 

### Using Github Pages
1. Navigate to the GitHub [Repository:](https://github.com/Daisy-McG/MilestoneProject-1)
1. Click the 'Settings' Tab.
1. Scroll Down to the Git Hub Pages Heading.
1. Select 'Master Branch' as the source.
1. Click the Save button.
1. Click on the link to go to the live deployed page.

### Run Locally
1. Navigate to the GitHub [Repository:](https://github.com/Daisy-McG/MilestoneProject-1)
1. Click the Code drop down menu.
1. Either Download the ZIP file, unpackage locally and open with IDE (This route ends here) OR Copy Git URL from the HTTPS dialogue box.
1. Open your developement editor of choice and open a terminal window in a directory of your choice.
1. Use the 'git clone' command in terminal followed by the copied git URL.
1. A clone of the project will be created locally on your machine.

***
## Credits
### Code
The code to style the check-box background color was taken from the comments of [Stackoverflow post](https://stackoverflow.com/questions/24322599/why-cannot-change-checkbox-color-whatever-i-do)
### Content
The content of this software was created by Daisy McGirr based upon discussions with Ronnie Robinson, Hair O' The Dog MCC.

### Media
The photos and video used in this video are property of Hair O' The Dog MCC. Permission was granted to use all media files by Ronnie Robinson, club Founder.
The YouTube video on the events page is property of Marijus Ltu. Permission was obtained to use this video.

### Acknowledgements

I'd like to thank my mentor Spencer Baribell for his guidance throughout my project.<br>
Thanks to fellow classmate @Jay Bradley for helping me figure out how to link my TOC to headings with spaces.<br>
I'd like to give a special mention to past students Anthony and Mr_Bim_alumni who guided me and helped me learn to debug with developer tools whenever I faced alignment issues with my Website.<br>

## Comments
Git commits are showing up as two contributors, one as Your Name and one verified as Daisy-McG. This was caused by pushing without setting a signature for commits from VS Code, a signature was added on 25/10/2020 and all new commits are now verified. All commits were pushed by Daisy McGirr.