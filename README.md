# Assignment-9
# Assignment 9 – Practice with jQuery Selectors and Events

## Overview
This project demonstrates the use of **jQuery selectors, commands, and event handling** to manipulate and interact with web page elements dynamically.

The assignment is divided into two main parts:
1. **Selectors and Commands**
2. **Event Handling**

---

## Part 1: jQuery Selectors and Commands

### Objective
Use jQuery to select and modify HTML elements in a sample webpage (e.g., the Vecta Corp site).

### Steps

1. **Setup**
   - Download the jQuery library (do **not** use a CDN).
   - Include it in your web page using a `<script>` tag.
   - Create a `$(document).ready()` function to hold all jQuery code.

2. **Styling Headings**
   Apply the following styles to all `<h2>` elements within `<section>` and `<aside>`:
   - Border: `1px solid black`
   - Color: `#CC1C0D`
   - Padding: `3px 0 3px 20px`
   - Border-radius: `5px` (top-right and bottom-left corners)
   - Background-color: `#DFE3E6`

3. **Navigation Menu**
   - Add a class `navigation` to each of the five navigation items.
   - Style `.navigation` with:
     - Border: `1px solid #929CA4`
     - Color: `#CC1C0D`
     - Padding: `3px 0 3px 20px`
     - Background-color: `#DFE3E6`

4. **Main Content**
   - Remove the classes `vprospect`, `vconvert`, and `vretain` from `<p>` elements inside the `<section>`.
   - Add the text **“Chevy Dealers Association”** below the word *“President”* in the client testimonials section (include a line break).
   - Wrap the testimonial text with `<q>` tags.

---

## Part 2: jQuery Events Practice

### Objective
Use various jQuery methods to handle user interactions.

### Exercises

1. Create a button that shows an alert when clicked using **`.click()`**.
2. Create a button that triggers an alert when clicked using **`.bind()`**.
3. Create a button that triggers an alert when clicked using **`.on()`**.
4. Create **two buttons** that share the same click event handler via **`.on()`**.
5. Create a `div` (400x400px) that responds with alerts for **click**, **mouseenter**, and **mouseleave** events.
6. Modify exercise 5 to display messages inside a `<span>` instead of using alerts.
7. Create a link to `https://modulemedia.com` that:
   - Prevents navigation on click.
   - Changes color to red.
   - Displays the triggering node name in an alert.
8. Create a `div` that displays the browser window’s width and height as the window resizes.
9. Create a text `<input>` that:
   - Changes background to light gray on focus.
   - Returns to white when it loses focus.
10. Create a form with `name` and `email` fields:
    - If any field is empty on submit, alert the user and set the border color to red.
    - If both are filled, set borders to green.

---

## How to Run

1. Download or clone the project files.
2. Ensure the local jQuery library file (e.g., `jquery-3.7.1.min.js`) is in the same directory.
3. Open the main HTML file (e.g., `assignment9.html`) in your web browser.
4. Inspect the console or UI interactions to verify the results.

---

## Files

- `assignment9.html` — Main HTML file containing structure and embedded jQuery script.
- `jquery-3.x.x.min.js` — Local jQuery library.
- `README.md` — This documentation file.

---

## Author
**[Your Name]**  
Course: *CS648 – Assignment 9*  
Instructor: *[Instructor Name]*  
Date: *[Submission Date]*

---

## License
This project is for **educational purposes only** and not for commercial use.

