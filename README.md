# WEDE5020
#ST10508756LETHABO MOHLALA
WebAIM
 The website is fully responsive and works on desktop, tablet and mobile phones using HTML5 and CSS3 only.

## Website Features
* 3 Page Website: Home (index.html), Enquiries (enquiries.html), Contact (contact.html)
* Responsive Navigation Menu with hover effect
* CSS Grid layout for content
* Responsive images
* Media queries for 768px and 480px screen sizes
* Semantic HTML tags: header, nav, main, footer

## File Structure
rosebankcollege1/
├── index.html
├── enquiries.html
├── contact.html
├── css_assets/
│   └── myfirststyles.css
├── images/
└── README.md


## Technologies Used
* HTML5
* CSS3
* CSS Grid - grid-template-columns: auto auto auto
* Flexbox - for navigation
* Media Queries

## Responsive Design Explanation
The file `css_assets/myfirststyles.css` has 2 media queries:

**1. For Tablet - max-width: 768px**
- Body background becomes rgb(117, 193, 102) green
- Container becomes 2 columns
- h1 becomes 30px, h2 becomes 20px, p becomes 10px

**2. For Mobile - max-width: 480px**
- Body background becomes rgb(230, 182, 79) light orange
- Container becomes 1 column (auto)
- nav ul flex-direction becomes column
- nav ul li a display becomes block
- h1 becomes 20px, h2 becomes 15px, p becomes 8px

Responsive image class used:
.responsive-image { max-width: 100%; height: auto; }

## CSS Styling
* CSS Reset applied: margin 0, padding 0, box-sizing border-box
* Header: burlywood background
* nav ul: background rgba(34, 70, 125, 0.877), display flex, list-style none
* nav ul li a:hover: background white, color blue, border-radius 35px
* .container div: background rgba(34, 70, 125, 0.877), white text, margin 5px, padding 20px, border-radius 20px


