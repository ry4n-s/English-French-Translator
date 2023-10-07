# English-French Translator :gb: :fr:

Translate between English and French seamlessly with our web-based application, leveraging the power of IBM Watson's Language Translator API. The system is built using Python (Flask) for the backend, combined with a frontend crafted in HTML, CSS (Bootstrap), and JavaScript.

## 🚀 **Overview**

This project demonstrates the capabilities of integrating modern web technologies, third-party APIs, and efficient coding practices to offer a dynamic and user-friendly language translation platform.

## 🛠 **Key Features and Implementation**

### Backend with IBM Watson

- **API Integration**: Uses the IBM Watson Language Translator V3 API.
- **Authentication**: IAMAuthenticator ensures a secure connection.
- **Security**: API key and service URL are fetched from environment variables for data protection.

### Core Translation Functions

- `englishToFrench`: Converts English text to French.
- `frenchToEnglish`: Converts French text to English.

### Web Application Framework

- **Framework**: Flask.
- **Routes**:
  - `/`: Main translation interface.
  - `/englishToFrench`: Endpoint for English to French translation.
  - `/frenchToEnglish`: Endpoint for French to English translation.

### Frontend Design

- **Styling**: Modern and responsive UI using Bootstrap.
- **User Interface**: A form to input text with options to select translation direction.

### AJAX for Dynamic Interaction

- **Asynchronous Interaction**: Utilizes JavaScript to send AJAX requests.
- **Seamless Experience**: `translateToFrench` and `translateToEnglish` functions fetch translations without a page refresh.

### Testing

- **Framework**: Uses unittest.
- **Checks**:
  - Validates English-to-French and French-to-English translations.
  - Ensures accurate handling of spaces.

![showcase](https://github.com/ry4n-s/English-French-Translator/assets/132171741/775f8df3-0828-4e74-b076-6ecae86dad74)
