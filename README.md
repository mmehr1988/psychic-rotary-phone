# psychic-rotary-phone

## Overview Of Changes Made

- Added title that when website is opened, the browser tab reads "Horiseon"
- Added type="text/css" attribute to the css stylesheet link
- Added comments to separate the main sections in both HTML & CSS files
- Organized CSS to follow a logical structure to how the website was structured

## Section: Header

- HTML |

  1. Header Element: Html has a specific header element. I therefore, placed the header components inside this element.
  2. NAV Element: Html has a specific NAV element.

  - Noticed the first nav link was not working. Looked over the contents section and realized "id" was missing and this was causing an issue. Updated the div to include the appropriate id to allow for proper use of the nav section.

- CSS | Removed the ".header" used in targeting the h1 element as it was not necessary.

## Section: Hero Img

- Accessibility is an extremely important component to building a website. Since the Hero image was referring to the the css document, there was no location to provide an 'alt' description in the html. Researched how to change the way the code was written, I incorporated the Hero image in the html document to and just add styling to prevent it from cropping.

## Section: Content & Benefits

- CSS | Condensed the elements where they had the same changes
- HTML | added an alt attribute to all the images.
-

## Section: Footer

- HTML | I updated the footer section to use the html element footer vs. div. By doing so, I was also able to remove class element as it was no longer necessary. I noticed a weird heart symbol was used. I researched, and I noticed that HTML has specific symbols for this. Decided it would be better to add using html code.

- CSS | By making the html change, I also updated the CSS styling for the footer to no longer target a class.

  1. Since the color theme of the body,html was specified to be color: #ffffff, I noticed the footer color also changed. Therefore, I specified the color of the footer should be black.

- SEO | This will make search engines understand the content of the page easier.

## CSS | Basic Setup

- CSS | color: #ffffff | The white color seems to be the theme of the website. I placed the color element inside the basic setup under the body,html styling to reduce the redundant use through out.

- CSS | font size: I changed the way font size was used across the different sections. I set a body "font size: 16px" and converted all font sized to be relative. This will make future scaling easier across the entire page.
