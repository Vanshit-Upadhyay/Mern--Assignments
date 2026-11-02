# Assignment 8 - Responsive Design - Chai Adda

## Main Objective
Learn to make an existing website work on phones, tablets and laptops.

## What I Did
I took my Assignment 7 project (Gallery, Product Grid and Dashboard) and made it responsive. I did not make a new project.

## Files
- gallery.html - Photo gallery with 9 images, now responsive
- product-grid.html - Product listing of 8 items, now responsive
- dashboard.html - Dashboard layout with header, sidebar, main and footer, now responsive
- README.md - This file

## Breakpoints Used
I used 2 breakpoints with @media queries:
- 768px - For tablet
- 480px - For mobile

## What Changes on Small Screens
- Gallery: Desktop 3-4 columns -> Tablet 2 columns -> Mobile 1 column
- Product Grid: Desktop 3-4 columns -> Tablet 2 columns -> Mobile 1 column, button becomes full width so it is easy to tap
- Dashboard: Desktop sidebar on left -> Tablet and Mobile sidebar moves on top in horizontal row
- Navigation: Desktop horizontal -> Mobile vertical and centred
- Headings and text: Font size reduced on tablet and mobile so text is not too small or too big
- Images: width: 100% and box-sizing: border-box used so images do not overflow and there is no horizontal scrolling

## Navigation
All three pages are linked with each other using navigation bar:
Gallery -> Products -> Dashboard

## Testing
Tested on 3 screen sizes using browser DevTools:
- Desktop - 1200px and above - Full layout
- Tablet - 768px - 2 columns layout
- Mobile - 480px and below - 1 column layout, no horizontal scrolling

## Problems Fixed
- Images overflowing - Fixed with width: 100% and box-sizing: border-box
- Horizontal scrolling - Fixed with max-width and padding control
- Buttons too close - Fixed with bigger padding and full width button on mobile
- Text too small - Fixed with proper font size on mobile

## Design Choices
Topic: Chai Adda, Budaun - Same topic as Assignment 5, 6 and 7 to keep the project continuous.
Colours: Dark Green #12372A for main, Cream #FBF3E4 for background, Orange #FF7A00 for buttons and highlights.
Fonts: Sora for headings and DM Sans for body text.

## What I Learned
- How to use @media queries with 768px and 480px breakpoints
- How to make grid change columns on different screens
- How to make dashboard sidebar change layout on mobile
- How to test on mobile, tablet and desktop using DevTools
- How to fix overflow, horizontal scrolling and small button problems
