# Current Task
 - style .code-box  -- see css tricks

# ToDo
 - add :hover and :focus effect to .nav-button-mask (could use tranform: scale)
 - hide nav-button from screen readers
 - fix width for @media desktop/medium desktop, navbar is overlapping content
 - hide .nav-button checkbox
 - pre code { colors } -- see css tricks
 - .word-wrap wrap long code in this .word-wrap class
 - Add link to tech-doc page to page h1
 - check all links
 - proofread
 - don't need a favicon for this site 
 - export github live
 - check that html verifies
 - check browser stack

# freeCodeCamp Technical Documentation Page Project

## Live site on GitHub Pages
 - unfinished
 - completion date
 
## Description of Project
freeCodeCamp - https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page

Build a website using HTML and CSS that is functionally similar to https://codepen.io/freeCodeCamp/full/NdrKKL

## Goals
 - Pass freeCodeCamp tests
 - Use semantic and accesible HTML and CSS
 - Make it responsive
 - Make it actually look good
 - Use some animation, and check for prefers reduced motion
 
## Things I learned
 - Accessibility and animation (prefers reduced motion)
   - when/which motion causes issues
   - when motion can help understanding
     - e.g. providing useful information to the user
     - e.g. examples that can't be understood without motion/animation
   - ways to provide a good user experience either way
 - &lt;pre> element
 - &lt;code> element
 - better understanding of CSS Combinators
 - fix monospace font size reduction
   - pre, code { font-family: monospace, monospace; font-size: 1em; }
 - transition: to create animation
 - CSS transform property performs better than changing other properties
   - e.g. translate vs changing top/bottom
   - "Transforms perform better..." <https://css-tricks.com/css-animation-tricks/>
   - overflow: auto; creates a scroll bar on block elements with a explicit height/width

  ### Note on Layout
   
  On a viewport that is wide enough (> 1396 pixels) I wanted to have the main
  content centered in the broswer window. 

  However with the #navbar open this leads to a lot of whitespace to the right
  of the content. So, even though the main content is centered on the viewport
  (in theory for better readability) the whole page itself seems lopsided and
  weighted to the left due to the extra whitespace on the right. Bad symmetry?

  On a real website I would probably forego the large desktop view where the
  main content is centered, and just use the middle width desktop view:
  700 < 1396 pixels. Centering the main content only when the navbar is closed.

## References
 - MDN Combinators
   - https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators
 - Prefers reduced motion and accessible animation
   - https://web.dev/prefers-reduced-motion/
   - https://css-tricks.com/revisiting-prefers-reduced-motion-the-reduced-motion-media-query/
   - https://alistapart.com/article/designing-safer-web-animation-for-motion-sensitivity/#section7
   - https://css-tricks.com/introduction-reduced-motion-media-query/

