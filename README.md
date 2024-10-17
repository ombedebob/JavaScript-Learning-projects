Project Overview

This project is a simple web-based QR Code Generator that allows users to create QR codes by entering text or a URL. The project dynamically generates the QR code using an external API and displays it on the screen. It also provides user feedback through animations when input is missing or incorrect.

Features

Generate QR Codes: Users can input a text string or URL, and a corresponding QR code will be generated.

Responsive Design: The web page adjusts to different screen sizes using CSS styling.

Error Handling: If the input field is empty when the "Generate QR" button is pressed, the input box will shake to indicate an error.

Smooth Transitions: The QR code image box expands smoothly when the code is generated.


Technologies Used

HTML: Defines the structure of the webpage.

CSS: Adds styling to the page, including layout, color schemes, and animations.

JavaScript: Adds functionality, such as generating the QR code and handling user interactions.

External API: The project uses the https://api.qrserver.com API to generate QR codes based on user input.


How It Works

1. The user enters text or a URL in the input field.


2. When the "Generate QR" button is clicked, the JavaScript function generateQr() is triggered.


3. If the input field contains text, a QR code is generated using the external API, and it is displayed in an expanding box.


4. If the input field is empty, the input box shakes for 1 second to indicate an error.



Files

index.html

This file contains the structure of the web page, including an input field, a button, and a container for the generated QR code image.

style.css

This file handles the styling of the page:

Centers the container on the screen.

Adds custom styling for the input field, button, and QR image container.

Includes an animation for shaking the input box in case of an error.


main.js

This file contains the main JavaScript logic:

Captures user input.

Calls the QR Code API to generate the QR image.

Handles adding and removing error animations when necessary.


How to Run

1. Clone or download the repository.


2. Open index.html in any modern browser.


3. Enter a URL or text into the input field and click the "Generate QR" button to see the generated QR code.



Future Improvements

Error Messages: Display more descriptive error messages when the input is invalid.

Custom QR Options: Allow users to customize the size or color of the QR code.

History Feature: Store and display previously generated QR codes for quick access.


External API Used

QR Code Generator API for generating QR codes.


License

This project is open-source and available under the MIT License
