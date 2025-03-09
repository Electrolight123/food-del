# food-del

## Overview
**food-del** is a food delivery web application that enables users to order food online seamlessly. The project consists of a backend powered by Node.js and MongoDB and a frontend built using modern web technologies. The admin panel allows for efficient management of orders and restaurant details.

## Installation & Setup

### Prerequisites
Before setting up the project, ensure you have the following installed:
- **Node.js** ([Download Here](https://nodejs.org/en/download/))
- **MongoDB** ([Create an Atlas Account](https://www.mongodb.com/cloud/atlas/register))

### Backend Setup
1. Open the project folder in **VS Code**.
2. Open the **Integrated Terminal**:
   - Right-click on the sidebar → Select **"Open In Integrated Terminal"**.
3. Run the following command to install dependencies:
   ```sh
   npm install
   ```
4. **Set Up MongoDB**:
   - Sign up on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register).
   - Create a new project.
   - Navigate to **Database Section** and build a database.
   - Select **M0**, choose a region, and create the database.
   - Set up **Username & Password** (Do not use ‘@’ in the password).
   - Whitelist IP `0.0.0.0/0`.
   - Click on **Connect** → **Compass Option**.
   - Copy the **Connection String**.
   - Paste the connection string in `db.js` and replace `<password>` with the password you created.

5. **Set Up Stripe Payment Gateway**:
   - Open the `.env` file in the backend folder.
   - Paste your **Stripe Secret Key** in the `STRIPE_SECRET_KEY` variable.

6. **Run the Backend**:
   ```sh
   npm run server
   ```

### Frontend & Admin Panel Setup
1. Open the project folder in **VS Code**.
2. Open the **Integrated Terminal** in the project directory.
3. Install dependencies:
   ```sh
   npm install
   ```
4. After installation, you should see a `node_modules` folder in the sidebar.
5. Run the frontend:
   ```sh
   npm run dev
   ```
6. The project will start in your default web browser.



