# Language Translation Web Application

A web-based language translator application that translates text between different languages. It allows users to enter text, select source and target languages, and get the translation. It also provides options to read the text aloud using the Web Speech API.

Features
Translate text between various languages using the MyMemory API.
Swap languages functionality.
Text-to-speech support for both input and translated text.
User-friendly interface with a colorful theme.
Demo
You can view a live demo of the project here.

Screenshots

Getting Started
These instructions will help you set up the project on your local machine for development and testing purposes.

Prerequisites
Web browser (Google Chrome, Firefox, etc.)
Code editor (Visual Studio Code, Sublime Text, etc.)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/language-translator.git
Navigate to the project directory:
bash
Copy code
cd language-translator
Usage
Open index.html in your preferred web browser to view and use the application.
Files
index.html: The main HTML file containing the structure of the application.
style.css: The CSS file for styling the application.
main.js: The JavaScript file containing the functionality of the application.
country.js: A JavaScript file containing the list of supported languages.
screenshot.png: A screenshot of the application for display in the README.
Project Structure
plaintext
Copy code
language-translator/
│
├── index.html
├── style.css
├── main.js
├── country.js
└── screenshot.png
Customization
Adding More Languages
To add more languages, update the countries object in country.js with the desired language codes and names.

javascript
Copy code
const countries = {
    "am-ET": "Amharic",
    "ar-SA": "Arabic",
    // Add more languages here
};
Changing Default Languages
The default languages for translation can be changed by updating the defaultLanguages object in main.js.

javascript
Copy code
const defaultLanguages = {
    from: "en",
    to: "es"
};
Built With
HTML5
CSS3
JavaScript
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
MyMemory API for translation services.
Font Awesome for icons.

