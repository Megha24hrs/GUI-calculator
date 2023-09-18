Here's a brief breakdown of the code:

Import the Tkinter library to create the GUI application.

Initialize a variable calculation to store the user's input.

Define functions:

add_to_calculation(symbol): Appends the provided symbol or number to the calculation variable and updates the display.
evaluate_calculation(): Evaluates the calculation and displays the result. If there's an error during evaluation, it displays "Error."
clear_field(): Clears the calculation and the display.
Create the main application window using tk.Tk() and set its geometry.

Create a Text widget named text_result for displaying the calculation.

Create various buttons for numbers (0-9), basic arithmetic operations (+, -, *, /, %), square root (√), factorial (!), decimal point (.), clear (C), and equals (=). Each button is associated with a specific function through the command parameter.

Organize the buttons on a grid layout using grid() with specified row and column positions.

Start the Tkinter main event loop using root.mainloop() to display the GUI and allow user interactions.

