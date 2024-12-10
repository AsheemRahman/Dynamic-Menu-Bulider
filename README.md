# Dynamic Menu Builder

This repository contains the source code for a full-stack application designed to dynamically create and manage menus and menu items. Built with a modern tech stack, it allows users to manage menus such as "Drinks" and "Snacks" with ease.

## Features
- Create menus with titles and descriptions.
- Add multiple items to menus, including item name, description, and price.
- Dynamically adjust the UI and functionality as menus and items are added.
- Clean and responsive user interface.

## Tech Stack

### Frontend
- **React.js**
- 
### Backend
- **Express.js OR Node.js**

### DATABASE
- **MongoDB**



## Prerequisites
- Node.js >= 14.x
- npm or yarn
- MongoDB  database

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AsheemRahman/Dynamic-Menu-Bulider.git
    cd Dynamic-Menu-Bulider
    ```

2. Install dependencies:
    - install dependencies in BACKEND and FRONTEND Folder
    ```bash
    npm install
    ```

3. Configure environment variables:
    - Create a `.env` file in the Backend Folder.
    - Add database connection details:
      ```env
      MONGODB_URI = your_database_connection_string
      PORT = 5000
      ```

4. Start the development server:
    ```bash
    cd BACKEND
    npm start
    ```

5. Start the Frontend development
    ```bash
    cd FRONTEND
    npm run dev
    ```

## Folder Structure
```
├── backend
│   
│   ├── controllers
│       ├── controller.js
│   ├── routes
│       ├── route.js
│   ├── models
│       ├── menu.js
│   ├── indes.js
│   
├── frontend
│   ├── components
│       ├── Header.jsx
│       ├── Footer.jsx  
│       ├── Menu.jsx
│       ├── MenuList.jsx
│       ├── CreateMenu.jsx
│       ├── CreateMenuItem.jsx
└── README.md
```

## Usage
1. Access the UI to create menus and items.
2. Click on a menu to view its associated items.
3. Manage the application dynamically as more menus and items are added.

## Scripts
### Backend
- `npm start`: Start the production server.

### Frontend
- `npm run dev`: Start the frontend development server.

Happy coding! 🚀
