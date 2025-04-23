# Simulate-ShortCut-Kye-

This project demonstrates how to use the **Shortkeys (Custom Keyboard Shortcuts)** browser extension to interact with web elements using JavaScript. Below are examples of scripts for different scenarios:

## 1. Focusing on an Input Field by ID
Use this script to focus on an input field with a specific `id`:

```javascript
var element = document.getElementById('call_details_save1');
if (element) {
    element.focus();
    console.log(element);
} else {
    console.log('Element not found');
}


2. Clicking a Button by ID
Use this script to click a button with a specific id:

var element = document.getElementById('end_phone');
if (element) {
    element.click();
    console.log(element);
} else {
    console.log('Element not found');
}

3. Clicking an Element by Class Name
If the element does not have an id but has a class, use this script to click a specific element in the class list:

var buttons = document.getElementsByClassName('btn-primary');
if (buttons.length > 0) {
    buttons[1].click(); // Adjust the index as needed
}

Usage
Install the Shortkeys (Custom Keyboard Shortcuts) extension in your browser.
Assign custom keyboard shortcuts to execute the above scripts.
Use the shortcuts to interact with the web elements as described.
Notes
Ensure the id or class used in the scripts matches the target element on the webpage.
Modify the index in the class-based script (buttons[1]) to target the correct element in the list.
