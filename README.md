# Crop-prediction-system

# Crop Prediction System

## Overview
The Crop Prediction System is a web application designed to predict suitable crops for cultivation based on input parameters such as soil type, temperature, and rainfall. The system uses machine learning models and a MongoDB database to store and manage data.

## Project Structure
```
📁 crop-prediction-system
│── server.js               
│── package-lock.json                
│── 📂 routes [prediction.js]
│── 📂 data [Crop_recommendation.csv]
│── 📂 agri [React app]            
│── 📄 package.json          
│── 📄 .env                   
```

## Dependencies
The project utilizes the following major dependencies from `package.json`:
- **express:** Web framework for Node.js
- **mongoose:** MongoDB object modeling tool
- **mongodb:** Driver for interacting with MongoDB
- **multer:** Middleware for handling multipart/form-data (file uploads)
- **cors:** Middleware to enable Cross-Origin Resource Sharing
- **dotenv:** Module to manage environment variables
- **csv-parser:** To parse CSV files
- **xlsx:** To handle Excel files

## Installation and Setup
### Prerequisites
- Node.js (v16 or above)
- MongoDB (local or cloud-based)
- React

### Steps to Run the Project
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-username/crop-prediction-system.git
   cd crop-prediction-system
   ```
2. **Install Dependencies:**  
   ```bash
   npm install
   ```
3. **Configure Environment Variables:**  
   Create a `.env` file and add your environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```
4. **Run the Server:**  
   ```bash
   npm start
   ```
5. **API Endpoint Access:** The server will start on `http://localhost:5000`

## Usage
- **Upload CSV/Excel Files:** Use the file upload endpoint to input crop data.
- **Get Predictions:** Use the prediction endpoint to receive suitable crop suggestions based on input parameters.
- **Manage Database:** View and update crop data stored in MongoDB.

## Contribution
Contributions are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the ISC License.

