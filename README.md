# 19 Progressive Web Applications (PWA): Text Editor

## **About the Project**

### **Overview**
This project is a browser-based text editor that operates as a single-page application (SPA) and meets the criteria for a Progressive Web Application (PWA). The application is designed to function both online and offline, ensuring data persistence through various techniques. It uses the `idb` package, a lightweight wrapper for the IndexedDB API, to store and retrieve data, ensuring redundancy and reliability even if some storage options are unsupported by the browser.

The project begins with an existing application, where additional methods for data handling and storage are implemented. The final product is deployed on Render, making it easily accessible.

Find the repository [here](https://github.com/AlejnadroVill/19-Challenge).

## **Table of Contents**
- [Get Started](#get-started)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)

## **Get Started**

To get started with this project, follow these steps:

1. **Clone the Repository:**
   ```
   git clone https://github.com/AlejnadroVill/19-Challenge.git
2. Navigate to the Project Directory:
cd 19-Challenge
3. Install Dependencies:
npm install
4. Run the Application:
npm start

This will start both the backend and frontend of the application. You can then interact with the text editor directly in your browser.

## **Usage**

Once the application is running, you can:

- **Write and Save Content:** The text editor allows you to create notes or code snippets that are automatically saved in the browser's IndexedDB whenever you click off the DOM window.
- **Offline Functionality:** The application works offline, allowing you to create and save content without an internet connection. The next time you connect, your content will be synced.
- **Installation:** You can install the application as a Progressive Web Application, adding it as an icon on your desktop for easy access.

## **License**

![GitHub](https://img.shields.io/github/license/AlejnadroVill/19-Challenge?style=for-the-badge)

See the [LICENSE](https://github.com/AlejnadroVill/19-Challenge/blob/main/LICENSE) for more details.

## **Credits**

This project was developed by [AlejnadroVill](https://github.com/AlejnadroVill) as part of the PWA challenge.
