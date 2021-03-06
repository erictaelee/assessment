For the skill assessment, we will be testing out your ability to pick up someone else's code and take it to the next level. 
For the hypothetical situation, a FED has been working on a project but got pulled off so we need your help.

Here's what the FED has to say:

This is where we allgot to in the cut, but we are having problems and haven't been able to fully test. 
Can you help us resolve the following issues as well as help catch if we missed something?
The client is very particular about having fast page speed, good SEO, and wants interesting interactive pieces.
Support wise they also want to have this page look right in browsers that are over 5% of the browser stats for the US over the past couple of months
Below are the items we haven't been able to get to yet.

Font:
  - We set up the Allura and Alex Brush font family stacks in the CSS but we don't have the fonts included

Site Logos:
  - We need to account for retina screens

Icons:
  - We haven't been able to add the icons to the setup yet
  - Hamburger menu, cart, and search icons haven't been added

Navigation:
  - We haven't setup functionality for the menu toggle to open up the bottom footer area in small screens

Slideshow:
  - We need another slide created from the PSD 
  - The styling isn't right yet for slide content as well
  - We also haven't been able to set up the slide functionality

Footer:
  - We got a fair amount of responsive styles done for the site however the footer isn't quite there yet
  - Social media icons need to be setup so some html changes there to put them in is fine.
  - Expander accordion Javascript functionality hasn't been setup or styled
  - Footer bottom area: we unfortunately can't pull the html content out of its location
     - Can we style up the setup so it matches the desktop and mobile styles

Responsive:
  - For some reason the site isn't switching over to "mobile" styles in devices
  - Also when you shrink down the browser some sort of content is causing a horizontal scrollbar in smaller screens
  - In between sizes for tablet portrait feel fairly empty, is there something we can style to make them look better


The client is very active in the project and wants a technical breakdown of what you did and how you resolved the missing items. 
So we need a writing assessment as well as the code above. 
They also want to know how the design UI/UX and FED code practices could be improved down the road, so please include that as well in your writing. 




Font: I've googled the Allura and Alex Brush font and found the link that had these fonts. Copied and pasted it into the <head> tag.

Site logos: I've chosen the SVG file over PNG because SVG is easily scalable at high resolution without losing quality and the file size does not change. The downside is that the SVG file struggles with older browsers, however the client is using retina screens, which means they are using a newer device.

Site Icons: I've removed the 'visually-hidden' class that hides the icon. Then added font awesome kit's code into the <head> and added the search icon. 

Navigation: Created hamburger menu using CSS and used JS to toggle menu in mobile view. It will display + sign as default and show - sign when toggled to 'active'. 

Slideshow: Used CSS to show 'next' and 'previous' arrow and used JS to add the functionality. I've set the current slide position to 0 and created a function to increment when clicked next and decrement when clicked previous. Had to look up some syntax and logic on google.

Footer:
  - Social media icons: Used the individual png file instead of using the sprite because each link is unique. Deleted list items <li> to align them.
  - Expander accordion: Added CSS to toggle 'active' when clicked then added JS functionality to show the list when the toggle is set active.
  - Footer bottom area: Added some @media condition to match the styling in CSS.

Responsive:
  - Added meta viewport in <head> to make it mobile responsive. Also added some CSS styling to enhance the aesthetics.
