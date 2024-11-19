# webpage-structure-with-several-buttons

#Explanation
HTML Structure:

Three buttons with unique ids (button1, button2, button3).
Each button is associated with a div for displaying a message (message1, message2, message3).
CSS:

Styled buttons with a blue color and rounded edges.
Messages are initially hidden (display: none) and appear on mouseover.
JavaScript Functions:

changeColor(event): Changes the button's background color to light blue when clicked.
showMessage(event): Displays the associated message when the mouse is over the button.
hideMessage(event): Hides the message when the mouse moves away.
hideButton(event): Hides the button when double-clicked.
Event Listeners:

Event listeners are added to each button for click, mouseover, mouseout, and dblclick events.
These listeners trigger the respective actions dynamically.
Workflow
Click a Button:

The button's color changes to light blue.
Hover Over a Button:

A message (e.g., "Mouse over Button 1") appears below the button.
Move the Mouse Out:

The message disappears.
Double-Click a Button:

The button disappears from the page.
