# scaling-fiesta
# Perfume Website – User-Centric Frontend Project

## Project Overview
This project is a **static front-end website** created to present perfume products in a clear, elegant, and user-friendly way.  
The site showcases a range of perfumes, provides brand information, and allows users to easily explore products and contact the business.

The website is built using **HTML5 and CSS3**, with optional use of **Bootstrap** to support responsive layout and accessibility.

---

## Project Purpose

### External User’s Goal
- Learn about different perfumes and scent types
- Explore perfume collections (men, women, unisex)
- Understand fragrance notes and pricing
- Decide whether to purchase or visit the store

### Site Owner’s Goal
- Promote perfume products
- Build brand identity and trust
- Encourage users to engage with the brand and make contact

The website presents information clearly and attractively to meet both user and business needs.

---

## User Experience (UX) Design

### Target Audience
- Adults interested in perfumes and luxury products
- Customers looking for gifts or personal fragrances
- Users browsing on mobile, tablet, and desktop devices

## User Stories

| ID | User Story |
|----|------------|
| US1 | As a customer I want to browse perfumes so I can choose one |
| US2 | As a customer I want clear navigation so I can find products easily |
| US3 | As a user I want mobile responsive design so I can use my phone |
| US4 | As a customer I want contact information so I can ask questions |
| US5 | As a user I want product prices visible so I can compare |

### UX Design Decisions
- Simple and consistent navigation across all pages
- Clean layout with clear sections and headings
- Luxury-inspired color palette to match the perfume brand
- Readable typography and sufficient spacing
- Responsive design to ensure usability on all screen sizes

Wireframes and layout planning were used to structure content logically before development.
Wireframes of desktop:
https://github.com/Y40Y50/yahyaPerfumes/blob/3b9db33785234be707633b5162b5b1e622a3b361/assets/wireframe%20desktop%20layout.pdf

Wireframes of Mobile Mode:
https://github.com/Y40Y50/yahyaPerfumes/blob/3b9db33785234be707633b5162b5b1e622a3b361/assets/wireframe%20Mobile%20layout%20copy.pdf

## Design Process

Before development the structure was planned to ensure good UX design.

### Home Page Structure

- Navigation bar
- Hero image
- Featured products
- Contact footer

### Products Page Structure

- Product card grid
- Images
- Prices
- Add to cart buttons

### Contact Page Structure

- Contact form
- Required input fields
- Submit button
- Contact information

### UX Design Decisions

Design choices included:

- Simple navigation
- Consistent layout
- Luxury colour theme
- Clear typography
- Responsive grid layout
- Accessibility considerations

---

## Features

### Existing Features

- Responsive navigation bar
- Product cards
- Contact form
- Responsive Bootstrap layout
- Footer contact information
- Social media links

### Future Features

Possible improvements:

- JavaScript shopping cart
- Product filtering
- Payment system
- Search function
- Database integration

---

## Technologies Used

### Languages

- HTML5
- CSS3

### Frameworks

- Bootstrap 5

### Tools

- Git
- GitHub
- GitHub Pages
- Google Fonts
- Font Awesome

---

## Information Architecture

The site contains 4 pages:

- Home (index.html)
- Products (products.html)
- Contact (contact.html)
- Cart (cart.html)
- Success page

Navigation is consistent across all pages.

---

## Testing

### Manual Testing

| Page | Test | Result |
|------|------|--------|
| Home | Navigation links | PASS |
| Home | Images display | PASS |
| Home | Responsive layout | PASS |
| Products | Product cards display | PASS |
| Products | Add to cart links | PASS |
| Contact | Form validation | PASS |
| Contact | Required fields | PASS |
| Contact | Submit works | PASS |
| All | Mobile responsive | PASS |

---

## Bugs Found and Fixed

| Bug | Problem | Fix |
|-----|---------|-----|
| Navbar overlap | Header covered content | Added body padding |
| Card alignment | Buttons uneven | Used flexbox |
| Form error | Form inside form | Removed duplicate form |

---
## Evidence of Design Implementation

## Navigation Design
-  A responsive navigation bar is implemented using Bootstrap
-  Includes links to all main pages (Home, Products, Contact, Cart)
-  Mobile-friendly collapsible menu improves usability

## Page Layout Design
* Semantic HTML structure used:
    - <header> for hero section
    - <main> for content
    - <section> for grouped information
    - <footer> for contact details
* Grid layout used for product display

## Accessibility Design
    - All images include descriptive alt text
    - High contrast colour scheme used
    - Responsive design supports all devices
    - Semantic elements improve screen reader support
    - Navigation accessible via keyboard

## UX Design Implementation
    - Clear visual hierarchy using headings
    - Content prioritised (hero → products → contact)
    - Consistent layout across pages
    - Simple and intuitive navigation

## Validation

### HTML Validation

HTML was tested using W3C validator.
https://github.com/Y40Y50/yahyaPerfumes/blob/3b9db33785234be707633b5162b5b1e622a3b361/assets/images/Screenshot%202026-03-31%20154726.png
Results:
- No major errors
- Semantic structure correct
- Accessibility structure good

## Screenshot:
[HTML Validation](assets/images/html-validation.png)

### CSS Validation

CSS tested using Jigsaw validator.
https://github.com/Y40Y50/yahyaPerfumes/blob/3b9db33785234be707##633b5162b5b1e622a3b361/assets/images/css%20validation.png
Results:

- No major errors
- CSS variables working correctly
## Screenshot:
[HTML Validation](assets/images/css-validation.png)

---

## Deployment

The project was deployed using GitHub Pages.

### Steps:

1 Create repository on GitHub
2 Upload project files
3 Commit changes
4 Enable GitHub Pages
5 Deploy from main branch
Project link:
https://github.com/Y40Y50/scaling-fiesta

---

## Version Control

Git was used throughout development.

Commits were made to track:

- Layout changes
- Styling improvements
- Bug fixes
- Feature additions

---

## Credits

### Resources Used

Bootstrap:
https://getbootstrap.com/
Google Fonts:
https://fonts.google.com/
Font Awesome:
https://fontawesome.com/

### Images

Images used for educational purposes only.

---

## User Stories with Evidence
## User1 Browse perfumes
    As a customer I want to browse perfumes so I can choose one

## Evidence:
    Products displayed using card layout
    Images, descriptions, and prices clearly visible

## Screenshot:
[Products Page](assets/docs/Products-page.png)

## Clear navigation
    As a customer I want clear navigation so I can find products easily

## Evidence:
    Navigation bar visible on all pages
    Links to Home, Products, Contact, Cart

## Screenshot:
[Home Page](assets/docs/home-page.png)

## Mobile responsive design
    As a user I want mobile responsive design so I can use my phone

## Evidence:
    Responsive Bootstrap layout
    Collapsible mobile menu
## Screenshot:
[Mobile View](assets/docs/mobile-view.png)

## Contact information
    As a customer I want contact information so I can ask questions

## Evidence:
    Address, phone, email clearly displayed
    Social media links included

## Screenshot:
[Contact Page](assets/docs/Contact-page.png)

## View product prices
    As a user I want product prices visible so I can compare

## Evidence:
    Prices clearly shown on each product card

## Screenshot:
[Products Page](assets/docs/Products-page.png)

## Development Process

Development followed this order:

1 Planning structure
2 Creating HTML pages
3 Adding CSS styling
4 Adding Bootstrap layout
5 Making responsive design
6 Testing pages
7 Fixing bugs
8 Deployment

---

## Testing Lifecycle

Testing included:

- Manual navigation testing
- Responsive testing
- Form validation testing
- Link testing
- Layout testing

---

## Author

Developed by Yahya Ahmed  
Frontend Development Student Project

---

## Final Notes

This project demonstrates:

- HTML structure
- CSS styling
- Responsive design
- UX design principles
- Testing process
- Version control

