# README for Beer.com

## Intro

This website has been developed for a new start-up called, Buy Me a Beer.com, a new online donation service.  The start-up founder's core goals for the website are:

- To inform potential users of the new service
- To gauge the level of interest/popularity in the new service
- To generate leads for potential content creators

![image of mockups](assets-readme/README-mockup.png)

[live site](https://josephwoodland.github.io/beer.com/)

## Index

- <a href="#The-Website-Brief" >The Website Brief</a>
  - <a href="#brief-agoals" >Audience Goals</a>
  - <a href="#brief-Wgoals" >Website Goals</a>
  - <a href="#brief-insperation" >Inspiration</a>
  - <a href="#brief-summary" >Summary of the brief</a>
 
- <a href="#ux">UX</a>
  - <a href="#ux-journey">User Journey</a>
  - <a href="#ux-sections">Sections of the website</a>
  - <a href="#ux-wireframese">Basic Wireframes</a>
- <a href="#design">Design</a>
  - <a href="#design-fonts">Fonts</a>
  - <a href="#design-style">Imagery and Style</a>
  - <a href="#design-features">Features for the website</a>
  - <a href="#design-tech">Technologies Used</a>
  - <a href="#design-scss">Architecture - SCSS</a>
  - <a href="#design-vs-code">VS Code</a>
  - <a href="#design-node">Node modules</a>
  - <a href="#design-libaries">Outside libraries</a>
  - <a href="#design-classes">CSS Pseudo-classes</a>
  - <a href="#design-used">Software Used</a>
  - <a href="#design-resources">Online resources</a>
- <a href="#testing">Testing</a>
  - <a href="#testing-auto">Automated Code Validation</a>
  - <a href="#testing-manual"> Manual testing</a>
  - <a href="#testing-responsive">Testing - Design Responsiveness</a>
  - <a href="#testing-resolved">Major testing issues identified</a>
  - <a href="#testing-user">User testing</a>
  - <a href="#testing-checklist">Testing Checklists</a>
  - <a href="#testing-ressolved">Issues and challenges I encountered</a>
- <a href="#deployment">Deployment</a>
- <a href="#future">Future Features</a>
- <a href="#credits">Credits</a>


- <span id="#The-Website-Brief"></span>
  
# The Website Brief

This is a copy of the [brief](assets-readme/Website%20Guideline.pdf)

### Target Audience

There are two target audiences for the website:

- General users (Users): users who want to donate a gift to someone, by donating the value/amount of the gift they want to send. These are also the existing and target audience for Content Creators.
- Content Creators (Creators): visitors who create content and want another medium to promote their content to fundraising/generate additional income through donations or gifts received. This audience is how the client will make money, taking a percentage of the donations they receive. As the content creators targeted are primarily desktop users, this site will have a desktop-first approach to design.

  - <span id="#brief-Agoals"></span>
  
## Audience Goals

### Users

- As a user, I want to understand what the donation service is
- As a user, I want to how this donation service is different from other donation services
- As a user, I want to register for more information.

### Creators

- As a creator, I want to understand how I can use this donation service to fundraise/ receive donations from fans and followers.
- As a creator, I want to register my interest to use the service.
- <span id="#brief-Wgoals"></span>
  
## Website Goals

### Users

- To measure interest in the donation service to indicate the potential/scalability of the user base
- To track user activity across the site; tracking unique visitors, repeat site visitors, duration on-site, and other related site metrics to validate user interest.

### Creators

- To gauge the interest of existing or potential creators who generate income through creating content on social media.
- To obtain contact information from creator audiences/visitors; primarily by email as well as through social media handles.
- <span id="#brief-insperation"></span>
  
## Inspiration

This site was inspired by elements of the following competitor websites. These sites, like Beer.com, have two distinct audiences each with a different objective/use for the services provided. These sites create a space for each audience, in some using a search function for donors/users while directing creators/fundraisers to sign up/in. It's essential for a quality UX that Beer.com also delivers a clear user journey and experience for each target audience. To deliver this, I was inspired to produce a separate page for the Creator audience, to separate the journey and experience between Creators and Users so each receives the experience and journeys they need to fundraise and donate respectively.

[BuyMeACoffee](https://www.buymeacoffee.com/)

[Patreon](https://www.patreon.com/)

[Just Giving](https://www.justgiving.com/)

<span id="#brief-summary"></span>
 

## Summary of the brief

The site should have a clean, clear, and simple layout so the visitor can easily find and quickly understand the site’s purpose and offering.

The site should be easy to navigate for both target audiences, even if they will use the site in different ways or require different information. Both target audiences should be able to leave their contact details to receive further information.

There should be several opportunities for site visitors to engage and interact with the site content, easily and functionally.

The sites’ content should be relevant, concise, and engaging without having unnecessary information. There should be nothing on the site without a purpose or that does not add value to the site objectives or building the brand image.

The site should conform to brand guidelines and the brand TOV, look and feel. These should be relaxed, friendly, and inviting.
- <span id="#ux"></span>
  
# UX
- <span id="#ux-journey"></span>
  
## User Journey

This is an example of a successful user journey for both audiences.

### The User

- I have been redirected to the hero section of the home page from an ad on my Facebook app using my Google Pixel 3.
- I am looking for more information about the service that Beer.com provides.
- I've read the hero home page section and now understand Beer.com allows me to donate to anyone for any reason. I'm still interested and now want more detailed information on how I can get involved.
- I click the hero section call to action button for 'More Information' or scroll down to see the 'More Information' section immediately below.
- I now have all the information I need and would like to register (for more information at a later date). I click the 'Contact us' button in the header and complete the 'Contact Us form.
- I've completed the form and before leaving the site I click one of the social icons in the footer to follow Beer.com on social.
- I feel really good about the experience, it only took a few minutes, my questions were answered and I don't have to do anything else as I know I will be contacted later.

### The Creator

- I have followed a link from an advert on the content live streaming platform I use while editing a video on my Macbook.
- I have been redirected to the hero section of the Creator page.
- I've read the hero Creator page section and now understand Beer.com helps content creators like me to fundraise.
- I'm still interested and now want more detailed information on how I can use Beer.com to make money through my content creation.
- If I'm eager I want to get in touch right away so I click the 'Contact Us' button in the hero section which stands out. If I want a little more information I scroll down to immediately see 3 clear simples 'How it works' steps.
- I now understand exactly how I can use Beer.com to start making money with my content creation. I'm excited it was so straightforward and simple and I click 'Contact Us' to register my interest and details.
- I want to keep up to date with Beer.com so I click their Twitter icon in the footer before I leave the site.
- <span id="#ux-sections"></span>
 
## Sections of the website

### General Layout

When deciding the most appropriate screen size for the site, I took into account the user goals and the client brief. As the Creators are the primary revenue target for the client, and predominantly desktop users, I chose the screen dimensions below. This choice was validated by my research, which showed this is one of the most popular/widely used screen formats for desktop heavy users. Looking at [statcounter](https://gs.statcounter.com/screen-resolution-stats/desktop/worldwide)

-1920x1080px

-1366x768px

I adopted these guidelines throughout the website, with a formatted width of 1366px and a height for the linked hero section of 768px.

The website needed to be fully responsive, taking into account that 55% of websites are viewed from mobiles and knowing the client is using social media advertising to target possible users.

### Navigation bar

The navigation bar must be accessible throughout the website, with clearly marked sections to navigate around the site.

### Landing/Creator page

The pages for each target audience group should be consistent in layout and flow where possible.

### Hero Section

To meet the client brief and user journey expectations, the landing section will be clear, concise, and informative. This approach will be consistent across all site pages for uniformity and consistency. The concise layout/approach is key to ensuring users understand the business concept within the first moments of landing on the page. When building this section I will ensure there is a clear call to action button to encourage/direct the user to take the next action on the site.

### Information/How to section

A key requirement is to inform the user of how they can sign up and use the service, therefore I will include a clear section dedicated to this. I will create a simple and uncluttered Information section as this section’s purpose is to provide the user with the information they need to progress through their site journey; rather than overwhelm with too much content in one section.

### Form section

This section has a simple but important function, to capture the right contact data to ensure the client can re-engage with users directly. It's key for the UX the form does not look overbearing to complete, therefore the form will be restricted to requesting essential contact information only.

### Footer

Like the Hero section, the footer will be consistent throughout the website. It will feature and promote social media links and icons. This is a familiar convention that most sites adopt and that the users will likely expect to see and understand the social icons are linked to relevant social accounts.
 - <span id="#ux-wireframese"></span>

## Basic Wireframes

Here is a sample of the original wireframes for the desktop site that was approved by the client.

![desktop](assets-readme/xd/Blue/Landing-info-%20Page%20w-1920px.png)

Other wireframes are [here](assets-readme/xd/Blue/Beer-Wireframes.xd)
- <span id="#design"></span>
 
# Design

The design elements were influenced and informed by the client’s brief, specifically the client’s brand guidelines which included the look and feel and TOV (tone of voice).
 - <span id="#design-fonts"></span>

## Fonts

### Main copy

-Noto Sans JP and as a back up sans-serif

### Heading copy

-Acumin Pro and as a back up of serif;
  - <span id="#design-style"></span>
 
## Imagery and Style

- I used a hero image of a group of people sharing a drink, to tie in the website/client business name and purpose. I decided to overlay the image with a filter so the image appears, as an illustration, to soften the image.
- I recognised the original image was too distracting, drawing attention away from the intro copy. The addition of the filter balanced the image and allowed it to sit more succinctly and naturally within the homepage banner, balancing well with the hero copy.
- I included illustrative icons to demonstrate the actions users should take, to bring the content to life, and make sure the site was not to text heavy in content. This decision was informed by my research and other sites that had a strong UX and the trend of these sites incorporating similar features.
- I kept the flow of the site engaging and fun by using hand-drawn graphic elements. For example, the borders between the site sections have hand-drawn lines, providing a slightly uneven surface that delivers a more human touch feel and experience to the site.
- I layered different textures to bring content to life; overlaying text above hand-drawn graphic elements. This stopped the site from feeling corporate and block-structured.

### Main colors

Brand colours are ![brand](assets-readme/brand-colours.png)

Example of the branded wireframes:

![wireframes](assets-readme/xd/Branded/Landing-info-%20Page%20w-1920px.png)

More wireframes can be found [here](assets-readme/xd/Branded/Beer.com-HF.xd)
 - <span id="#design-features"></span>

## Features for the website

### Responsive design on all devices

- Website must be responsive.

### Interactive pages

- Visitors must be able to navigate between pages.

### Links to email contacts

- Visitors must be able to contact the clients through the built-in contact form.

### Links to social media

- Visitors must be able to link to the brand's social media pages.
  - <span id="#design-tech"></span>
 
## Technologies Used

### Languages

HTML5 - I used HTML 5 for the layout and structure of the website.

CSS - CSS has been used to style the HTML5 elements
 - <span id="#design-scss"></span>

## Architecture - SCSS

As I am coding different pages with many reused elements throughout the website - which could potentially also need individual formatting tweaks - I decided to use a CSS Preprocessor on this project.

Using the import feature of SCSS would first allow me to structure the architecture of the project in a much cleaner way. This style of architecture allows for smaller files that can be easily connected.

Besides,  allowing the use of variables makes the site maintenance smoother, and helps significantly with the responsive design. Giving the option to just change the variable and this will change every time that variable has been used throughout the code.

Using the nesting feature of SCSS allows for cleaner code making site up-keep and bug fixes easier to locate and address.
  - <span id="#design-vs-code"></span>

## VS Code

I used VS Code as my code editor. In the code editor, the extensions that I used were:

- Prettier - to automatically format my code for basic formatting mistakes and to have a consistent style throughout the code.
- Npm - I used this extension to give npm support for the version of VS Code I have.
- Image preview - I used this extension that shows a preview of any linked images in my code to help me quickly identify if the URL path is correct and to identify the right image.
- Markdown all in one - I used this which enabled me to edit the readme file with live preview in VS Code.
  - <span id="#design-node"></span>
 
## Node modules

I used basic node modules to help me code in a smoother and more organised approach.

- Devsever - I used the dev server module to live to reload my project, on a change of the code. This made it easier to see changes I had been making to the code.

- Node-sass - I used this to node so I could use the SCSS file and architecture.

- Watch sass - I used this module to compile the SCSS structure and architecture that I was using into a CSS format.

- Autoprefixer - I used this extension to add prefixes to my code for added browser support.
- Font Awesome - I       used this extension to integrate free icons into the page.
 - <span id="#design-libaries"></span>

## Outside libraries

- Unsplash images - I used this library for the hero image on the website.

- Adobe font Typekit - I used the Adobe font library for the font family on the website.

- Google fonts - I used Google fonts for one of the font families on the website.
  - <span id="#design-classes"></span>
 
## CSS Pseudo-classes

- Hover: I used the hover class to change the state of various items over the page, all buttons, and icons. This is a familiar convention that signals to the site visitor the interactive site elements/features they can engage with.

- Active: I used the active class to change some CSS properties of an object to indicate to the visitors that this object has been interacted with.

- Focus: I used the focus class for visitors to the website who need extra accessibly support when navigating the website.

- Target: I used the target class to activate the modal on the interaction of the profile icon.
 - <span id="#design-used"></span>

## Software Used

- Git - This was used to manage the different versions of my project, using different branches to test and add new features/sections to the website. Once tested they were then merged into the master branch and then, using Git Desktop pushed to the Git Hub repository.

- Git Desktop - I used this to manage commits and push them to the GitHub repository

- GitHub - I used GitHub to store the version of the project remotely.

- Adobe XD - I used XD to create and build the wireframes, to design some of the unique icons on the page and the unique color patterns on the page.

- Photoshop - I used photoshop to edit the hero image on the page, I used some filters on the image to create the illustrated filter effect on the image.
- <span id="#design-resources"></span>

## Online resources

### [W3 Schools](https://www.w3schools.com/)

### [Stack Overflow](https://stackoverflow.com/)

### [Code Pen](https://codepen.io/)

### [npm](https://www.npmjs.com/)

### [MDN](https://developer.mozilla.org/en-US/)
- <span id="#testing"></span>
 
# Testing
 - <span id="#testing-auto"></span>

## Automated Code Validation

I passed the code through the online code checking tool [w3validator](https://validator.w3.org/)

- Html Code has passed through the validator with no issues.

- CSS code passed through the validator with no issues. I have three warnings that I believe are necessary for the website to run. Two are around importing the fonts into the stylesheet. The other is a warning around using pointer-events, which I need to be able to close the modal.

### Chrome DevTools

I completed an audit on all pages for mobile and desktop.

- ### Performance = Good

This test was well performing across all sites and pages scoring 100 on a desktop on 96 across the mobile pages.

- ### Accessibility = Good

   This test was also performed well, with 90 on mobile, 92-93 across the desktop pages, and being marked down on the font awesome icons imported for the footer using [aria-hidden=” true”]. I researched to investigate if I could change this outcome, however, I could not find a solution. In addition, the score was marked down due to there being a lack of contrast between foreground colors and background. This was a result of a design decision that I am reluctant to change. I checked the areas highlighted with this issue and believe there is sufficient contrast for the users to understand the text, without impacting the quality of their UX or ability to engage with the site.

- ### Best Practices = Good

   High performing across all pages and formats, 93 and above. Made down due to an incorrect aspect ratio of an icon. After investigation, I believe this is not an issue that needs a resolution. The aspect is .09% out on a small icon that is sized to fit in place on the center grid.

- ### SEO = Good

   100 on all pages both desktop and mobile.
  - <span id="#testing-manual"></span>

## Manual testing

### Testing Environments

I used branches in Git to create a safer environment to develop different features and sections of the website. Once the initial section/feature had been finished and the initial test had been completed, the branch would merge with the master branch. Initially, I would delete the branch but after a consultation with my mentor, I decided to keep them for reference.

I used two sets of hardware to undergo building and completing the tests for the website; using a 28 inc iMac and a 13inch Mackbook air with the M1 processor. On both, I was primarily using the Google Chrome web browser. Testing on other environments has been completed remotely; due to the COVID-19 lock-down restrictions I have not been able to use other people’s equipment to test on, however, I am confident the remote testing was still sufficient.

### Desktop testing

Platforms :

- Mac book air 2020 M1 -OS Big Sur
- iMac - OS Catalina

Browsers:

- Chrome
- Firefox
- Safari

Mobile testing:

- Pixel 3 (Android 11)
- iPhone 7 (IOS 14)

Browsers:

- Chrome
- Safari
  - <span id="#testing-responsive"></span>

## Testing - Design Responsiveness

### Simulated Testing

For each section on each page, I tested various screen sizes in the development environment. Using the Google Developer tools I tested the responsiveness throughout the development process. I updated the code as I tested, noting anything that appeared irregular or out of sync with the layout of the page.

Tested with Chrome DevTools using profiles for with screen sizes:

- Moto G4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5 SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad
- iPad Pro

Also used the responsive profiles preset in the dev tools of:

- Mobile S (320px)
- Mobile M (375px)
- Mobile L (425px)
- Tablet (768px)
- Laptop (1024px)
- Laptop L (1440px)
  - <span id="#testing-resolved"></span>

## Major testing issues identified

       1. Issue: Safari on a desktop in a small window and on a small iPhone screen would cut off the bottom of sections.
       Resolution applied: increasing the pixel height of certain sections on a small screen.
 
       2. Issue: Using my pixel in portrait mode on the contact page would encounter a bug where the placement on the icons inside the input boxes would be off-screen, creating white space.
       Resolution applied: I fixed this by changing the containing div to `display: flex;` and re-formatting the icon to appear on the left hand side of the input box.
  - <span id="#testing-user"></span>

## User testing

To test if the layout of the website would deliver the client’s goals, I used two groups each with 5 new users to use the website. One group was the 'user' audience and the other the 'creator' audience.  The overall results of this test are as follows.

### User Tests

- What did most users remember about the business after the 5-second showing?

       The constant feedback was that Beer.com is about gifting drinks or meeting up with friends and family.

- What did users remember about the sign-up process?

       Everyone recognised that you can sign in by using their existing social media accounts.
- After asking the Creator to try and contact Beer.com, how did they get on? Could they find the Social Media links?

       All test users understood where to find the 'Contact Us' form very quickly. One user spent a little more time than the other users on the top of the page to locate the link. though all others scrolled down to locate the form very quickly and easily.
 
       Social media links were found by all users within 10 seconds of the question being asked.

### Creator Tests

- What did the test subject remember after 5 seconds on the hero section of the creator page?

       Beer.com is something to do with earning more money from content.

- How did the test subject remember how the service works?

       All seemed familiar with using services to get paid for content but unsure of the specific way that the company would go about that.

- Would you contact the company for more information about the service?

       All said yes.

- After asking the Creator to try and contact the company, how did they get on?

       All immediately clicked on the 'Contact Us section in the NavBar, within 5 seconds of being asked the question, and read the top section for a few seconds then down to the form with no issues.

- What device do you normally use to look at websites?

       All said laptop or desktop screens mainly, but do go on social media on their phones a lot.
  - <span id="#testing-checklist"></span>

## Testing Checklists

Testing all links/buttons clicked to have the desired outcome. To pass, links will have to direct the user to the right page or section, as well as have some interaction with the site by hovering the cursor over the interactive elements/features.

### Navbar

- Sticky to the page - **Pass**
- Links items link to the correct page - **Pass**
- Modal icon link all pages, ability to close the Modal - **Pass**
- Can interact with the search bar - **Pass**
- Search bar focus on the click of the search icon  - **Pass**
- Highlighted section underneath the current page - **Pass**

### Navbar - Small

- Icon link to drop-down menu - **Pass**
- Sticky to the page - **Pass**
- Links items link to the correct page - **Pass**
- Modal opens from the profile link - **Pass** (the feature is to indicate further features to visitors to the website)
- Basic interaction with the search bar - **Pass** (the feature is to indicate further features to visitors to the website)
- Search bar focus on the click of the search icon  - **Pass**
- The highlighted section underneath the current page - **Pass**

### Hero Section

- Contact us links to the form on the contact page, all pages - **Pass**

### Example profile section on the Home page

- Button links to the creator page - **Pass**

### Example creator dashboard

- Tell me more button links to the contact page Hero section - **Pass**

### Form inputs

- Highlights red on focus - **Pass**
- Colour (border turns blue) feedback with the correct style of input - **Pass**
- Submit gives feedback if a required field is empty on interaction - **Pass**
- Submit button links back to the home page - **Pass**

### Footer

- Info@buy-me-a-drink.com links once pressed opens up a local email window - **Pass** (note, this email address is fake at time of publishing)

- Facebook icon - opens in new window facebook.com - **Pass**
- Twitter icon - opens in new window twitter.com - **Pass**
- Instagram icon - opens in new window instagram.com - **Pass**
  - <span id="#testing-ressolved"></span>

## Issues and challenges I encountered

### Dropdown menu

I needed to create a CSS-only dropdown menu, from an icon that I created and exported from XD.
   The main problems related to this were, making the exported SVG responsive to user engagement, and then linking that engagement to the exported SVG. After researching a solution via various online forms, I discovered a way to use checkbox input, linking that to the icon with an ID class, which would toggle between the active displays.

### Modal

I decided to add a Modal that would be triggered by the profile icon in the navbar, just using CSS. This was in addition to searching for a different solution to one that I have done before.

   Though there was not an immediate need to find an alternative approach, I enjoyed the challenge of finding one. This required a significant amount of time investigating an alternative approach. I was incredibly satisfied with the alternative I discovered, as I believe it was more sophisticated. I copied the code into my editor and edited the styling from there. I have labeled the code clearly in the HTML and the CSS.

### Nav-bar

The search input and icon alignment. This took a significant amount of adjusting and re-adjusting; I am still not 100% happy with the outcome, as I feel the code I have written to make minor adjustments makes the code look a bit unkempt/untidy.

### CSS Grid - Whitespace

This was another recurring issue to resolve. On each screen size, the grid would spill over from the section. Using overflow:none and adjusting the width and height of the columns and rows was the only fix.

### Known bugs

       How it works section on a small number of mobile devices in landscape mode, can cut off a small part of an icon.
 
       These issues can be fixed with time; give the likelihood of anyone viewing the website from these devices in landscape mode are incredibly small/unlikely. With added time this could potentially be fixed by changing the height formatting to be written in view height instead of pixels.
 
       In Firefox Submit button on the form is labeled Submit Query.
 
       Formatting for the search bar in the NavBar on the test iPhone, the border-radius is not formatting as on other devices and web browsers. After researching the problem I still have not found a solution.
- <span id="#deployment"></span>

# Deployment

I used multiple branches in this project; the master branch is the main deployment branch which will be the most up-to-date and deployable version of the code.

## How to deploy

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

- Select Settings from the top menu above the file window
- Scroll down to the GitHub Pages section
- Under Source click the drop-down menu labeled None and select Master Branch
- On selecting Master Branch the page will be automatically refreshed and the website is now deployed
- Scroll back down to the GitHub Pages section in Settings to retrieve the link to the deployed website.

## Run this code locally

Clone this project from GitHub by the terminal:

- Under the repository name, click Clone or download
- In the Clone with HTTPs section, copy the clone URL for the repository
- In your local IDE open Git Bash
- Change the current working directory to the location where you want the cloned directory to be made
- Type git clone and then paste the URL you copied in Step 2
<https://github.com/josephWoodland/beer.com.git>
- Press Enter. Your local clone will be created

Clone this project from GitHub by the Git Desktop:

- Under the repository name, click Clone or download
- Click the option to used GitHub Desktop
- In the clone, Repository Modal choose where you would like it to be stored locally
- The clone has been created and stored in your local file.

Further reading and troubleshooting on cloning a repository from GitHub can be found [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

## Running the code

As I have been using node_modules. You will have to have npm installed on your computer, which you can find details [here](https://www.npmjs.com/).

Once you have got the files in your coder of choice, run `npm install` to install the modules and settings laid out in the package.json file.
To use the `watch:sass` and the live reload modules for the development environment in the terminal use npm start, once this has started a window with the website loaded with the current code.
- <span id="#future"></span>

# Future Features

### Email links

- Before the site is live I will have to link the forms and email links properly so they work with a live email.

### Google/Facebook Analytics

- This feature is needed to track the users to the website, and how they behave.

### Profiles

- Further down the line I will have to implement user profiles that will be kept behind a log-in functionality.

### Scrolling Profiles

- We will need a section that will highlight user profiles, and what they have done to deserve the drink donation.
- <span id="#credits"></span>
# CREDITS

 I used the slack community to help me with structuring the README.

To help me with the responsive dropdown menu I used this page as reference.

<https://medium.com/creative-technology-concepts-code/responsive-mobile-dropdown-navigation-using-css-only-7218e4498a99>

<https://tutorialzine.com/2015/08/quick-tip-css-only-dropdowns-with-the-checkbox-hack>

<https://stackoverflow.com/questions/4847996/css-animation-onclick>

textarea not being responsive enough; <https://www.studentstutorial.com/html/responsive-textarea>

Here is were I researched how to do a css only open model

<https://codepen.io/timothylong/pen/HhAer>
