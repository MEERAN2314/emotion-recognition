# Emotion Recognition Project

This project is designed to recognize emotions using a combination of frontend and backend technologies. The frontend is built with React, and the backend uses Flask.

## Getting Started

### Prerequisites
- Node.js and npm installed for frontend development
- Python 3 and pip installed for backend development
- A virtual environment recommended for Python dependencies

### Installation

1. Clone the repository:
   ```
   git clone git@github.com:MEERAN2314/emotion-recognition.git
   cd emotion-recognition
   ```

2. Install frontend dependencies:
   ```
   cd frontend
   npm install
   cd ..
   ```

3. Install backend dependencies:
   ```
   cd backend
   pip install -r requirements.txt
   ```

### Running the Application

1. Start the frontend development server:
   ```
   cd frontend
   npm start
   ```
   This will open the application in your default browser at http://localhost:3000.

2. Start the backend server:
   ```
   cd ../backend
   python app.py
   ```
   The backend will run on http://localhost:5000.

## Usage

The application allows users to upload images or videos, and the system will analyze and recognize emotions. The frontend provides a user-friendly interface to interact with the backend API.

## Contributing

Contributions are welcome! Please read the CONTRIBUTING.md file for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
