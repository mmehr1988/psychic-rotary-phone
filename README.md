# psychic-rotary-phone

#### SUMMARY OF CHANGES MADE

## COMMENTS

1. Use of Comments To Keep Organized: Added comments to separate the main sections in both HTML & CSS files. Structured the code to follow a logical format.

## HEAD ELEMENT

1. Added title so that the browser tab reads "Horiseon"
2. Added type="text/css" attribute to the css stylesheet link

## HEADER ELEMENT

Using the HTML symantics (`<header>` & `<footer>` & `<nav>`) vs. `<div>`: Utilizing HTML semantics to structure html document allows for future developers to understand the content of the document easier. It also helps search engines decipher the meaning of the code in a more precise manner.

1. Header Element: In CSS, I removed the ".header" used in targeting the h1 element as it was not necessary.

2. NAV Element: Html has a specific NAV element. I updated the html code and made the necessary changes for the css side.

3. NAV Link: When testing out the code in the browser, I noticed the "Search Engine Optimization" nav link was not working - "id" was missing in the div which housed the code content.

4. Flexbox For Building Navigation Bar: I noticed the nav header would continously break onto a new line. To prevent this issue, I was able to put together the process of building a versatile header through use of Flexbox. All thanks to our bootcamp.

## HERO IMG

Accessibility is an extremely important component to building a website. Since the Hero image was referring to the the css document, there was no location to provide an 'alt' description. Researched how to change the html code so that it utilizes the "img" element thus allowing for a "alt" description to be written.

## CONTENT & BENEFITS

1. Removing Unique Class Names: Reviewing the CSS code for both sections, I realized a unique class name for each div was not necessary. I replaced all the class names in the html document for both content / benefits section to read as "content" and "benefits" respectively. Makes for a cleaner & concise code :).

2. Missing Alt Attributes: Coming back to the importance of accessibility, all img elements in the html file were missing alt descriptions. As a result, I simply used the section titles as the description for each image.

## FOOTER

1. `<footer>` vs. "class=footer": I updated the footer section to use the html element footer vs. div & class. By doing so, I was also able to remove class element as it was no longer necessary.

- In CSS, for the functionality of the footer to work with the above change, I updated the footer to no longer target a class.

2. Heart Icon vs. HTML Code `&#10084;&#65039;`: I noticed a weird heart symbol was used. Out of curiosity, I researched and came across HTML having specific syntax to for purpose. Decided it would be better to add using html code since I'm not 100% sure the original symbol will translate correctly across all platforms.

## OTHER CHANGES - CSS

1. Font-size [px vs. %] - In CSS, I changed the way the styling for font-size was being utilized. Instead of specifying a px for each, I placed the font size = 16px in the body and updated to use % in relation to the 16px. This should make future updates easier.

2. color: #ffffff - Since the theme of the document was to show all writing in white color, I also placed this in the body to target all except: <a> links & `<footer>`.

3. Normalize CSS - I added normalize css file as I've read it renders all elements more consistently across browsers.
