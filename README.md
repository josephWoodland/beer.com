Buy Me a Beer.com
 
 
To design a simple website for a new potential start up called 'Buy Me a Drink.com'
 
The client would like a simple and clean website with the goal to quickly inform potential users of the start up, what service the company is trying to provide, and make it easy to get in contact and express interest.
 
 
\*\* ----- UX -----
(link to the Guidelines)
 
I decided to use a main width of the initial content to be 1366px as at the time of doing the research for the website this was the most popular size screen to view a website. According to Statcounter at the time.
 
1366x768 (22.98%)
1920x1080 (20.7%)
1536x864 (7.92%)
1440x900 (7.23%)
1280x720 (4.46%)
 
knowing that nearly 45% of desktop users used the top two resolutions I thought it was important to make sure that they were catered for, not only in the screen width but in the height of the main sections( particularly the hero section).
 
Also with 55% using mobile to view websites and with the client expressing the use of facebook advertising. We paid particular attention to the very low pixel width count screens.
 
The initial wireframe design I created in Adobe XD.
 
(link to wireframes)
 
 
After the wireframes were signed of We created a mood board around the brand guidelines and website ideas.
 
After then I added the brand colour to the wireframes, branded all the assets that I created and added the mockups for smaller screens.
 
(link to colour wireframes)
 
 
 
\*\* ----- FEATURES -----
 
**_ Existing Features
 
As the main goal of the website was to track interest in the project the feature lists were quite small.
 
I have added a form section on a contact page, this makes it very easy for the user to be able to contact the company with any questions that they might have. I have also added a direct link to send an email to the client with a Malito link in the footer. We decided to put the form on it owns page for two reasons, it makes it clear in the nav bar where to go to contact the company, and also give the client more options around social media advertising. Can run a set of adds with more information linking straight to the contact page.
 
I have added Google analytics tag to the head section of the website, so the client can track the visitors to the website. This will give them a better understanding about the potential users and interest of the business idea.  
 
 
_** Features Left to Implement
 
For the initial goal of the website the features have all been made and implemented.
 
For the future of the project, if there is enough interest in the project, there will be a lot of features to implement. The next stage of the feature roadmap will be:-
    
	Next phase of the project
       Creator section
 
           There will be a section of the design for the attention of social media creators, once there is enough interest from users the client will then try and push the idea towards potential content creators that can use the platform to better monetize their content.
 
	Phase 3
 
User Sign in
 
           As the business is based around users 'gifting' other users the value of a drink, or designated product. There will need to be a secure login area for each user to have a profile. This will have bank details saved to be able to make purchases.
      
       Transaction integration
 
           There will need to be a intergrated payment feature where one users can pay each other. All details will have to be protected.
 
\*\* ----- TECHNOLOGIES USED -----
 
I used XD to mock up the wireframes and create the logos and icons. 
 
I wrote the code in visual studio code, and used GitHub to help with version control. 
 
The language that I have used to build the website is HTML and CSS.
 
Node Modules
 
I used some node modules to watch my code and carry out live uploads on save to the server that I was using for testing. This meant that I could also use the SCSS format of CSS to write my code, as one of the modules would compile the SCSS and write it to style.css also on save. Also used a prefixer module that would add the relevant prefix to the code to make it more accessible to different web browsers.
 
CSS FRAMEWORKS
 
Some of the frameworks that I used in the css language were css grid and css flexbox. Both of these frameworks were used to make it easier to position items on the page. Specifically I used CSS Grid for the how it works section, this made it very easy to organise the section to fit the specs from the wireframes. 
 
I used CSS flexbox to easily align the Navigation bar at the top of the page.
 
To make the drop down menu just using CSS I used the checkbox input to switch between having the nav bar hidden and shown.
 
 
\*\*\* ----- TESTING -----
 
I split the testing of the website into two sections. One was basic testing of functionality, which would be carried out by myself. The other got a small sample group of text subjects to test the website along the goal guidelines.
 1.
	For this test I run through each of the pages of the website, testing all the links I have set up making sure they were linked correctly.
 
 2. I tested the website by getting some sample users from inside the target audience profile. I structured the test around the goals that have been set out by the client.
 
Here are the recorded results. 
 
(link to the test slides doc)
 
 
\*\*\* ----- ISSUES/BUGS I HAD WITH DEVELOPMENT -----
 
Nav-Bar
 
The SVG item I created and exported in xd for the logo is not able to change the colour. Not sure what the issue is.
 
Search input in the nav-bar.
This caused me a few issues. Much more than I expected. Mainly around aligning the items within the nav-bar flex box.
 
One thing that slowed me up a little was being able to target the individual elements.
 
aligning the items I had issue with placing the search bar correctly, adding the icon next to the search bar, and in particular aligning the icon inside the middle of the box. As the SVG is thought of as a text item I used the text-align property, unfortunately this just aligned the icon on the horizontal axis, I tried various properties to work around justify-content and others. Eventually I made a div around the item and made that div a flex-box and then centered the content inside.
 
Finishing off the search bar with a border on focus and then clicking on the area around the icon also make the bar focused raise some more issues with aligning the content. I have worked around it by adding another div element and then adding a top margin to get them aligned. I do not feel like this is the most efficient way to do this.
 
-- SVG --
 
The SVG images that I made in XD and exported were not able to change the colour of the logo. This meant that I just had to re export the SVG icons in the colour that is needed for the web page.
 
--Footer--
 
I had a lot of trouble with the layout of the footer, when I had built it like in the wireframes it did not look quite right. So I redesigned the coder, which did take longer than it should have done.
 
\*\* ----- DEPLOYMENT ------
 
 
 
 
 
\*\* ----- CREDITS -----
 
Using Adobe typekit for my fonts.
 
unsplash images - all images on the site have been download from unsplash.com
 
To help me with the responsive dropdown menu I used this page as reference. 
 
https://medium.com/creative-technology-concepts-code/responsive-mobile-dropdown-navigation-using-css-only-7218e4498a99
 
https://tutorialzine.com/2015/08/quick-tip-css-only-dropdowns-with-the-checkbox-hack
 
https://stackoverflow.com/questions/4847996/css-animation-onclick
 
textarea not being responsive enough;
https://www.studentstutorial.com/html/responsive-textarea
