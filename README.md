# Code First Girls Introduction to Web Dev Project

This project is part of the eight week Coding Kickstarter Introduction to Web Dev course with Code First Girls. I decided to create a simple coffee shop website.

## HTML Pages / CSS File

The website has three pages:

- A homepage
- A menu page
- A contact page

Although I primarily used Bootstap to style the site, I also used an external CSS file to change some Bootstrap default styles where desired and to add custom colors, fonts and components (for example, buttons).

## Wireframe

I created a low fidelity wireframe for the homepage on [moqups](https://moqups.com/):

(https://app.moqups.com/vuBgmpATfmovUq5jnDljsfxtFnqDP9zC/view/page/ad64222d5)

<img width="576" alt="Screenshot 2024-05-14 at 18 37 56" src="https://github.com/ViannaF/coffeeshop/assets/88505281/15b2ad79-4df6-4b53-a790-c3ba860b38de">

## CSS Framework

I used [Bootstrap v5.3](https://getbootstrap.com/) to style this project.

I made use of the following components:

- [Navbar](https://getbootstrap.com/docs/5.3/components/navbar/) across all three webpages for the dark themed collapsible navbar with toggle button
- [Carousel](https://getbootstrap.com/docs/5.3/components/carousel/) for the testimonial slider on the homepage
- [Accordion](https://getbootstrap.com/docs/5.3/components/accordion/) for the menu page
- [Cards](https://getbootstrap.com/docs/5.3/components/card/) for the customer favourites section

I also used the container and grid system to ensure alignment and responsiveness.

I made extensive use of the various bootstrap utilities for spacing, text formatting and flex.

## Links

- All three webpages include a navigation bar with links to the other pages or an internal fragment of the same page.
- There is also a footer with a sitemap with working links to other pages in the site as well as social media icons linking to their corresponding websites.
- On the homepage there are three call to action buttons which link to relevant fragments/pages of the site.
- The full size hero header has an arrow that links to a fragment further down on the webpage.
- The contact page also has a separate dedicated section for social media icons that link to their corresponding websites.

## User Interaction

- All buttons darken on hover to indicate interactivity
- All buttons in the active state change background colour and text colour
- Links that are part of the active class (indicating the current page) are more opaque and links also become more opaque on hover
- Javascript to disable form submissions if there are invalid entries (both newsletter and contact forms)
- Javascript to apply bootstrap classes with custom form validation messages and styling on the contact form
- A testimonial slider with indicators using Bootstrap (Javascript) that users can swipe or click through on the homepage
- A Bootstrap accordion containing collapsible content for each accordion item (menu category) on the menu page

## UI/UX

### Colour theory

- Used shades of brown and orange to evoke friendliness, sociability, happiness, good times and a cosy feel. I also felt brown fit well with the coffee theme.
- Extracted color theme from hero image using [Adobe Color](https://color.adobe.com/create/color-wheel)
- These colours are also analagous to help ensure a harmonious, pleasant and relaxing design, similar to a coffee shop itself.

### Typography

- Used two contrasting but complementary google fonts to differentiate paragraphs and headings.
- Chose Merriweather(serif) for headings and logo to appear more traditional and cosy.
- Chose Lato(sans-serif) for paragraph text as it is simple, modern and readable.

### Other UI/UX Principles

- No more than 60 characters per line to ensure readability
- Tried to keep text concise and relevant or appealing
- Headings in larger font sizes to draw attention
- Draw attention to key information with bold font weight
- Bold black text and contrasting yellow colour for call to action buttons to draw attention
- Navigation links on the current page more opaque to remind the user where they are on the site
- Upper case letters used to draw attention to the newsletter sign up section
- Sufficient contrast between all text and background to ensure readability (checked with [AIM Contrast Checker](https://webaim.org/resources/contrastchecker/))
- Used dark overlay and white font colour where text is used over photographs to ensure sufficient contrast
- Font size always at least 16px on all devices to ensure readability and increases on larger screens for important text
- Used Bootstrap containers and grid system to ensure alignment between various elements and spacing utilities to avoid pages appearing cluttered
- Hero section and text large and centered to draw attention
- Used different colors to differentiate/highlight different sections on the pages
- Ensure connected text has little space between it while different information and sections are spaced further apart
- Either centered, short paragraphs or F-shaped reading pattern (e.g. contact page) to ensure readability and manage attention
- Consistent use of colors, fonts and spacing throughout the website. All images, cards and buttons have the same border radius
- Forms provide clear feedback using both colour and text

## Mobile Responsive

- Used boostrap to create a navigation menu that collapses behind a button on small devices
- Used bootstrap grid system to create an "About Us" section that consists of two columns (one text, one photograph) which are stacked on small - medium devices and side by side on larger screens
- Used bootstrap cards to show customers' favourite menu items - cards are stacked on small to medium devices and in three columns on larger devices
- The arrows on the tesimonial carousel disappear on small devices as there is not enough room for them
- The footer consists of three stacked columns (sitemap, contact details, opening hours) that are displayed side by side on larger screens
- The newsletter section also consists of three stacked columns that are dispalyed side by side on larger screens.
- All social media icon links are large enough to tap on touchscreen devices
- Used Bootstrap flex utilities for the content of the menu accordion items so that the headings/descriptions and the prices are two stacked columns on small to medium devices and side by side on larger screens
- Used Bootstrap flex utilities so that the visit us section on the contact us page is displayed as two stacked columns (contact details and google map) on small to medium devices and side by side on larger screens
- Used CSS hack found [here](https://blog.hubspot.com/website/how-to-embed-google-map-in-html#:~:text=To%20make%20a%20responsive%20Google%20Map%20in%20HTML%2C%20take%20your,with%20the%20class%20google%2Dmap.&text=Here's%20the%20result.,the%20size%20of%20your%20browser.) to ensure google map scales to fit smaller devices
