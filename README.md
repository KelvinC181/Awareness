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

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 