# Horiseon Code Refactor Challenge

## User Story
* A marketing agency that needs their code updated to follow accessibility standards so that their site is optimized for search engines.

## Acceptance Criteria
* Source code contains semantic HTML elements
* HTML elements follow a logical structure independent of styling and positioning
* Image elements contain acceible alt attributes
* Heading attributes fall in sequential order
* Title is concise and descriptive

## Solution
* Changed divs to other semantic elements such as header, nav, footer and section elements to provide structure to the body
* Added an id attribute to social-media-marketing article section so that navigation link works
* Added alt attributes to all the images, descriptive alts for images and empty alts for decorative graphics
* Changed selectors in CSS to match new semantic elements in HTML
* Consolidated CSS by using less specific selectors to remove repetetive code

## Website
https://crossigarcia.github.io/horiseon/

## Screenshot of Website  

![Horiseon Webpage](./assets/images/horiseon-index.png)