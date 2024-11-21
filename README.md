# Accessibility Quiz  
#### Learned it from [freeCodeCamp](https://www.freecodecamp.org/) || See it live at [CodePen](https://codepen.io/shady-ashraf/pen/LYwKaYZ)  
###### Accessibility is making your webpage easy for all people to use – even people with disabilities. In this course, you'll build a quiz webpage. You'll learn accessibility tools such as keyboard shortcuts, ARIA attributes, and design best practices.

---

## Table of Contents  
- [Overview](#overview)  
- [Features](#features)  
- [File Structure](#file-structure)  
- [HTML Details](#html-details)  
- [CSS Styling](#css-styling)  
- [Deployment](#deployment)  
- [Selectors Used in the Project](#selectors-used-in-the-project)  

---

## Overview  
The **Accessibility Quiz** is a project that collects user information and quizzes users on HTML and CSS concepts while adhering to accessibility standards.

**Technologies used:**  
- HTML5  
- CSS3  
---

## Features  
- User-friendly, accessible layout with responsive design.  
- Form validation for email, date of birth, and required fields.  
- Multiple-choice questions for HTML and CSS concepts.  
- Dropdown menus, text areas, and radio buttons for input flexibility.  
- Clear navigation for jumping between quiz sections.  

---

## File Structure  
```
project/
├── index.html  
└── styles.css  
```

---

## HTML Details  
The HTML file (`index.html`) contains:  
- **Form Elements:**  
  - Text inputs for name, email, and date of birth.  
  - Radio buttons for multiple-choice questions.  
  - Dropdown menu for CSS-related questions.  
  - Text area for open-ended feedback.  
- **Accessibility Features:**  
  - `aria-labelledby` for section roles.  
  - Labels explicitly associated with inputs using `for` attributes.  
  - Hidden labels (`sr-only` class) for screen readers.  

---

## CSS Styling  
The CSS file (`styles.css`) provides modern, responsive styling:  
- **Theme:**  
  - Light background (`#f5f6f7`) with contrasting dark text (`#1b1b32`).  
- **Form Styling:**  
  - Responsive layout with a max width of 600px.  
  - Styled inputs and buttons for consistency and usability.  
- **Interactive Design:**  
  - Smooth scrolling with `scroll-behavior: smooth`.  
  - Hover effects for navigation links and buttons.  

---

## Deployment  
1. Clone the repository:  
   ```bash  
   git clone https:https://github.com/shadyashraf174/Quiz.git  
   ```  
2. Open the `index.html` file in any web browser.  

---

## Selectors Used in the Project  

### **Selectors in HTML**  

#### **Element Selectors**  
- **`<header>` and `<footer>`**: Define page header and footer.  
- **`<form>`**: Encapsulates input elements for the quiz.  
- **`<fieldset>` and `<legend>`**: Group related inputs with captions.  
- **`<label>` and `<input>`**: Associate input fields with descriptive labels.  
- **`<ul>` and `<li>`**: Organize multiple-choice answers.  
- **`<select>` and `<option>`**: Create dropdown menus for selection.  
- **`<textarea>`**: Collect open-ended responses.  

---

### **Selectors in CSS**  

#### **Element Selectors**  
- **`body`**: Sets background, font, and margin for the entire page.  
- **`h1`, `h2`**: Customize font and spacing for headings.  
- **`form`**: Defines the container width and layout.  
- **`button`**: Styles the submit button with padding and hover effects.  

#### **Class Selectors**  
- **`.info`**: Styles input fields and labels in the form.  
- **`.answers-list`**: Removes bullets for multiple-choice answers.  

- **`@media (prefers-reduced-motion: no-preference)`**:
This media query checks whether the user has indicated a preference for motion effects on their device. If the user hasn't opted to reduce motion, the styles within the query will apply.

#### **Pseudo-Class Selectors**  
- **`input:hover`**: Highlights fields on hover.  
- **`li:hover`**: Adds interactivity to navigation links.  

---

![image](https://github.com/user-attachments/assets/44862ef4-aee9-4ab0-a8e1-2236338ad057) 

--- 
