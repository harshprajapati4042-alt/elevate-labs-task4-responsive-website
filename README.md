# elevate-labs-task4-responsive-website
Task 4: A responsive website converted from a desktop-only layout using CSS media queries, Flexbox/Grid and relative units for Elevate Labs Web Development Internship.

A small cafe website converted from a desktop-only layout to a mobile-friendly layout using CSS media queries, relative units and flexible layouts. Built for the Elevate Labs Web Development Internship.

Problems in the Desktop-Only Version :
body had a fixed width of 1100px, so phones showed a horizontal scrollbar
Columns and cards had fixed pixel widths
The navigation links did not fit on a small screen
Images had fixed sizes and did not shrink
No viewport meta tag

What I Changed :
Added the viewport meta tag: <meta name="viewport" content="width=device-width, initial-scale=1.0">
Replaced fixed pixel widths with %, rem and max-width
Added img { max-width: 100%; height: auto; } so images scale inside containers
Used Flexbox for the hero and about sections, and CSS Grid for the feature cards
Added media query for max-width: 768px: columns stack vertically, font sizes reduce, cards become one column
Added a collapsible hamburger menu on small screens (pure CSS, no JavaScript)
Added media query for max-width: 480px for small phones
Fixed horizontal overflow so the page never scrolls sideways

What I Learned :
Media queries, mobile-first and desktop-first design
Viewport meta tag and CSS units (%, rem, vw)
Flexbox and Grid for responsive layouts
Testing responsive pages with Chrome DevTools
