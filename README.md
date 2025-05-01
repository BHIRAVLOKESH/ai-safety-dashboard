AI Safety Dashboard

Overview
The AI Safety Dashboard is a web application built with React.js. It allows users to track and manage incidents related to AI safety. The project features a clean, responsive design using modern web development practices like React components and CSS Grid for layout management.

Table of Contents
1. Language/Framework Choice
2. Installation Instructions
3. Run Locally
4. Building for Production
5. Running Tests
6. Optional: Ejecting the Project
7. Design Decisions and Challenges

Language/Framework Choice
- Frontend: The project is built using React.js, a JavaScript library for building user interfaces, particularly for single-page applications (SPAs). React’s component-based architecture makes it a great fit for this project.
- Styling: CSS is used to handle the styling of the application. Modern CSS features like CSS Grid and Flexbox are used for layout and responsive design to ensure the dashboard adapts well to different screen sizes.

Installation Instructions

Prerequisites
Before starting, ensure that you have the following installed on your machine:
- Node.js (version 14.x or higher) – Download from https://nodejs.org/
- npm (Node Package Manager) – This comes bundled with Node.js.

Steps to Install Dependencies
1. Clone the Repository:
   If you have the project in a .zip file or directly from a GitHub repository, navigate to the project folder after extracting it. Alternatively, you can clone it using:
   git clone https://github.com/your-username/ai-safety-dashboard.git
   cd ai-safety-dashboard

2. Install Project Dependencies:
   In the root directory of the project, open a terminal or command prompt and run:
   npm install

   This will download and install all the required dependencies listed in package.json.

Run Locally
Once the dependencies are installed, follow these steps to run the application locally:

1. Start the Development Server:
   Run the following command to start the local development server:
   npm start

   This will open a development server at http://localhost:3000 where you can view the project in your browser.

Building for Production
If you need to create an optimized version of the project for deployment, you can build it for production:
npm run build

This command will generate a build folder containing optimized, minified files ready for deployment.

Running Tests
If there are unit tests available, you can run them with the following command:
npm test

Optional: Ejecting the Project
If you need to customize the underlying configuration (like Webpack or Babel), you can eject the project. Be aware that this action is irreversible:
npm run eject

Design Decisions and Challenges

Design Decisions:
- Responsive Layout: The application uses CSS Grid and Flexbox for creating a responsive design. The layout adjusts automatically to different screen sizes, making it mobile-friendly.
- Component-based Architecture: React components like IncidentCard, IncidentDashboard, and NewIncidentForm allow for modular and reusable code. This promotes maintainability and scalability.
- Color Palette: A warm and modern color palette was chosen for a clean, user-friendly interface. Colors are used effectively for various states like severity-high to highlight important incidents.

Challenges:
- TypeScript Integration: Ensuring that TypeScript types were correctly integrated into React components was a challenge. This was addressed by defining custom types and properly configuring TypeScript.
- CSS Styling: Ensuring that styles dynamically change (e.g., hover states, severity-based colors) while keeping the layout responsive was a challenge. Using CSS Grid and Flexbox helped achieve a flexible and user-friendly layout.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit pull requests. Make sure to follow the code style and write tests where applicable.

License
This project is licensed under the MIT License – see the LICENSE.md file for details.

Contact
For questions or suggestions, feel free to open an issue in the GitHub repository or contact the project maintainer.

Thank you for using the AI Safety Dashboard! 🚀



//the node_modules were deleted so before running the project install  npm install and run the project npm run dev
