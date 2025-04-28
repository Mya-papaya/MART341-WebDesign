# Website Development Techniques Documentation

This document outlines the techniques used in developing the Sustainable Eats website. Each required technique has been applied thoughtfully to enhance the functionality and user experience. Below, I describe how and why each technique was applied.

## Required Techniques

### 1. **At Least 4 Pages**
   - **Technique Applied**: The website contains a minimum of four distinct pages that align with a cohesive theme around sustainable eating and eco-friendly practices.
     - **Pages**:
       - `Home` – The main page that introduces the purpose of the site.
       - `Featured` – A page highlighting featured recipes.
       - `Recipes` – A page where users can submit and browse recipes.
       - `Contact Us` – A page for users to reach out for further inquiries.
   - **Why Applied**: Multiple pages are crucial for organizing content into digestible sections and improving overall website navigation and user engagement.

### 2. **Responsive Design**
   - **Technique Applied**: The website layout adjusts smoothly across different screen sizes using CSS properties and flexible layout techniques.
     - **Responsive behavior**: The layout switches between a multi-column view on desktops to a single-column layout on mobile devices.
   - **Why Applied**: Ensuring the website is mobile-friendly and responsive helps reach a broader audience and provides an optimal viewing experience across various devices, such as desktops, tablets, and smartphones.

### 3. **Media Queries**
   - **Technique Applied**: CSS media queries are used to make design adjustments at specific screen widths.
     - **Breakpoints**: 
       - At `max-width: 1024px`, the content adjusts to fit smaller screens (tablets).
       - At `max-width: 768px`, the navigation menu becomes a vertical stack, and other elements reflow accordingly for smaller screens.
       - At `max-width: 480px`, buttons and content width adapt to be full-screen for smaller mobile devices.
   - **Why Applied**: Media queries allow the design to adapt and provide an enhanced user experience on different devices, ensuring content is always legible and well-organized.

### 4. **Navigation Menu**
   - **Technique Applied**: The website includes a clear and user-friendly navigation menu. The navigation bar at the top allows visitors to easily access the main sections of the website.
     - **Menu Items**:
       - Home, Featured, Recipes, Forum, Contact Us, About
   - **Why Applied**: A well-structured navigation menu is essential for guiding users through the website. It ensures that visitors can quickly find the information they are looking for, improving usability and user satisfaction.

### 5. **Dropdown Menu**
   - **Technique Applied**: A dropdown menu is implemented within the navigation bar for the `Recipes` section. It allows users to access sub-pages like submitting recipes and browsing featured recipes.
     - **Dropdown Items**:
       - Submit Recipe
       - Browse Recipes
   - **Why Applied**: The dropdown menu helps in organizing related content into a collapsible section, keeping the main navigation clean while still offering easy access to more specific areas of the website.