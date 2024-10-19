# ValidMail

**ValidMail** is a web application designed to validate email addresses for businesses. It uses the [Email Validation API](https://emailvalidation.io) to ensure email addresses entered by users are properly formatted and deliverable.

## Features

- **Real-time validation:** Validate emails instantly through the app.
- **Email breakdown:** Displays detailed information like domain, deliverability, and format.
- **Simple UI:** Easy-to-use interface for users to input emails and see results.
- **Responsive design:** Works seamlessly across desktop and mobile devices.

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Node.js and npm installed
- API key from [Email Validation](https://emailvalidation.io)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/validmail.git
   
2. Install dependencies:

    ```bash
    npm install

3. Create a .env file in the project root and add your API key:

    ```makefile
    API_KEY=your_api_key_here

4. Run the application:

    ```bash
    npm start

5. Open your browser and go to http://localhost:3000 to view the app.

### Project Structure
  
  ```graphql
  
  ValidMail/
  │
  ├── css/
  │   └── style.css          # Main CSS for styling
  ├── img/
  │   └── email.svg          # Image assets used in the UI
  ├── js/
  │   └── index.js           # JavaScript for form submission and API integration
  ├── index.html             # Main HTML file
  ├── package.json           # Node.js dependencies
  └── README.md              # Project documentation
```

## Usage
  1. Input your email address in the form.
  2. Submit the form to validate the email.
  3. The app will return information about the email, such as deliverability status, domain, and more.

## API
  ValidMail uses the Email Validation API for checking the email. Make sure to replace the API key in the JavaScript file with your own API key.
