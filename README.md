📘 How to Run a Next.js Project from a ZIP File
Follow the steps below to unzip and run a Next.js project locally on your machine.

🔧 Prerequisites
Before you begin, ensure you have the following installed:
Node.js (v18 or higher recommended): Download Node.js


npm (comes with Node.js) or Yarn


A code editor like VS Code (optional but recommended)


📦 ZIP Files Overview

ZIP File
Short Landing Page UI
old-healthCompass-landingPage.zip

📦 1. Extract the ZIP File
Locate the ZIP file on your computer.


Right-click → Extract All or use a tool like unzip or 7-Zip.


Open the extracted folder.


📁 2. Open the Project in Terminal
Open a terminal/command prompt.


Navigate to the extracted folder:


bash
CopyEdit
cd path/to/extracted-folder


📥 3. Install Dependencies
Install all required packages using npm or yarn:
npm install
# or
yarn install


🚀 4. Run the Development Server
Start the Next.js development server:
npm run dev
# or
yarn dev

By default, your project should be running at:
http://localhost:3000 (or other port)


🧪 5. Optional Scripts
Other useful scripts you may find in package.json:
bash
CopyEdit
npm run build      # Build the app for production
npm run start      # Start the production server
npm run lint       # Lint the codebase


❗ Common Issues
Port already in use? → Try: PORT=4000 npm run dev


Missing modules? → Ensure you're in the correct directory and have run npm install.


✅ You're All Set!
Your Next.js app should now be running locally. Modify code and refresh the browser to see updates instantly.

Temporary deploy link : https://health-compass-landing-page-chi.vercel.app/  (read only)

