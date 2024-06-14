# Interactive-Div-Color-Changer

## Description
This web page demonstrates an interactive feature where clicking on a div element changes its background color using jQuery. The page includes multiple div elements styled with CSS and a jQuery script that handles click events to update their appearance dynamically.

### Components:

1. **HTML Structure**:
    - A series of div elements, each containing a number from 1 to 7.

2. **CSS Styling**:
    - Each div is styled to have a fixed width, height, margin, and border to make them visually distinct and evenly spaced.

3. **JavaScript Functionality (jQuery)**:
    - When any div is clicked, all div elements' background color is reset to white.
    - The background color of the div before the clicked one (if it exists) is changed to green.
    - If the first div (with text "1") is clicked, an alert is displayed stating "Je suis la première div" ("I am the first div").

### Features:
- **Interactive Color Change**: Clicking on a div changes the background color of the previous div.
- **Conditional Alert**: Specific behavior for the first div, including an alert message.
- **Dynamic Content Update**: Utilizes jQuery to dynamically update styles based on user interactions.
