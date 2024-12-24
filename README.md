Layout 3 Project - 100Devs

Overview

This project is part of the 100Devs course, designed to help students develop a solid understanding of CSS fundamentals. The goal is to create a responsive web page layout inspired by the TechCrunch homepage. All layout positioning is achieved using float, without the use of id or class selectors. This approach ensures mastery of foundational CSS techniques.

Goals

- Build a visually appealing and functional web page layout inspired by the TechCrunch design.
- Practice using the float property for layout positioning.
- Develop an understanding of the challenges and limitations of float-based layouts.
- Strengthen skills in writing clean, semantic HTML and efficient CSS.

Technologies Used

HTML5: To create a semantic and accessible structure.
CSS3: To style and position elements using float and pseudo-classes.

Project Structure

project-folder/  
|-- index.html  
|-- assets/  
    |-- css/  
        |-- styles.css  
    |-- images/  


- index.html: Contains the HTML structure of the webpage, including headers, sections, and footers. All styling is applied using generic HTML tags and pseudo-classes.
- assets/css/styles.css: Includes the CSS file with all styles defined using the float property.
- assets/images/: Contains all the images used in the layout, such as the collage image for the hero section.

Features

Navigation Bar

- Position: Fixed at the top of the page.
- Content:
  - Logo positioned on the left.
  - Links for "Courses," "Search," and "More," along with user actions like "Login" and "Sign-Up."
- Styling:
  - Background: White or light gray.
  - Text: Black with hover effects, such as color changes or underlines.

Hero Section
- Position: Just below the navigation bar, spanning the full width of the page.
- Content:
  - Bold and attention-grabbing headline (e.g., "Empowering the Next Generation of Learners").
  - Short tagline below the headline.
  - Two action buttons: "Get Started" and "Learn More."
  - Collage-style image alongside the text or as a background.
- Styling:
  - Clean and modern fonts (e.g., Open Sans, Roboto).
  - Subtle gradient or clean white layout for the background.

Main Content
- Position: Below the hero section, occupying the primary viewport.
- Sections:
  - Featured Stories:
    - Grid layout showcasing articles or key features.
    - Each grid item includes:
    - Thumbnail image.
    - Title (e.g., "Revolutionizing Quantum Computing").
    - Brief description or author name.
   - Latest Articles:
    - Two-column layout featuring smaller image thumbnails, titles, and timestamps.
- Styling:
  - Consistent spacing and padding between sections.
  - Alternating background colors for sections to improve readability.

Footer
- Position: Stretches across the bottom of the page.
- Content:
  - Links: Privacy Policy, Terms of Service, and Contact Us.
  - Social media icons for platforms like Twitter, LinkedIn, and Facebook.
  - Newsletter subscription field with a "Subscribe" button.
- Styling:
  - Background: Dark gray or black.
  - Text: Light gray or white for contras

Instructions to Run
Clone the repository using the command:

git clone <repository-url>

Navigate to the project folder:

cd project-folder

Open the index.html file in any web browser to view the layout.

CSS Layout Using Float

- Use float: left; to position elements side by side.
- Clear floats by applying .clearfix or overflow: hidden; to parent elements.
- Use generic tag selectors (e.g., h1, p, ul) and pseudo-classes for styling instead of ids or classes.
- Test responsiveness by resizing the browser and adjusting padding/margins to ensure consistency across different screen sizes.

Learning Outcomes

- Understand the fundamentals of float-based layouts and their limitations.
- Write clean, semantic HTML without relying on ids or classes.
- Develop a deeper appreciation for modern CSS techniques like Flexbox and Grid after mastering float challenges.
- Strengthen problem-solving skills by overcoming common float issues like collapsed parents and layout inconsistencies.


