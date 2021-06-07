# psychic-rotary-phone

#### SUMMARY OF CHANGES MADE

- Using the <header> & <footer> vs. div, this will make search engines understand the content of the page easier.

**HEAD Element**

1. Added title so that the browser tab reads "Horiseon"
2. Added type="text/css" attribute to the css stylesheet link

**BODY ELEMENT**

1. Use of Comments To Organize: Added comments to separate the main sections in both HTML & CSS files. Structured the code to follow a logical structure.

**HEADER ELEMENT**

> Header Element: For the header section, I updated the div to use HTML's header element vs. div. In CSS, I removed the ".header" used in targeting the h1 element as it was not necessary.

> NAV Element: Html has a specific NAV element. I updated the html code and made the necessary changes for the css side.

> Search Engine Optimization NAV Link: When testing out the code in the browser, I noticed the "Search Engine Optimization" nav link was not working - "id" was missing in the div which housed the code content.

> Flexbox For Building Navigation Bar: Looking class assignment, I was able to put together the process of building a versatile header through use of Flexbox.

**HERO IMG**

> Accessibility is an extremely important component to building a website. Since the Hero image was referring to the the css document, there was no location to provide an 'alt' description. Researched how to change the html code so that it utilizes the "img" element thus allowing for a "alt" description to be written.

**CONTENT & BENEFITS**

> Removing Unique Class Names: Reviewing the CSS code for both sections, I realized a unique class name for each div was not necessary. I replaced all the class names in the html document for both content / benefits section to read as "content" and "benefits" respectively. Makes for a cleaner & concise code :).

> Missing Alt Attributes: Coming back to the importance of accessibility, all img elements in the html file were missing alt descriptions. As a result, I simply used the section titles as the description for each image.

**FOOTER**

> <footer> vs. "class=footer": I updated the footer section to use the html element footer vs. div & class. By doing so, I was also able to remove class element as it was no longer necessary.

- In CSS, for the functionality of the footer to work with the above change, I updated the footer to no longer target a class.

> Heart Icon vs. &#10084;&#65039;: I noticed a weird heart symbol was used. Out of curiosity, I researched and came across HTML having specific syntax to for purpose. Decided it would be better to add using html code since I'm not 100% sure the original symbol will translate correctly across all platforms.

**OTHER CHANGES - CSS**

> Font-size [px vs. %] - In CSS, I changed the way the styling for font-size was being utilized. Instead of specifying a px for each, I placed the font size = 16px in the body and updated to use % in relation to the 16px. This should make future updates easier.

> color: #ffffff - Since the theme of the document was to show all writing in white color, I also placed this in the body to target all except: <a> links & <footer>.
