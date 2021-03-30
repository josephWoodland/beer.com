- Read me for Joseph Woodland's milestone project. ----- Beer.com -----

\*\* ----- UX -----

\*\*\_ Project Goals

This website has been desgined at teh request of a new start up called 'Buy Me A Drink.com'

_** Player Goals
**_ Parental Goals
_** Developer and Buiness Goals
**_ User Stories
\*\* Design Choices
\*\*\* Wireframes

\*\* ----- FEATURES -----

**_ Existing Features
_** Features Left to Implement

\*\* ----- TECHNOLOGIES USED -----

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
