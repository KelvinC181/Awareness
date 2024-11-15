# Awareness (PP1)

Awareness is my first website created on my own, it is a project to design a responsive site for mental health awareness using HTML, CSS and Bootstrap.  In the project, I try to adept a structural design process, make often and practical commits, and keep to best coding practice. Secondly, the project is also a first attemp to implicate use of AI to assist the design and coding process.  All the images excpet existing logos are generate with microsoft designer.


![Responsice Mockup](documentation/readme/readmecover.png)

## Design

To ensure a mindful product with complete features, my design process follows a logical workflow.

### User Stories

First off all, I identified users by using copilot to generate some user examples and then filtered and added my own ideas. I identified the users as mostly individuals who are seeking for help/friends and family of such individuals so our call to action is for them to find help and connecting with us. Following the same logic I then propmted copilot to generate user stories and then filtered and added my own on top.

<img src="documentation/readme/users.jpg" alt="copilot users" width=49%>
<img src="documentation/readme/stories.jpg" alt="copilot users" width=49%>

<p style="margin-bottom: 20px;"></p>

Next I created issues after identifying the acceptance criteria and tasks associate with the user stories.  With this I identified what features I would like in the website.  Finally, I then decided their importance in the website and set their priority in the project (please see the linked project Awareness User Story).

### Layout and Color Scheme/Fonts

I then used balsamic to create layouts of the three pages I planned on having.  I created 3 differnt layouts for each page targeting mobile, tablet and desktop devices.  In these layouts, I considered what I would believe to look best and is most natural to view on each screen size and designed my responsive grid/features accordingly.

<img src="documentation/readme/layout1.jpg" alt="copilot users" width=33%>
<img src="documentation/readme/layout2.jpg" alt="copilot users" width=33%>
<img src="documentation/readme/layout3.jpg" alt="copilot users" width=33%>

<p style="margin-bottom: 20px;"></p>

I picked my color scheme and fonts with consideration of users in mind.  I wanted the site to be warm and welcoming to individuals who need help, but keep a professional and clear look to appear trustworthy.  In the end, I settled on a color scheme of yellow blue and green in refernce of advice found on [this article](https://bungalowwebdesign.com/7-best-color-palettes-for-therapy-websites-in-2023-examples/).  I choose yellow as the warm basetone to the website and blue as a contrast color as text color, green is used as a feature color as green ribbon is a representation for mental health awareness.  You can find the full set of color scheme in my css file as css variables.

I picked Poppin for all headings and features to give a professional look to the website and PT serif for inner text for a softer, easier to look at style.

## Features 

In this project, all features are designed in a mobile first approach.  I build the code with mobile view in mind, then modify the code to be responsive and adjust to fit other screen sizes such as tablets and desktop.  To achieve this, I used a mix of bootstrap responsive class and custom css to modify a solid base of html structure.

### Existing Features

- __Navigation Bar__

  - Featured on all pages, the full responsive navigation bar includes links to Home page, Common Issues page, Find Help page and a button connecting to the sign up form for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

<img src="documentation/readme/navbar1.jpg" alt="navbar desktop view" width=100%>
<img src="documentation/readme/navbar2.jpg" alt="navbar tablet view" width=70%>
<img src="documentation/readme/navbar3.jpg" alt="navbar mobile view" width=50%>
<p style="margin-bottom: 20px;"></p>

- __The landing page image__

  - The landing includes an illustration with text overlay to allow the user to quicky identify the website's purpose. 
  - This section introduces the user to Awareness with a welcoming image and quickly intergrates the using to the site.

<img src="documentation/readme/landing.jpg" alt="awareness landing image" width=100%>
<p style="margin-bottom: 20px;"></p>

- __About Us__

  - The about us section describes in a more detailed manner our purpose, and also gives instruction of how to use the site. 
  - This helps first time user understand the purpose of our site and guides the user to navigate the site.  This should hopefully make it more likely that our targeted user will find the help they need using our site.

<img src="documentation/readme/aboutus.jpg" alt="about us section image" width=100%>
<p style="margin-bottom: 20px;"></p>

- __Awareness and Prevension__

  - This section gives a short introduction to the importance of awareness and prevention of mental health issues, and has an embedded video about the topic and a call to action button leading to the next section. 
  - This section highlights the importance of awareness and prevention, then gives more detail through the embedded video to encourage call to action.

<img src="documentation/readme/a&p.jpg" alt="awareness and prevention section image" width=100%>
<p style="margin-bottom: 20px;"></p>

- __The Footer__ 

  - The fully respooinsive footer section includes links to the relevant contact details and social media sites for Awareness. There is also a call to action button to contact us. 
  - The footer is valuable to the user as it encourages them to contact us to find help.

<img src="documentation/readme/footer1.jpg" alt="footer desktop view" width=100%>
<img src="documentation/readme/footer2.jpg" alt="footer tablet view" width=70%>
<img src="documentation/readme/footer3.jpg" alt="footer mobile view" width=50%>
<p style="margin-bottom: 20px;"></p>

- __Sidebar__

  - The fully responsive sidebar has links to each topic of the common issue section. 
  - This sidebar helps users navigate to the topics they want to see quickly and easily. 
  - *I would like to make the sidebar close when navbar is clicked on but this requires javascript and will be updated in the future*

<img src="documentation/readme/sidebar1.jpg" alt="sidebar desktop view" width=33%>
<img src="documentation/readme/sidebar2.jpg" alt="sidebar mobile view collapsed" width=33%>
<img src="documentation/readme/sidebar3.jpg" alt="footer mobile view" width=33%>
<p style="margin-bottom: 20px;"></p>


- __Common Issues__

  - This page containes simple information about some common mental health issues.  Each topic also contains a call to action button linking to related pages with more detailed information.
  - This page gives brief information to users and encourage them to find out more about these issues.  This should encourage users to learn about mental health and possibly identify their problem and if they need professional help.

<img src="documentation/readme/info.jpg" alt="common issue section" width=100%>
<p style="margin-bottom: 20px;"></p>

- __Resources/Find Help__

  - This page consists of bootstrap cards regarding external resources for finding help for mental health issues.  Each card contains an image of the logo of the resourse, a brief description and a call to action for the user to visit the resource.
  - This page serves as the main call to action of the website, it provides serveral resources for individuals who wants to seek help to actually find help and contact professionals, and hope to make it easy and intuative to do so.

<img src="documentation/readme/help.jpg" alt="find help section" width=100%>
<p style="margin-bottom: 20px;"></p>

- __Contact Form__

  - This is a form for users to fill in in their contact information so they could be contacted for any futhre inquiries.  A modual is included to provide confirmation that the form is submitted correctly.
  - This provides a method of call to action for users in need to seek help by providing more options to those with other unincluded mental health issues.

<img src="documentation/readme/form.jpg" alt="contact form" width=80%>
<img src="documentation/readme/modal.jpg" alt="confirmation modal" width=19%>
<p style="margin-bottom: 20px;"></p>

### Features Left to Implement

- Events Section: Contains recent mental health wellness events that are updated.
- User Testimonies: For users to sumbit and view messages and stories of their mental health journey.

## Testing 

My project went through multiple tests.  I conduct tests on features whenever I "finish" a feature and whenever I add other features that may interact with an older feature.  This allowed me to constantly find bugs and inconsitency in the project, then correct and modify the project accoringly.

At the end of the project I futher tested the website by using validators and lighthouse to validate and ensure performance of the project.

My project is full responsive, and will automatically resize and reorder items using a responsive bootstrap grid and custom css at different screensize breakpoints.  This is to ensure that the website is easy to read and good to look at with any device.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official W3C validator
  - [Home Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkelvinc181.github.io%2FAwareness%2Findex.html)
  - [Common Issues](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkelvinc181.github.io%2FAwareness%2Finfo.html)
  - [Find Help](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkelvinc181.github.io%2FAwareness%2Fresources.html)
  - [Contact Form](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkelvinc181.github.io%2FAwareness%2Fform.html)
- CSS
  - No errors were found when passing through the official W3C(Jigsaw) validator
  - [CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkelvinc181.github.io%2FAwareness%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- Lighthouse
  - Good scores were achieved in lighthouse
  - Best practice score in index.html due to youtube embed
  
  <p style="margin-bottom: 20px;"></p>
  <img src="documentation/readme/lighthouse1.jpg" alt="lighthouse for index.html" width=49%>
  <img src="documentation/readme/lighthouse2.jpg" alt="lighthouse for info.html" width=49%>
  <img src="documentation/readme/lighthouse3.jpg" alt="lighthouse for resources.html" width=49%>
  <img src="documentation/readme/lighthouse4.jpg" alt="lighthouse for form.html" width=49%>
  <p style="margin-bottom: 20px;"></p>

### Unfixed Bugs

There are a few features I would consider as "bugs" but these will require javascript to amend, and will be updated in the future.
- navbar should close when anywhere else is clicked on the screen.
- sidebar should close when anywhere else is clicked on the screen.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab and pages section 
  - From the source section drop-down menu, select the main branch
  - Click save and the page will be automatically deployed 

The live link can be found here - https://kelvinc181.github.io/Awareness/


## Credits 

This project was done during CI full stack developer bootcamp.  The design process, some page structures and features are inspired by and further developed on from the walk-projects of the course.

### AI Assistance Declaration

This project was developed with the assistance of AI tools, including GitHub Copilot. These tools were used to help generate code snippets, provide suggestions, and improve overall productivity during the development process. While AI tools provided valuable assistance, all final decisions and implementations were made by the project developer.

### Content 

- All text content are prompted and created by GitHub Copilot and futher modifed to fit the website.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Fonts can be found on google fonts

### Media

- All illustrations used on the home and common issues page are generated using Microsoft Designer
- The logos for the find help page were taken from google search:
- [Mental Health Foundation Logo](https://www.google.com/imgres?q=mental%20health%20foundation%20logo%20mhf%20logo&imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Ff%2Ffd%2FMHF-logo24.png&imgrefurl=https%3A%2F%2Fen.m.wikipedia.org%2Fwiki%2FFile%3AMHF-logo24.png&docid=0MafQ6GVi-dk9M&tbnid=jiPm8OkXWKvYbM&vet=12ahUKEwiY-rPIrtmJAxUvVkEAHaXiLnQQM3oECGwQAA..i&w=823&h=690&hcb=2&ved=2ahUKEwiY-rPIrtmJAxUvVkEAHaXiLnQQM3oECGwQAA)
- [Mind Logo](https://www.google.com/imgres?q=mind%20logo&imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fen%2Fa%2Fab%2FMind_Charity_Logo_2021.png&imgrefurl=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FMind_(charity)&docid=tZcH5rHasZ-zNM&tbnid=DC_qlv7ngSqYdM&vet=12ahUKEwi_-r7trtmJAxWgRUEAHaVsCloQM3oECBkQAA..i&w=421&h=237&hcb=2&ved=2ahUKEwi_-r7trtmJAxWgRUEAHaVsCloQM3oECBkQAA)
- [Samaritans Logo](https://www.google.com/imgres?q=Samaritans%20logo&imgurl=https%3A%2F%2Fstorage.googleapis.com%2Felasticsauce.appspot.com%2Fgoodmoves-files%2F0683z00000HWJqEAAX-samaritans-core-green-logo.png&imgrefurl=https%3A%2F%2Fgoodmoves.org%2Forganisation%2F001b000000St65pAAB%2Fsamaritans&docid=oVc6p6U4rp-RVM&tbnid=Qku9rpQcKL5CRM&vet=12ahUKEwii3dmwr9mJAxVeX0EAHYgGJI4QM3oECEgQAA..i&w=728&h=194&hcb=2&ved=2ahUKEwii3dmwr9mJAxVeX0EAHYgGJI4QM3oECEgQAA)
- [Rethink Mental Illness Logo](https://www.google.com/imgres?q=rethink%20mental%20illness%20logo&imgurl=https%3A%2F%2Fwww.arthritisaction.org.uk%2Fwp-content%2Fuploads%2F2019%2F07%2FRethink-Mental-Illness-logo.png&imgrefurl=https%3A%2F%2Fwww.arthritisaction.org.uk%2Fmhdirectory%2Frethink-mental-illness%2Fattachment%2Frethink-mental-illness-logo%2F&docid=zURQVgi9iSAdjM&tbnid=l47bJ2WxYqdKvM&vet=12ahUKEwih7u_Tr9mJAxULVUEAHU3_BhcQM3oECBcQAA..i&w=4124&h=4123&hcb=2&ved=2ahUKEwih7u_Tr9mJAxULVUEAHU3_BhcQM3oECBcQAA)

