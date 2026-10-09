# Assignment 1 – Personal Portfolio Website

## 1. Project Description

For Assignment 1, I created a personal portfolio website using HTML5 and CSS3. The purpose of my website is to introduce myself, showcase my technical skills and previous projects, and provide visitors with a way to contact me.

My website consists of four separate HTML pages:

- **Home (index.html):** Introduces visitors to my portfolio and provides navigation to the other pages.
- **About Me (AboutMe.html):** Includes information about my interests, educational background, career goals, personal photograph, and introduction video.
- **Projects (Projects.html):** Showcases six projects related to networking, cybersecurity, Python programming, and web development.
- **Contact Me (Contact.html):** Includes a contact form where visitors can enter their information and comments.

I used semantic HTML5 elements such as `header`, `nav`, `main`, `section`, and `footer` to organize the website.

## 2. Responsive Web Design

My website uses responsive web design to improve its appearance and usability across different screen sizes.

I used fluid widths, percentage-based sizing, and CSS media queries to adjust the layout for mobile phones, tablets, and desktop computers.

The viewport sizes selected for the website are:

- **Mobile devices:** 480 pixels and below.
- **Tablet devices:** 481 pixels to 959 pixels.
- **Desktop and laptop devices:** 960 pixels and above.

I organized the responsive design into three separate CSS files:

- **css/mobile.css:** Designed for screens 480px and below. This stylesheet adjusts the website to use the available screen width, reduces padding, and displays navigation links vertically.
- **css/tablet.css:** Designed for screens between 481px and 959px. This stylesheet adjusts content widths and spacing to fit medium-sized screens.
- **css/laptop.css:** Designed for screens 960px and above. This stylesheet maintains a centered website layout with a maximum width of 960px.

The main `style.css` file contains the shared website design, including the header, footer, navigation, colours, and page content.

The website uses `max-width: 100%` for images and videos to help prevent media from overflowing smaller screens.

I did not use CSS Flexbox.

## 3. CSS Gradients

I used two types of CSS linear gradients on the Projects page to improve its visual appearance.

**Regular Linear Gradient**

```css
background: linear-gradient(#F2F0F2, white);
```

This gradient is applied to the main Projects section using the `#projects` selector. It creates a smooth transition from light grey to white.

**Angled Linear Gradient**

```css
background: linear-gradient(135deg, white, #F2F0F2, #79C4F2);
```

This gradient is applied to the individual project boxes using the `.project-box` selector.

The 135-degree angle creates a diagonal transition between white, light grey, and light blue.

Both gradients were selected to improve the appearance of the Projects page while maintaining a consistent colour scheme.

## 4. Colour Scheme

I selected a blue, grey, and dark teal colour palette to create a professional appearance that reflects my interest in information technology, networking, and cybersecurity.

The colours used throughout the website include:

- **Light Grey – #F2F0F2:** Used for content section backgrounds.
- **Light Blue – #79C4F2:** Used for borders, hover effects, and gradients.
- **Bright Blue – #048ABF:** Used for buttons, borders, and accent colours.
- **Dark Blue – #025373:** Used for the header, footer, navigation background, and headings.
- **Dark Teal – #092626:** Used for text and project descriptions.

I applied these colours consistently throughout the four pages to maintain a unified design.

**Adobe Color reference:** [Add your Adobe Color palette link or screenshot here.]

## 5. Website Features

### Navigation

All four pages include navigation links that allow visitors to move between the Home, About Me, Projects, and Contact Me pages.

### About Me Page

The About Me page includes a personal photograph, an introduction describing my interests and goals, and an embedded HTML5 introduction video.

The video uses playback controls and a poster image.

### Projects Page

The Projects page showcases six projects:

1. VLSM Network Design
2. EIGRP Routing Lab
3. VRF-Lite Network Lab
4. Python Programming Project
5. LAN Security Analysis
6. Personal Portfolio Website

Each project includes a heading and a description of the work completed and the skills involved.

### Contact Me Page

The Contact Me page includes a form that allows visitors to enter their contact information and comments.

HTML5 input types and validation attributes are used to help users enter information correctly.

### Footer

The footer contains my university email address and a copyright statement.

## 6. Technologies and Tools Used

- **HTML5:** Used to structure the website and organize its content.
- **CSS3:** Used for styling, responsive design, gradients, and visual effects.
- **Visual Studio Code:** Used to create and edit the website files.
- **Git:** Used for version control.
- **GitHub:** Used to store the website files and development history.
- **GitHub Pages:** Used to publish the website online.

## 7. Testing and Validation

The following tools were selected to test the website:

**W3C HTML Validator**

Used to check the HTML files for markup errors and warnings.

https://validator.w3.org/

**W3C CSS Validator**

Used to check the CSS files for syntax errors.

https://jigsaw.w3.org/css-validator/

**W3C Link Checker**

Used to check navigation links and identify broken links.

https://validator.w3.org/checklink

**Spelling Check**

Used to review the text on the website for spelling mistakes.

**WAVE Accessibility Evaluation Tool**

Used to evaluate accessibility issues, including image alternative text, headings, form labels, and colour contrast.

https://wave.webaim.org/

Validation errors and warnings are reviewed and corrected during development.

## 8. GitHub and Version Control

I used Git and GitHub to manage my portfolio website.

Git commits were used to record changes during development, including updates to the HTML pages, CSS styling, and multimedia files.

The repository is intended to contain all files required to run the website, including the four HTML pages, CSS files, images, and introduction video.

**GitHub Repository:**

https://github.com/joelvictor-ctrl/Assignment01

## 9. Website Deployment

GitHub Pages is used to host the portfolio website so it can be accessed through a web browser.

**Live Website:**

https://joelvictor-ctrl.github.io/Assignment01/

The website includes links to all four pages, allowing visitors to navigate between the different sections.

## 10. Conclusion

Creating this personal portfolio website helped me develop my understanding of HTML5, CSS3, responsive web design, and website development.

Through this assignment, I gained experience creating multiple web pages, organizing content with semantic HTML5 elements, styling a website using CSS, embedding multimedia, creating forms, and using GitHub for version control.

This project also allowed me to showcase my interest in information technology, networking, cybersecurity, and programming.
