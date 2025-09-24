# Ashley's Registration Form

## Project Overview
This is a responsive registration form built using HTML, CSS, and JavaScript. It allows users to enter their personal information and displays the submitted data on the page without refreshing. The form includes fields for first name, last name, email, password, birthdate, and interests.

## Features
- Dark theme with neon accents
- Input fields with hover and focus effects
- Submit button with animated glow on hover
- JavaScript-powered form handling
- Displays submitted data dynamically
- Clears inputs after submission

## Technologies Used
- HTML5 for structure
- CSS3 for styling and layout
- JavaScript for interactivity

## How It Works
1. User fills out the form.
2. On submit, JavaScript prevents page refresh.
3. Input values are collected and displayed in a styled output section.
4. Inputs are cleared for the next entry.

## What I Learned

- How to use querySelector and addEventListener in JavaScript
- How to style form elements with hover and focus effects
- How to dynamically update the DOM using innerHTML
- How to loop through checkboxes and collect selected values

## Challenges I Faced

- Understanding how to connect JavaScript to the form without refreshing the page was tricky at first. I learned how to use `event.preventDefault()` to stop the default behavior.

- I struggled with selecting multiple inputs and applying consistent styles. At first, I only styled the first and last name fields in class, but I figured out how to loop through all inputs using `querySelectorAll`.

- Getting the submitted data to display correctly in the output section took some trial and error. I had to learn how to access values from different input types, including checkboxes.


## Accessibility & ARIA Enhancements

This project includes several accessibility improvements using semantic HTML and ARIA attributes to support users with assistive technologies:

- **Navigation landmark**: The `<nav>` element includes `role="navigation"` to help screen readers identify the section as a navigational region.
- **Input with `aria-label`**: The first name field uses `aria-label="First name"` to provide a descriptive label for screen readers without displaying a visible label.
- **Input with associated `<label>`**: The last name field uses a visible `<label>` linked to the input via `for="lastName"` and `id="lastName"` for clear accessibility.
- **Button with `aria-label`**: The submit button includes `aria-label="Submit registration form"` to clarify its purpose beyond the visible "Send" text.
- **Link with `role="button"`**: A styled link includes `role="button"` and keyboard support to behave like a true button for screen reader users.

Additionally, I’ve included two paragraphs in the HTML explaining the purpose of ARIA and web accessibility in my own words.



## Author
Created by Ashley — When I had to ask for help or examples, every line was still typed manually to reinforce learning and build confidence with HTML, CSS, and JavaScript.