# MP1-DTL (User-Centric Frontend Development Milestone Project)

## Table of Contents
1. [Project Overview](#project-overview)
2. [User Experience (UX)](#user-experience-ux)
    - [Project Goals](#project-goals)
    - [User Stories](#user-stories)
    - [Design](#design)
    - [Wireframes](#wireframes)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Testing](#testing)
    - [Manual Testing](#manual-testing)
    - [Validation](#validation)
    - [Bugs and Fixes](#bugs-and-fixes)
6. [Deployment](#deployment)
7. [Credits](#credits)
8. [Acknowledgements](#acknowledgements)

---

## Project Overview

Deluxe Transportation is a static front-end website designed to present useful information to users about luxury transportation services. This project was developed as part of the User-Centric Frontend Development Milestone Project. The site is intended to meet both the user's needs and the site owner's goals, providing a clear, professional, and accessible user interface.

**[Update: Add Project Link Here]**

## User Experience (UX)

### Project Goals
The goal of this project is to create a responsive, user-friendly website that effectively communicates the services offered by Deluxe Transportation. The website aims to attract potential customers by showcasing the fleet, services, and contact information.

### User Stories
1. **New User Goals**:
    - I want to understand what services the company offers.
    - I want to easily find contact information to book a service.
    - I want to see the fleet of vehicles available for hire.

2. **Returning User Goals**:
    - I want to quickly access booking options.
    - I want to stay updated on new services or changes in offerings.

3. **Frequent User Goals**:
    - I want to contact the company directly through the website.
    - I want to download the company brochure or CV.

### Design
#### Colour Scheme
The website uses a professional colour palette of dark greys, whites, and accent colours like orange and blue to create a clean, modern look.

#### Typography
Two fonts, **Roboto** and **Exo**, are used throughout the website to maintain a balance between readability and style.

#### Imagery
High-quality images of the fleet and services are used to engage the user and convey a sense of luxury and professionalism.

### Wireframes
Wireframes were created to plan the layout of the site across different screen sizes (mobile, tablet, desktop). These wireframes served as a blueprint for the website's responsive design.

**[Update: Add Wireframe Images and Links Here]**

## Features

### Existing Features
1. **Responsive Navigation Bar**:
    - A responsive navigation bar that adjusts to different screen sizes.

2. **Hero Section**:
    - A prominent hero section showcasing the company’s brand and main call-to-action.

3. **Services Section**:
    - Detailed information about the services offered, with visual icons and descriptions.

4. **Fleet Showcase**:
    - A gallery of vehicle images, each with descriptions and specifications.

5. **Contact Information**:
    - Clear and accessible contact details with links to social media profiles.

6. **Footer**:
    - A footer section containing additional navigation and download links.

### Future Features
1. **Online Booking Form**:
    - Adding an interactive form for online bookings (pending the use of JavaScript).

2. **Testimonials Section**:
    - Displaying customer testimonials to build trust and credibility.

## Technologies Used
### Main Technologies
- **HTML5**: For structuring the content of the site.
- **CSS3**: For styling the site.
- **Bootstrap 4.2.1**: For responsive design and layout.
- **FontAwesome**: For icons and visual enhancements.
- **Google Fonts**: For custom typography.

### Tools
- **Git**: For version control.
- **GitHub Pages**: For deployment.
- **Balsamiq**: For creating wireframes.

## Testing

### Manual Testing
The website was manually tested across various browsers (Chrome, Firefox, Safari) and devices (mobile, tablet, desktop) to ensure compatibility and responsiveness.

1. **Navigation**: 
    - Tested all links in the navigation bar to ensure they direct to the correct pages.
    - Verified that the navbar is responsive on mobile devices.

2. **Responsive Design**:
    - Checked that the layout adapts correctly to different screen sizes, ensuring all content is accessible.

3. **Contact Links**:
    - Tested all contact links (email, phone, social media) to ensure they open the correct apps or pages.

### Validation
- **HTML Validation**: The HTML code was validated using the [W3C HTML Validator](https://validator.w3.org/).
- **CSS Validation**: The CSS code was validated using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).

### Bugs and Fixes

- **Bug 1**: **Navigation bar not collapsing on mobile devices.**
  - **Fix**: Adjusted the Bootstrap classes to ensure the collapse functionality works without JavaScript.

- **Bug 2**: **Footer overlapping content on smaller screens.**
  - **Fix**: Added appropriate padding to ensure the footer stays at the bottom of the page.

- **Bug 3**: **Video background in the hero section not displaying full width.**
  - **Fix**: Used Bootstrap's grid system and CSS adjustments to ensure the video background covers the entire width of the screen across different device sizes.

- **Bug 4**: **Button styling in the hero section not matching the requested yellow color.**
  - **Fix**: Updated the CSS to apply the correct yellow background color (`#f8c146`) and appropriate hover effects to the button.

- **Bug 5**: **"Stay in Touch" text in the footer not properly aligned.**
  - **Fix**: Adjusted the padding and positioning in the CSS to ensure the "Stay in Touch" text and icons have consistent spacing and are properly aligned.

- **Bug 6**: **Hero section video not playing or not fitting correctly.**
  - **Fix**: Reorganized the HTML structure for the hero section, added a full-width container for the video background, and ensured the video is responsive across all device sizes.

- **Bug 7**: **Issues with the hero section video alignment.**
  - **Fix**: Used `object-fit` and Bootstrap's grid system to center the video and ensure it scales correctly while maintaining the desired layout.

- **Bug 8**: **Video background in the hero section positioned incorrectly, sitting in the bottom right corner.**
  - **Fix**: Used `position-absolute`, `top: 50%`, `left: 50%`, and `transform: translate(-50%, -50%)` to center the video and ensure it covers the entire section.

- **Bug 9**: **Hero section video height extending beyond the desired area, affecting the layout.**
  - **Fix**: Removed `height: 100vh;` and ensured the video scales correctly with `object-fit: cover` to maintain the proper aspect ratio.

- **Bug 10**: **"Book Now" button in the hero section not performing the same action as the submit button.**
  - **Fix**: Replaced the `<a>` tag with a `<button>` tag and added `onclick="alert('Service not enabled');"` to trigger the same alert as the submit button.

- **Bug 11**: **Content in the hero section not fading in sequentially.**
  - **Fix**: Added CSS animations using keyframes and `animation-delay` to create a staggered fade-in effect for the `<h1>`, `<p>`, and button elements.

- **Bug 12**: **Buttons not centered or sized appropriately in the contact form.**
  - **Fix**: Used Bootstrap's `d-flex`, `justify-content-center`, and `btn-sm` classes to center the buttons and make them smaller for a better layout.

## Deployment

### GitHub Pages
The project was deployed using GitHub Pages. The deployment process is as follows:

1. **Clone the Repository**: 
    - Run `git clone [Update Repository URL]`.
2. **Navigate to the Project Directory**:
    - Use `cd [Update Project Directory]`.
3. **Push to GitHub**:
    - Run `git push origin main`.
4. **Deploy to GitHub Pages**:
    - Go to the repository settings on GitHub.
    - Under the "GitHub Pages" section, select the main branch as the source.

**[Update: Add Deployed Project Link Here]**

### Running Locally
To run the project locally, follow these steps:

1. **Clone the Repository**:
    - Run `git clone [Update Repository URL]`.
2. **Open the Project**:
    - Open the `index.html` file in your browser.

## Credits

### Content
- The text content was created specifically for the Deluxe Transportation project.

### Media
- **Images**: Images were sourced from **Pexels** and **Google Images**. Specific credits:
    - **Image**: (https://wwww.pexels.com)
    - **Images**: (https://wwww.google.com)
    - **Videos**: (https://wwww.google.com)
- **Logo**: The logo was purchased and owned by the project owner.

### Code
- **Bootstrap and FontAwesome**: External libraries used for styling and icons.

## Acknowledgements
- I would like to thank [Teacher & Mentor's Name] for their guidance and support throughout the project.
