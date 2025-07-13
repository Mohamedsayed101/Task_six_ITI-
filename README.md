# Task Six 
This is Tasks for ITI Summer Traninig 

## Features

- Some Responsive Design
- Clean and elegant layout
- Custom CSS variables for easy theming
- Sections included:
  - Navigation Bar
  - Hero Section
  - About Me
  - Services
  - Contact Form
  - Footer

## Technologies

- HTML5
- CSS3
- Git and Github

## File Structure

project/

│

├── index.html

├── style.css

├── README.md

├── images/

│   ├── car-2.jpg

│   └── laptop.jpeg

└── CSS/

│   └── style.css

## Explain section by section

### For HTML

We have several main sections in the `index.html` file:

- **`<head>`**:  
  Contains metadata about the page such as:
  - Character encoding (`<meta charset="UTF-8">`)
  - Page title (`<title>`)
  - Meta tags for SEO and responsive design
  - Link to the external CSS file
  - Favicon link
  - Author and description tags

- **`<body>`**:  
  Includes all the visible parts of the website, organized into several sections:
  
  - **Navigation Bar (`<header>` or custom div)**:  
    A fixed top navigation bar with links to different sections of the page.

  - **Hero Section** *(optional)*:  
    Introductory section that welcomes the user.

  - **About Section**:  
    Provides information about the website owner or the purpose of the site.

  - **Services Section**:  
    Lists the services offered, formatted as a styled list.

  - **Contact Section**:  
    A form where users can input their name, email, phone, and message.

  - **Footer**:  
    Displays copyright and closing information.

Each section is wrapped in a `div` with a specific class name (like `.box`, `.about`, `.contact`) to allow targeted styling.

### For CSS

The `style.css` file is organized into clear sections with comments and CSS variables for easier maintenance. Here's a breakdown of the main parts:

- **:root (CSS Variables)**:  
  Defines global color variables (e.g., `--main-color`, `--text-color`) used throughout the stylesheet for consistency and easy theme updates.

#### Example from the code:
```css
:root {
  --main-color: #8b82df;
  --secondary-color: #6a1c6b;
  --third-color: #9c7eb5;
  --last-color: #87a8e8;
  --fav-color: #dd3344;
  --anthor-color: #19185d;
  --text-color: #fff;
  --highlight-color: #1f6bde;
}
```
- **Global Elements**:  
  Basic resets and shared styles including:
  - `*` selector for box-sizing and margin reset
  - `body` for default font
  - `a`, `h2`, `.box` for consistent styling

- **Container**:  
  The `.container` class is used to define the background image and general layout for the entire website.

- **Navigation Bar (`.nav-bar`)**:  
  - Flexbox layout for aligning logo and links
  - Sticky positioning to keep it fixed on top
  - Styling for hover effects and active states
  - Responsive behavior using media queries

- **About Section (`.about`)**:  
  Background color, text color, and spacing for the section describing the developer or purpose.

- **Services Section (`.services`)**:  
  Custom list style using `::before`, background color, padding, and heading colors.

- **Contact Section (`.contact`)**:  
  - Form styling using `flex-direction: column`
  - Custom input fields and `:focus` effects
  - Button styling with hover effects

- **Footer (`.footer`)**:  
  Simple text-centered design with custom colors.

- **Responsive Design (`@media`)**:  
  A media query for screen widths below `768px`, adjusting layout of navigation links and overall alignment.

## About the Developer

**Name**: Mohamed Sayed Omar  
**Title**: Front-End Developer | Computer Science Student  
**University**: Faculty of Computers and Information, Fayoum University  
**Location**: Fayoum, Egypt  
**Email**: [ms3655@fayoum.edu.eg](mailto:ms3655@fayoum.edu.eg)  
**GitHub**: [Mohamedsayed101](https://github.com/Mohamedsayed101)
**Linked in**: [Mohamed Sayed](https://www.linkedin.com/in/mohamed-sayed-439a54347/)

## Author

Mohamed Sayed
