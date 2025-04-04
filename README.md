# portfolio-hackathon

- I designed a low-fidelity mockup to structure my portfolio website before developing the actual design. This helped in planning the layout, user flow, and key sections efficiently
 
# 2. Designing Tool that I  Use: 

🔹 Sketching on Paper – Quick and easy way to plan layouts.

🔹 Wireframing Tools – Figma( For  High fidelity Wireframe)


# Low Fidelity Mockup Design ( book sketch)

- The key sections are( Home, About, Qualification , Service ,Projects and Contacts)

As shown below 
![lowFidelityWireframe](https://github.com/user-attachments/assets/b7a1b24f-1035-4e63-bf94-779608daf2a6)

# High Fidelity Mockup

- It involves designing a static real website but has no functionality

- For mackbook pro 16 i checked on the following scaling and Responsiveness
  
- I check on typography and spacing
  
- Allignment of texts
## Here is my design website protoype  that can be viewed in Mackbook pro 16

- https://www.figma.com/proto/nejFjWw1pYt2abMhKN7jFx/Dorothy-s-Portfolio?node-id=1-2&p=f&t=3o4nOLcKJ8jGsYyt-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2


- Figma Link : https://www.figma.com/design/nejFjWw1pYt2abMhKN7jFx/Dorothy-s-Portfolio?node-id=1-2&t=41IkWuYTRFHd07rv-0


## Technical Documentatio: Dorothy  PortFolio Web Project Setup

# Project Overview

- This document provides a technical overview of the web project, including the folder structure, HTML, CSS, and JavaScript files. 

- It also explains the setup process and how the files interact.

1. Folder Structure

- The project follows a structured approach where assets such as CSS, JavaScript, and images are stored in separate folders.

As Shown:

![portfolioo](https://github.com/user-attachments/assets/8f0bc90b-066f-4504-8550-2f124948ede1)

2. ## Steps to Set Up the Project

# Step 1: Creating the Project Folder

- Open the visual studio terminal and create a new folder for the project:

cd ~/Desktop  

mkdir dorothyPortfolio

cd dorothyPortfolio 

# Step 2: Creating the Folder Structure

- Inside the web-project directory, create subfolders for assets:
  
mkdir assets

mkdir assets/css assets/js assets/img

# Step 3: Creating Essential Files

- Create the required HTML, CSS, and JavaScript files:

touch index.html

cd assets/css && touch main.css

cd ../js && touch main.js


## Index.html file 

-  A portfolio website for Dorothy, showcasing skills, experience, and projects.

 ## in index.html

## Technologies Used:

HTML (structure)

CSS (styling)

Google Fonts (custom typography)

Remix Icons (icons for UI)

Swiper.js (image slider functionality)


## main.css file 

- This CSS file defines a variety of design tokens, reusable components, and responsive styles for a web application. The key sections are as follows:

## Design Tokens (CSS Variables)
- Colors: Defines primary, secondary, background, text, and border colors, with shades for primary and footer sections.

- Font & Typography: Includes font families, sizes (small to extra-large), and weights (regular to bold).

## Layout: Contains dimensions like container width, header height, and transitions.

## Z-Index: Defines stack levels for menu and fixed elements.

- Box Shadows & Transitions: Applies smooth transition effects and subtle box shadows for UI elements.

## CSS Reset
- Universal box-sizing, zero margin/padding for all elements.

- Standardizes font settings and image handling for a clean layout.

## Reusable Components
- Container: Set width, centered content, and max-width.

- Section: Padding for spacing and layout structure.

- Buttons: Styles for primary and secondary buttons with hover effects.

- Grid: Uses CSS Grid for layout, ensuring responsive design.

## Header
- Navigation Bar: Fixed header with branding, links, and toggle for smaller screens.

- Responsive Menu: Toggle visibility based on screen size for mobile users.

## Hero Section
- A full-page hero layout with centered text and a primary title that includes a bottom bar for visual enhancement.

- Information section with large numbers for emphasis.

## About Section
- Text content layout with centered title and description.

Skills section styled as cards with icons and labels.

## Qualification Section
- List of qualifications, styled with border separation and a footer section with styled text.

## Service Cards
- Cards for services with hover effects, background color changes, and icons.

## Project Section
- Layout for displaying projects, including images, titles, descriptions, and links with hover effects.

## Testimonial Section
- Cards displaying testimonials with images, descriptions, and styled pagination for slides.

## Contact Section
- Centered contact form with a description, title, and styling for form fields.

## Footer
- Includes sections for social media links, contact information, and copyright notice.

## Scrollbar
- Custom scrollbar styling for a smooth user experience.

## Media Queries
- Responsiveness across devices, adjusting navigation, layout, and image size for various screen widths.



## main.js

This JavaScript code provides functionality for a responsive navigation menu and smooth scroll animations. It controls the toggling of the menu, updates the hamburger icon, animates the header on scroll, and reveals sections as the user scrolls.

Key Components:
Navigation Menu Toggle:

Controls visibility of the navMenu using the nav__menu--open class.

Toggles between hamburger (ri-menu-3-line) and close (ri-close-line) icons.

Closes the menu when a navigation item is clicked.

Header Scroll Animation:

Adds/removes header--scroll class to the header when scrolling beyond 40px.

ScrollReveal Animations:

Uses ScrollReveal to animate elements like .hero__content, .about__content, and .footer__content.

Elements are animated with custom durations, delays, and origins (e.g., top, left).

Code Behavior:
Menu Toggle:

Toggles the nav__menu--open class and updates the icon using the changeIcon() function.

The menu closes when any navigation item is clicked.

Icon Change:

Changes the hamburger icon to a close icon when the menu is open, and vice versa.

Initial Page Load:

On load, ensures the icon reflects the menu's state.

Header Scroll:

On scroll, adds/removes the header--scroll class based on the scroll position.

ScrollReveal Animations:

Animates elements with varying durations, distances, and delays based on their class.

## Hosting
push your code to github using the following commands:

git init

git add .

git commit -m "first initial"

git remote add origin https://github.com/Dorothy2020/portfolio-hackathon.git

git branch -M main

git push -u origin main

   

- I have used Netlify.com to host my portfolio website, and here is the link for my portforlio website
 #  Here is my portfolio website.
  https://dorothy-akoth.netlify.app/

- The website is mobile friendly and can be viewed in any devices


# # the end  



  
