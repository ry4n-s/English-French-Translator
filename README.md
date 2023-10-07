# English-French-Translator
Translates between English and French using the IBM Watson translator. Uses Python (Flask), JavaScript, HTML.

This project showcases a web-based language translation application designed to convert text between English and French. The application leverages IBM Watson's Language Translator API for real-time translations. The backend is crafted in Python, while the frontend is developed with HTML, CSS (using Bootstrap), and JavaScript. The application also provides a testing suite to ensure the accuracy and functionality of the translation service.

Key Features and Implementation Details:

Backend Setup with IBM Watson:

Utilizes the IBM Watson Language Translator V3 API for translation capabilities.
Uses an IAMAuthenticator for secure API authentication.
API key and service URL are securely fetched from environment variables, ensuring that sensitive data is kept hidden.
Translation Functions:

Two core functions are implemented:

englishToFrench: Translates English text to French.
frenchToEnglish: Translates French text to English.

Testing Suite:

The application incorporates a unittest-based testing suite ensuring that:

English-to-French and French-to-English translations work correctly.
Spaces are accurately handled.

Web Application with Flask:

Flask is employed to serve the web application and handle HTTP requests.

Three routes are defined:

/: Renders the main translation interface. 

/englishToFrench: Handles the translation request from English to French.

/frenchToEnglish: Manages the translation request from French to English.

Frontend Implementation:

The interface is designed with Bootstrap for a modern and responsive look.
Users can input text to be translated through a form and choose between translating to French or English.
The translated result is dynamically displayed below the form.

AJAX Calls for Seamless User Experience:

The frontend uses JavaScript to initiate asynchronous AJAX requests to the backend translation routes, ensuring a seamless and interactive translation experience.
translateToFrench and translateToEnglish functions in JavaScript fetch the translation from the backend and display it on the web page without requiring a page refresh.
This project highlights a combination of modern web technologies, third-party API integration, and efficient coding practices to deliver an interactive and user-friendly language translation platform.

![showcase](https://github.com/ry4n-s/English-French-Translator/assets/132171741/775f8df3-0828-4e74-b076-6ecae86dad74)
