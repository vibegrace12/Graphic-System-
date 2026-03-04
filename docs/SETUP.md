# Setup and Installation Instructions for the Graphic System Dashboard Project

## Prerequisites
- Ensure you have Node.js (v14 or above) installed on your machine.
- Install MongoDB and ensure the service is running.

## Installation Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/<owner>/Graphic-System-.git
   ```  

2. **Change to the project directory**
   ```bash
   cd Graphic-System-
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Set up environment variables**
   - Create a `.env` file in the root directory and populate it with your configuration settings:
     - `MONGODB_URI=<your_mongodb_uri>`
     - `PORT=3000`  

5. **Run the application**
   ```bash
   npm start
   ```

## Accessing the Dashboard
- Open your browser and navigate to `http://localhost:3000` to access the dashboard.

## Troubleshooting
- If you encounter issues, check the console for error messages. Ensure all services are running and configurations are correct.