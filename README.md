# Rajasthan Police Internship Project 


![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
[![Localhost Badge](https://img.shields.io/badge/Localhost-running-green?style=for-the-badge&logo=localhost)](http://localhost)
[![ngx-toastr Badge](https://img.shields.io/badge/ngx--toastr-latest-orange?style=for-the-badge&logo=angular)](https://www.npmjs.com/package/ngx-toastr)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
[![Lordicon Badge](https://img.shields.io/badge/Lordicon-latest-purple?style=for-the-badge&logo=lordicon)](https://lordicon.com/)
[![favicon Badge](https://img.shields.io/badge/favicon-latest-blue?style=for-the-badge&logo=favicon)](https://favicon.io/)
[![HTTP Badge](https://img.shields.io/badge/HTTP-latest-green?style=for-the-badge&logo=http)](https://developer.mozilla.org/en-US/docs/Web/HTTP)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)


## Project Overview

The **Rajasthan Police Internship Project** is a web application developed to assist with various administrative tasks for the Rajasthan Police. The project utilizes a modern tech stack to create an efficient and user-friendly interface for handling data and operations.

## Technologies Used

- **Frontend:**
  - [Angular](https://angular.io/) for building the dynamic user interface.
  - [HTML5](https://www.w3.org/html/) for the structure of web pages.
  - [CSS](https://www.w3.org/Style/CSS/Overview.en.html) for styling web pages.
  - [TypeScript](https://www.typescriptlang.org/) for adding static typing to JavaScript.
  - [Bootstrap](https://getbootstrap.com/docs/5.0/) for responsive UI components.
  - [ngx-toastr](https://www.npmjs.com/package/ngx-toastr) for displaying notifications.

- **Backend:**
  - [Node.js](https://nodejs.org/) for server-side scripting.
  - [JSON Server](https://www.npmjs.com/package/json-server) for creating a REST API.

- **Other Tools and Libraries:**
  - [Git](https://git-scm.com/) for version control.
  - [Lordicon](https://lordicon.com/) for animated icons.
  - [favicon](https://favicon.io/) for browser tab icon.
  - [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) for communication protocol.

## Project Structure
```
Here's a detailed breakdown of the project structure:
Rajasthan-Police-Intern-Project/
│
├── README.md               # Project documentation
├── package.json            # Project dependencies and scripts
├── angular.json            # Angular CLI configuration
├── tsconfig.json           # TypeScript configuration
│
├── src/
│   ├── app/
│   │   ├── components/     # Reusable components (header, footer, forms, etc.)
│   │   ├── services/       # Business logic and data handling services
│   │   ├── models/         # TypeScript interfaces and models
│   │   ├── modules/        # Custom Angular modules
│   │   ├── ...             # Additional application files
│   │
│   ├── assets/             # Static assets (images, icons, fonts)
│   ├── environments/       # Environment configurations (dev, prod)
│   ├── index.html          # Main HTML file
│   ├── main.ts             # Main entry point for Angular
│   ├── styles.css          # Global styles
│   ├── ...                 # Additional source files
│
├── .gitignore              # Files and directories to ignore in Git
├── karma.conf.js           # Karma test runner configuration
├── protractor.conf.js      # Protractor end-to-end test configuration
└── ...

```


## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.io/cli)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/rishab1wnl/Raj-Police-Intern-Project.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Raj-Police-Intern-Project
    ```
3. **Install the dependencies:**
    ```bash
    npm install
    ```

### Running the Application

1. **Start the Angular development server:**
    ```bash
    ng serve
    ```
    The application will be accessible at [http://localhost:4200/](http://localhost:4200/).

2. **Start the JSON server for API:**
    ```bash
    npm run json-server
    ```
    The API will be accessible at [http://localhost:3000/](http://localhost:3000/).

### Useful Commands

- **Build the project:**
    ```bash
    ng build
    ```
- **Run unit tests:**
    ```bash
    ng test
    ```
- **Run end-to-end tests:**
    ```bash
    ng e2e
    ```

## API Endpoints

- **User Login:** `http://localhost:3000/login`
- **User Signup:** `http://localhost:3000/sign-up`
- **Expense Data:** `http://localhost:3000/expensedata`


> *This project was developed with ❤️ and ☕.*
