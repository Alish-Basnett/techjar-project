Responsive Dashboard with React
A responsive dashboard built with React and Ant Design, featuring animated UI components, loading animations, and a login page with validation and error handling. Designed for both desktop and mobile screens. Optional integration of Redux and TypeScript enhances state management and code quality.

Features
Clean and Visually Appealing Design: Ensures a professional and attractive interface.
Responsive Layout: Adapts to both desktop and mobile screens.
Animated UI Components: Enhances user experience with smooth animations.
Loading Animation: Indicates data fetching with a full-page loading animation.
Login Page: Includes email and password validation with error handling.
Mocked Login API: Validates user credentials with a mock API.
Redux (Optional): Manages global state efficiently.
TypeScript (Optional): Ensures type safety and improves code quality.
Getting Started
Prerequisites
Node.js
npm or yarn
Installation
Clone the repository:

git clone https://github.com/your-username/techjar-dashboard.git
cd responsive-dashboard
Install dependencies:

npm install
# or
yarn install
Running the Application Locally
Start the development server:

npm start
# or
yarn start
Open http://localhost:3000 to view it in the browser.

Building for Production
Build the application:

npm run build
# or
yarn build
The build artifacts will be stored in the build directory.

Folder Structure
bash
Copy code
/src
├── /components
├── /pages
├── /redux
├── /styles
├── App.tsx
├── index.tsx
└── ...

Mocked Login API
For the purpose of this project, a mocked login API is used to validate user credentials. The credentials are predefined, and the API returns appropriate responses for successful and failed login attempts.

Optional: Using Redux
If you choose to use Redux for state management, follow these steps:

Install Redux and React-Redux:

npm install @reduxjs/toolkit react-redux
# or
yarn add @reduxjs/toolkit react-redux
Set up Redux in your project by creating slices and configuring the store.

Optional: Using TypeScript
If you choose to use TypeScript for type safety, follow these steps:

Ensure TypeScript is installed:

npm install typescript @types/react @types/react-dom @types/react-redux
# or
yarn add typescript @types/react @types/react-dom @types/react-redux
Use TypeScript by creating .ts and .tsx files and defining types for state, actions, and components.
