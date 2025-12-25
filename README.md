# Temperature-Converter
Temperature converter 

This project is a simple temperature converter built with HTML, CSS, and JavaScript. 

The HTML file creates a form where the user can type a number into a textbox, select one of two radio buttons to choose the conversion direction, and then click a submit button to run the calculation. 

The CSS file styles the form by centering it on the page, adding background color, rounded borders, and bold readable text for labels and results. The JavaScript file contains the logic for the conversion. 

It first connects to the HTML elements using document.getElementById, then defines a convert() function. Inside this function, the code checks which radio button is selected using the .checked property.

 If the “Celsius ➡️ Fahrenheit” option is chosen, the input value is converted using the formula F=C\times \frac{9}{5}+32, and the result is displayed with the degree symbol and “F.” If the “Fahrenheit ➡️ Celsius” option is chosen, the formula C=(F-32)\times \frac{5}{9} is applied, and the result is shown with “°C.” If neither option is selected, the program displays a message prompting the user to choose one.
 
  This combination of HTML for structure, CSS for design, and JavaScript for functionality makes the converter interactive and easy to use.

