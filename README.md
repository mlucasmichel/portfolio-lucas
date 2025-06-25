
# My Portfolio

A multi-page personal portfolio site developed as part of the Code Institute’s Web Development Diploma.

---

## Features

- **Multi-Page Structure** — Home, Projects, Contact  
- **Responsive Navigation** — consistent on all pages  
- **Hero Section** — intro text and Call-To-Action  
- **Projects Section** — grid with project cards  
- **Contact Form** — accessible labels with name, email, phone and message fields
- **Footer** — social icons & logo  
- **Responsive Design** — adapts well to mobile, tablet and desktop

---

## UX Design

### Project Goals
The goal of this project is to create a space where I can showcase my skills and recent projects to potencial recruiters, colleagues or people who just want to know more about me!
### User Goals  
- Quickly understand who I am 
- Review projects
- Contact me.
### Business/Dev Goals  
- To have a digital "business card"
- Establish web presence 
- Demonstrate skills.
### User Stories
As a visitor, I want to: 
- Navigate through the website easily, so I can explore different sections.
- See a clear introduction and visual representation of the developer's role or skills
- Learn more about the developer, so I can understand their background.
- See the developer's projects, so I can evaluate their work
- Contact the developer, so I can reach out for collaboration or questions.

### Design Choices
The color palette was chosen to reflect who I am. Red for the energy and passion I bring to learning and creating, and grey for the calm, thoughtful approach I take to solving problems. It's a mix that feels like me: focused, curious, and driven.

The rounded card style for each section was used to keep things clean and modern. It helps break up the content nicely and makes everything easier to read without feeling too formal or cluttered. 

### Wireframes
Wireframes created with [Wireframe.cc](https://wireframe.cc):

| Home | Projects | Contact |
|--|--|--| 
|[Mobile](https://wireframe.cc/xbEQ7C) | [Mobile](https://wireframe.cc/fFB90Q) |[Mobile](https://wireframe.cc/9ur1d1) | 
|[Desktop large](https://wireframe.cc/wI3rSN) | [Desktop Large](https://wireframe.cc/RGRC3M) |[Desktop Large](https://wireframe.cc/W3wCp4) | 
|[Desktop XL](https://wireframe.cc/Qg8dV0) | [Desktop XL](https://wireframe.cc/tHcuNC) | [Desktop XL](https://wireframe.cc/44l4Af)|

---

## Technologies Used

- **Languages**: HTML, CSS  
- **Frameworks**: Bootstrap
- **Tools**:  
  - Git & GitHub  
  - GitHub Pages  
  - Visual Studio Code  
  - WebAIM Accessibility Tools  
  - W3C Validators
  - Gimp

---

## Testing

### Manual Testing

- **Navigation**
  - All navigation links work and go to the correct pages.
  - Navigation is with keyboard is possible (using tab and enter keys).

- **Form**
  - Contact form validates for mandatory fields (name, email and message).
  - Email field asks for valid email format.
  - Submit button only works when form is completely filled.
  - Placeholder text and labels are clear and accessible.

- **Responsivess**
  - Layout adapts well to different screen sizes:
    - Mobile: Xiaomi 13 Pro, Samsung Galaxy S22
    - Tablet: iPad, Samsung Tab
    - Desktop: 15" to 27” screens
  - Text is legible and buttons accessible on every breakpoint.

- **Footer & Social Links**
  - All external links open in new tabs and have `rel="noopener"` attributes.
  - Hover state is visible.

- **Images & Alt Text**
  - All images load correctly and contain `alt` attributes.


### Validation

- **HTML**
  - HTML was validated with [W3C HTML Validator](https://validator.w3.org/)
  - No major errors or warnings.

- **CSS**
  - CSS was validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
  - No major errors.


### Accessibility Testing

- Semantic HTML elements used (e.g. `<nav>`, `<main>`, `<section>`, `<footer>`).
- Site is navigable using a keyboard (using tab and enter keys).
- All form elements have visible labels and placeholders.
- Tested with [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) audit:
  - Accessibility score: **90+** (on mobile and desktop).
  - Identified no accessibility issues.

---

## Deployment

This project was developed using VS Code and version-controlled with Git. All changes were regularly committed and pushed to GitHub during development.

### GitHub Pages

The site is deployed using **GitHub Pages** directly from the `main` branch. To deploy your own version:

1. Log in to [GitHub](https://github.com).
2. Navigate to your project repository.
3. Go to **Settings** → **Pages** in the left-hand menu.
4. Under **"Source"**, select the `main` branch and set the folder to `/ (root)`.
5. Click **Save**. GitHub will generate a live link to your deployed site.
6. The live site will be automatically updated whenever changes are pushed to `main`.

### Running the Project Locally

If you'd like to run this project on your own machine:

1. Go to the repository on GitHub.
2. Click the green **Code** button and copy the HTTPS link.
3. Open a terminal in your preferred code editor or IDE.
4. Use the following command to clone the project:
   ```bash
   git clone https://github.com/mlucasmichel/portfolio-lucas.git
   ```
5. Move into the project directory:
   ```bash
   cd your-repo-name
   ```
6. Open the index.html file in your browser.

---

## Credits

### Content

- All written content was created by me

### Media

- Images:
  - Screenshots for projects page taken by me and cropped using [Gimp](https://www.gimp.org/)
  - Profile illustration generated using Samsung AI
- Icons from [Font Awesome](https://fontawesome.com/)

### Code

- Code for box-shadows taken from https://getcssscan.com/css-box-shadow-examples
    ```CSS
    box-shadow: rgba(67, 71, 85, 0.27) 0px 0px 0.25em,
    rgba(90, 125, 188, 0.05) 0px 0.25em 1em;
    ```


### Acknowledgments

- Thanks to Code Institute for all the support

---
