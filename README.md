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
    - A responsive navigation bar that adjusts to different screen sizes, allowing easy access to all parts of the site.

2. **Hero Section**:
    - A prominent hero section with a background video or image, featuring the company's brand and a clear call-to-action button.

3. **Services Section**:
    - Detailed information about the services offered, accompanied by icons and descriptions to provide clarity and visual appeal.

4. **Fleet Showcase**:
    - A gallery displaying images of the fleet, with descriptions and specifications for each vehicle to inform potential customers.

5. **Contact Information**:
    - Easy-to-find contact details, including links to social media profiles, phone numbers, and email addresses, allowing users to get in touch quickly.

6. **Footer**:
    - A footer section with additional navigation links, social media icons, and copyright information, ensuring users have access to key resources and legal information.

7. **Client Testimonials**:
    - A testimonials section showcasing client feedback, helping to build credibility and trust with potential customers.

8. **Animated Fade-in Effects**:
    - Smooth animations for elements like the hero text and buttons, enhancing the user experience by making the site more interactive.

9. **Call-to-Action Buttons**:
    - Prominent buttons throughout the site directing users to important actions such as booking a service or contacting the company.

### Future Features
1. **Online Booking Form**:
    - Adding an interactive form for online bookings (pending the use of JavaScript).

2. **Testimonials Section**:
    - Expanding the testimonials section to include more customer reviews and ratings.

*Please note: Some features may display a "Service Not Enabled" message as this project is a demonstration for the Milestone Project One and does not include full backend functionality.*

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

- **Bug 13**: **During the HTML validation process, a warning was encountered indicating that the document was not mappable to XML 1.0 due to the presence of two consecutive hyphens in comments (e.g., `<!-----Navigation----->`). The warning is related to the way comments are structured with extra hyphens, which conflicts with XML parsing rules.**
  - **Fix**: The comments were updated to be XML-compliant by removing the extra hyphens. For example, the comment `<!-----Navigation----->` was changed to `<!-- Navigation -->`. This ensures that the comments do not interfere with XML processing while still remaining descriptive.

- **Bug 14**: **The HTML validation process flagged an issue with the trailing slashes (`/`) in self-closing tags like `<link />`. While valid in XHTML, trailing slashes are not necessary in HTML5 and can cause issues, especially with unquoted attribute values.**
  - **Fix**: The trailing slashes were removed from the self-closing tags to comply with HTML5 standards. For example, `<link />` was changed to `<link>`. This ensures that the HTML is correctly formatted for HTML5 without any unnecessary elements that could cause validation issues.

- **Bug 15**: **The content cards in the "Welcome to DELUXE TRANSPORTATION" section were displaying with unequal heights, and the padding between the `h2` heading and the cards was insufficient. Additionally, the images inside the cards did not maintain a consistent height, leading to a misaligned layout and visual inconsistency.**
  - **Fix**: Applied Flexbox properties to the card containers to ensure that all cards maintain the same height, regardless of the content within them. CSS was updated to enforce a consistent height for images within the cards. This adjustment ensures that all images are displayed with the same height, further aligning the cards uniformly. Increased the padding between the `h2` heading and the card section to improve spacing and overall layout aesthetics.

- **Bug 16**: **The fleet vehicle images in the "Our Fleet" section were being cropped from both sides due to the `object-fit: cover;` CSS property. This caused important parts of the images to be cut off, leading to a poor visual representation of the vehicles.**
  - **Fix**: The `object-fit` property was changed from `cover` to `contain` for the fleet vehicle images. This adjustment ensures that the entire image is displayed within the card without any cropping, while maintaining the aspect ratio. The `contain` value allows the image to fit within its container, preserving the visual integrity of the vehicle photos.

- **Bug 17**: **Images in index.html were being cropped due to the use of `object-fit: cover` in shared CSS class.**
  - **Fix**: Separated the styling for the images in `index.html` by adding a unique class (`index-card`) to the images on that page. Updated the CSS to use `object-fit: contain` for the `.index-card img` class, ensuring the images maintain their full aspect ratio without cropping, while retaining the `object-fit: cover` setting for images on other pages like `fleet.html`.

- **Bug 18**: **Footer icons (e.g., email, phone, WhatsApp, Facebook) led to 404 error pages when clicked.**
  - **Fix**: Updated the HTML to include an `onclick` event handler for each footer icon. Now, when an icon is clicked, a "Service Not Enabled" alert is displayed instead of leading to a 404 error page. This was achieved by removing the href links and adding `onclick="alert('Service Not Enabled');"` to each anchor tag.

- **Bug 19**: **Fleet vehicle images were being cropped from both sides due to `object-fit: cover`.**
  - **Fix**: Updated the CSS to use `object-fit: contain` instead of `cover` for the fleet vehicle images. This ensures that the entire image is visible without being cropped, providing a better visual representation of the vehicles.

- **Bug 20**: **"Deluxe Transportation" text was not fully visible on mobile.**
  - **Fix**: Added a media query to adjust the `h1` font size for screens with a width of 768px or less. This ensures that the text is fully visible and readable on smaller screens.

- **Bug 21**: **Mobile menu not functioning properly.**
  - **Fix**: The mobile menu issue was resolved by ensuring that the necessary Bootstrap JavaScript components were included and correctly linked. This allows the mobile menu to toggle open and close as intended.

- **Bug 22**: **Button color `#ffcc00` not persisting on click.**
  - **Fix**: Updated the CSS to ensure that the button retains the `#ffcc00` color when clicked and remains consistent throughout the user interaction. This provides a consistent and expected user experience.

- **Bug 23**: **Navigation Bar Issue: "Home" link remains highlighted when navigating to other pages.**
  - **Fix**: The `active` class was manually applied to the corresponding navigation link on each HTML page (`index.html`, `fleet.html`, `services.html`, and `contact.html`). This ensures that the correct page is highlighted when a user navigates to it, providing clear visual feedback about the current page.

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
    - **Vehicle Images**: [Google Photos](https://www.google.com/search?q=vehicle+category+icons&sca_esv=e4392de686f6f47e&sca_upv=1&udm=2&biw=1470&bih=798&sxsrf=ADLYWII-DtPfB9Z6F5AJS5_0i3vFkeYhqQ%3A1724914762416&ei=ShzQZr-NGdqehbIPwdfF-A8&ved=0ahUKEwi_2rmd0JmIAxVaT0EAHcFrEf8Q4dUDCBA&uact=5&oq=vehicle+category+icons&gs_lp=Egxnd3Mtd2l6LXNlcnAiFnZlaGljbGUgY2F0YWdvcnkgaWNvbnNIrjNQpwVY9C1wAngAkAEAmAHGAaABqAmqAQMyLji4AQPIAQD4AQGYAgOgAugCwgIFEAAYgATCAgYQABgHGB7CAggQABgHGAgYHpgDAIgGAZIHAzAuM6AHpQ0&sclient=gws-wiz-serp)
    - **Fleet Image**: [Google Photos](https://www.google.com/imgres?q=luxury%20fleet%20chauffere&imgurl=https%3A%2F%2Fimages.squarespace-cdn.com%2Fcontent%2Fv1%2F654efd4d03812d7a71956efc%2F7860b529-db7b-49e1-ad53-ad5c1f5b2e79%2FBLACKWAZE%2BFLEET%2BOF%2BFIRST%2BCLASS%2BCHAUFFEUR%2BCARS%2B.jpg&imgrefurl=https%3A%2F%2Fwww.blackwaze.co.uk%2F&docid=Q9iOO8CtMBg8VM&tbnid=3mUOOXsRFPW-uM&vet=12ahUKEwj9tKrW0JmIAxXcSkEAHUj6D_8QM3oECGYQAA..i&w=1792&h=1024&hcb=2&ved=2ahUKEwj9tKrW0JmIAxXcSkEAHUj6D_8QM3oECGYQAA)
    - **Service Image**: [Google Photos](https://www.google.com/imgres?q=premium%20services%20chauffere&imgurl=https%3A%2F%2Fwww.nobletransfer.com%2Fupload%2Fuserfiles%2Fimages%2Fnoble-blog-image(3).jpg&imgrefurl=https%3A%2F%2Fwww.nobletransfer.com%2Fblog%2Fstuttgart-airport-transfer-with-premium-limousine-and-chauffer-service-from-noble-transfer%2F&docid=RCL0vxaG_jtZIM&tbnid=C4L4W_xEslG8zM&vet=12ahUKEwiI66720JmIAxUsWEEAHSHYBvkQM3oECHoQAA..i&w=1600&h=1006&hcb=2&ved=2ahUKEwiI66720JmIAxUsWEEAHSHYBvkQM3oECHoQAA)
    - **Contact Image**: [Google Photos](https://www.google.com/search?q=get%20in%20touch&udm=2&tbs=rimg:CSjzhLS2JFOaYXM3cgSjCqu1sgIAwAIA2AIA4AIA&hl=en&sa=X&ved=0CBoQuIIBahcKEwjQlv6005mIAxUAAAAAHQAAAAAQCQ#vhid=oFEqwsXaf7Ax-M&vssid=mosaic)
    - **Videos**: [ShutterStock](https://www.shutterstock.com/video/clip-16780849-4k-big-airplane-landing-dusk)
- **Logo**: The logo was purchased and owned by the project owner.

### Code
- **Bootstrap and FontAwesome**: External libraries used for styling and icons.

## Acknowledgements
- I would like to thank [Teacher & Mentor's Name] for their guidance and support throughout the project.
