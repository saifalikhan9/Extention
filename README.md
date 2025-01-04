# Chrome Extension Installation Guide

Follow the steps below to install the Chrome extension built using TypeScript and React with Vite:

## Prerequisites
Ensure you have the following installed on your system:
- Node.js (version 14 or higher)
- npm (Node Package Manager)

## Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/saifalikhan9/Extention
   ```
   Replace `https://github.com/saifalikhan9/Extention` with the URL of your repository.

2. **Navigate to the Root Folder**
   ```bash
   cd <repository-folder>
   ```
   Replace `<repository-folder>` with the name of the cloned repository folder.

3. **Install Dependencies**
   Run the following command to install all required dependencies:
   ```bash
   npm install
   ```

4. **Build the Extension**
   Use the following command to build the project:
   ```bash
   npm run dev
   ```
   This will generate a folder named `dist` in the root directory.

5. **Load the Extension in Chrome**
   - Open Google Chrome and navigate to `chrome://extensions/`.
   - Enable "Developer mode" (toggle is located at the top-right corner).
   - Click on the "Load unpacked" button.
   - Select the `dist` folder generated in the previous step.

6. **Verify Installation**
   The extension should now be visible in your Chrome extensions list. If applicable, pin it to the toolbar for easy access.

## Notes
- Ensure you rebuild the project (`npm run dev`) after making any changes to the source code.
- For troubleshooting or further development instructions, refer to the project's documentation or contact the developer.

Enjoy using your Chrome extension!

