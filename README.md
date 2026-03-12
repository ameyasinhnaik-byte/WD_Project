# Ameya's Portfolio Website

## Project Overview

This is a personal portfolio website for showcasing Ameya’s (my) professional background, including my experience, services, about section and contact information. The site is designed with a clean layout and modern style, making it easy for visitors to explore my work. This website also gives a brief description about my past work and also allows for visitors to contact me. This website can be used a job portfolio or for internships by tweaking some information. The website is designed to be responsive on different screens thus giving a user-friendly experience to the visitors. The website is static and the color scheme which is added is visually appealing to the eyes, which enhances the structure of the webpage.

ps: this website is just a experiment which was created for learning html, css and javascript and I don't have the qualifications mentioned on the page!!

## How to Open/View

1. Download the zipped folder added in the submission and **unzip** it.
2. Make sure that you have all the files (portfolio1.html, projects.html, about.html, contact.html), the respective css files, and the png images.
3. **If any of these are absent then the webpage won't work as intended.**
4. Open the ``portfolio1.html`` file in any modern web browser (e.g., Chrome, Firefox, Edge).
5. No additional server setup is needed — it's a static website.
6. ps : **Don't forget to unzip the folder.**

##  Tools & Technologies Used

#### HTML5 
HTML5 is the backbone of this portfolio website. It structures all the content you see on the page, including headings, sections, images, and links. Using semantic HTML tags such as `<header>`, `<section>`, `<nav>`, and `<footer>`, the website is well-organized and more accessible to users and search engines. The `DOCTYPE html` declaration at the top ensures that browsers render the page in standards mode. Additionally, meta tags are used for responsive design and character encoding to improve usability across devices and platforms.

####  CSS3 
CSS3 is responsible for the design and layout of the website, turning plain HTML into a visually appealing and user-friendly experience. This project uses both traditional CSS properties and modern techniques such as Flexbox for layout alignment. Key styling features include:
- Custom color schemes for backgrounds, text, and hover effects
- Responsive layouts using `vw` (viewport width) and `vh` (viewport height)
- Hover animations to enhance interactivity in navigation links and footer items
- Box models and spacing (using `margin` and `padding`) for clean section separation
- Rounded corners and subtle shadows for modern, card-like sections
This website avoids external CSS frameworks like Bootstrap to maintain custom styling and lightweight code.

#### Other Pages
This website also includes other pages such as the projects.html, about.html, contact.html, which have been linked to portfolio1.html. This creates a more professional website and prevents cluttering of information on a single page. The color scheme of the home is has been followed in the other pages and the other pages are also designed to be responsive. In the contact.html, basic form elements such as input type = "Text", input type = "Email", input type = "Textarea" have been used. The projects.html features the my previous projects and the About.html gives a slight overview of me as a person along with my work information

####  Google Fonts (Poppins)
Typography plays a huge role in the design of this portfolio. The **Poppins** font from [Google Fonts](https://fonts.google.com/specimen/Poppins) is imported to give the website a modern and professional look. It supports different font weights like 400 (regular), 600 (semi-bold), and 700 (bold) to create a visual hierarchy and make headings stand out while keeping body text clean and readable.

The font is loaded via `<link>` tags and applied universally through the `font-family` property in CSS, ensuring consistency across the site.

#### Typed.js Library
Typed.js is a lightweight JavaScript library used in this portfolio to create a dynamic typing animation effect in the hero section (the "Hi, my name is..." area). This library brings movement and interactivity, helping to catch the visitor's attention. In this project:
- Multiple roles (like "Web Developer", "SEO Specialist", "Digital Marketer", "Video Editor") are displayed one after another with typing and backspacing effects.
- The typing speed is controlled using the `typeSpeed` option.
- The animation is initiated by targeting a specific `<span>` element using its ID (`#element`).

By using Typed.js, the site feels more dynamic and engaging without adding much extra code or slowing down the loading speed.
#### Hamburger Icon
- I used a simple button with a hamburger `(☰) `icon as the toggle trigger.
- On larger screens, the navigation links are displayed horizontally.
- On smaller screens, the links are hidden by default and shown when the hamburger button is clicked.
- This is handled using CSS media queries and a small JavaScript function (in some code inBuilt and in some I have created them) that adds/removes a .show class to the links container.

#### Images and Assets
Custom PNG images are used for the experience timeline (e.g., `html.png`, `node.png`, `insta.png`, `whatsapp.png`) and profile area (`pi.png`). The layout ensures these images are responsive and blend well with the surrounding text and background, providing visual cues about each role and technology.

##  References & Resources

- [Typed.js Documentation](https://github.com/mattboldt/typed.js/)
- [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)
- Basic layout inspiration from online portfolio templates, personal design preferences & youtube videos  
---
#### Name: Naik Ameya Vaibhav
#### COEP Technological University 
