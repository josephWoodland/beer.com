- Read me for Joseph Woodland's milestone project. ----- Beer.com -----

\*\* ------ Project Brief --------

To design a simple website for a new potential start up called 'Buy Me a Drink.com'

The client would like a simple and clean website to quickly inform potential users of the start up what service the company is trying to provide.

Brand colours have been decided already and handed over, the websites that they said to use for insperation were:


\*\* ----- UX -----


I decided to use a main width of the initial content to be 1366px as at the time of doing the research for the website this was the most popular size screen to view a website. According to Statcounter at the time. 

1366x768 (22.98%)
1920x1080 (20.7%)
1536x864 (7.92%)
1440x900 (7.23%)
1280x720 (4.46%)

knowing that nearly 45% of destop users used the top two resolutions I thought it was important to make sure that they were catered for, not only in the screen width but in the height of the main sections( particulary the hero section). 

Also with 55% using mobile to veiw websites and with the client expressing the use of faceboook advertising. We paid perticular attention to the very low pixel width count screens.

The initial wireframe design I created in Adobe XD.

(link to wireframes)


After the wireframes were signed of We created a mood board around the brand guidlines and website ideas. 

After then I added the brand colour to the wireframes and also branded all the asstets that I created. 

(link to colour wireframes)


\*\* ----- FEATURES -----

**_ Existing Features

As the main goal of the website was to track intrest in the project the feature lists was quite small. 

Need a way for potential users to get in contact with the founders. 

        I achived this by having a simple form set up on a seperate page. Which would capture inputs into the text area and then send this as a email to the founders. 

        Also at the request of the client the form would be on a seperate page so this can be easliy linked to via facebook advertising.

Need a way to track any hits to the website.

        For this I installed Google Analytics into the website. This allowed all data and hits to the website to be tracked. From thier the cliens can see how much interest the project has.


_** Features Left to Implement

There will be alot of features to implement if the interest is there for the project. 

        User Sign in

            As the buisness is baised around users 'gifting' other users the value of a drink. There will need to be a secure log in area for each user to have a profile. This will have bank details saved to be able to make purchases.
        
        Transaction intergration

            There will need to be a=intergrated payment feature where one users can pay each other.

        Creator section

            There will need to be a seperate section for the recivers of the gift. This will be set out like a dashboard with all the payment information on it. 

\*\* ----- TECHNOLOGIES USED -----

The language that I have used to build the website is HTML and CSS.

I used a CSS compiler so I could write and organise the code using SCSS. 

I used a node module


\*\*\* ----- TESTING -----

\*\*\* ----- ISSUES/BUGS I HAD WITH DEVLOPMENT -----

Nav-Bar

The SVG item I created and exported in xd for the logo is not able to change the colour. Not sure what the issue is.

Search input in the nav-bar.
This caused me a few issues. Much more then I expected. Mianly around aligning the items within the nav-bar flex box.

One thing that slowed me up a little was being able to target the indevidual elements.

with aligning the items I had issue with placeing the search bar correctly, adding the icon next to the search bar, and in particular aligning the icon inside the middle of the box. As the SVG is though of as a text item I used the text-align property, ufortunatly this just aligned the icon on the horizontal axis, I tried various propeties to work around jusitfy-content ann others. Eventually I made a div around the item and made that div a flex-box and then centered the content inside.

Finishing off the search bar with a border on focus and then and making clicking on the area around the icon also make the bar focused rasied some more issues with aligning the content. I have worked around it by adding another div element and then adding a top margin to get them aligned. I do not feel like this is the most efficiate way to do this.

-- SVG --

The SVG images that I made in XD and exported were not able to change the colour of the logo. This ment that I just had to re export the SVG icons in the colour that is needed for the webpage.

--Footer--
I had alot of trouble with the layout of the footer, when I had built it like in the wireframes it did not look quite right. So I redesigned in the coder, which did take longer than it shoudl of done.

\*\* ----- DEPLOYMENT ------

\*\* ----- CREDITS -----

unsplash images - all images on the site have been downoad from unsplash.com
I have used font awsome for some of the icons on the page.

To help me with the resonsive dropdown menu I used this page as reference.
https://medium.com/creative-technology-concepts-code/responsive-mobile-dropdown-navigation-using-css-only-7218e4498a99

https://tutorialzine.com/2015/08/quick-tip-css-only-dropdowns-with-the-checkbox-hack

https://stackoverflow.com/questions/4847996/css-animation-onclick

textarea not beign responsive enough;
https://www.studentstutorial.com/html/responsive-textarea
