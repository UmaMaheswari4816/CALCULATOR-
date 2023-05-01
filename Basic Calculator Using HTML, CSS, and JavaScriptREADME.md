# CALCULATOR-
Simple calculator using HTML and JS
This project is a basic calculator built using HTML, CSS, and JavaScript. 
The calculator has a simple user interface with buttons for numbers, operators, and functions such as clear and equals. 
The HTML code creates the structure of the calculator, while the CSS code styles it to look visually appealing. 
The JavaScript code is responsible for the calculator's functionality. It uses the DOM to select elements and perform calculations based on user input.
When a user clicks a button, the corresponding value is appended to the input field. 
When the user clicks the equals button, the calculator evaluates the input field and displays the result. 
The clear button clears the input field. Overall, this project is a great way to learn about basic web development concepts such as HTML, CSS, and JavaScript.

he JavaScript concepts used in the code are:

Functions: The code defines three JavaScript functions: show(), calc(), and ac(). These functions perform different actions on the calculator when the user interacts with it. For example, show() adds the clicked number/operator to the input field, calc() evaluates the expression in the input field and displays the result, and ac() clears the input field.

Document Object Model (DOM): The code uses the DOM to manipulate the HTML elements on the page. For example, document.getElementById('res') is used to get the input field element and document.getElementById('res').value is used to get or set its value.

Event Listeners: The code uses event listeners to detect when the user interacts with the calculator. For example, onclick event listeners are added to the number and operator buttons to call the show() function when they are clicked.

Conditional Statements: The code uses conditional statements (if statements) to check if certain conditions are met before executing a block of code. For example, the calc() function checks if the input field is not empty before evaluating the expression.

Arithmetic Operators: The code uses arithmetic operators (+, -, *, /, %) to perform mathematical operations on the input field. For example, + is used to add two numbers and / is used to divide a number by another number.

eval() Function: The code uses the eval() function to evaluate the mathematical expression in the input field and display the result. The eval() function takes a string argument and evaluates it as a JavaScript expression. However, using eval() with untrusted user input can be dangerous and lead to security vulnerabilities.


HTML concepts used in the code:

<!DOCTYPE html>: This is the document type declaration, which tells the web browser what type of document to expect. In this case, it is an HTML document.
<html>: This is the root element of an HTML document.
<head>: This element contains the metadata for the web page, such as the title, meta tags, and scripts.
<meta>: This element contains metadata, such as the character set, viewport settings, and keywords for search engines.
<title>: This element sets the title of the web page, which appears in the browser tab.
<style>: This element is used to define CSS styles for the HTML document.
<body>: This element contains the visible content of the web page.
<div>: This element is used to group and style HTML elements.
<table>: This element is used to create a table on the web page.
<tr>: This element defines a table row.
<td>: This element defines a table cell.
<button>: This element creates a clickable button.


CSS concepts used in the code:

background-color: This property sets the background color of an element.
padding: This property sets the padding of an element.
text-align: This property sets the horizontal alignment of text within an element.
font-size: This property sets the size of the font.
border: This property sets the border of an element.
cellspacing: This property sets the space between table cells.
cellpadding: This property sets the space between the border and content of a table cell.
bgcolor: This property sets the background color of an HTML element.
color: This property sets the color of the text.
