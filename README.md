# App Switcher

App Switcher is an Electron-based application that allows users to quickly switch between open windows and view system information.

## Features

- Quick app switching: Easily search and switch between open applications
- System information display: View real-time CPU and RAM usage
- Global shortcut: Activate the app switcher from anywhere using a keyboard shortcut
- Cross-platform: Works on Windows, macOS, and Linux

   ![image](https://github.com/user-attachments/assets/3bab8a86-c8ac-4841-99ec-b364a8f64006)
## Setup Guide

1. Clone the repository:
   ```
   git clone https://github.com/Bentlybro/Windows-App-Switcher.git
   cd Windows-App-Switcher
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the application:
   ```
   npm start
   ```

4. To use the app checkout [usage](https://github.com/Bentlybro/Windows-App-Switcher/tree/main?tab=readme-ov-file#usage)

## Building the Application

To build the application for your platform, use one of the following commands:

- For all platforms:
  ```
  npm run build
  ```

- For Windows:
  ```
  npm run build:win
  ```

- For macOS:
  ```
  npm run build:mac
  ```

- For Linux:
  ```
  npm run build:linux
  ```

## Usage

1. Launch the application.
2. Use the global shortcut `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the App Switcher window.
3. Type in the search bar to filter open applications.
4. Click on an application in the list to switch to it.
5. The App Switcher window will automatically hide when you switch to an application or click outside the window.

## Current Capabilities

- Display a list of open windows, excluding system windows
- Search and filter open windows by title
- Switch to a selected window, bringing it to the foreground
- Show real-time CPU and RAM usage information
- Automatically update the window list when the App Switcher is opened
- Global shortcut to quickly access the App Switcher from any application

## Technologies Used

- Electron
- Node.js
- HTML/CSS (with Tailwind CSS for styling)
- JavaScript

## Dependencies

- active-win: For getting information about open windows
- node-window-manager: For managing window focus and bringing windows to the foreground
- systeminformation: For retrieving system information (CPU and RAM usage)
