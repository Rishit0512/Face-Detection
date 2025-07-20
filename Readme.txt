# Facemesh React App

This project is a React application that uses TensorFlow.js and the facemesh model to detect and visualize facial landmarks in real time using your webcam.

## Features

- Real-time face detection using your webcam
- Draws a facial mesh overlay with triangulation and keypoints
- Built with React and TensorFlow.js

## Getting Started

### Prerequisites

- Node.js (v14 or newer recommended)
- npm

### Installation

1. Clone this repository.
2. Navigate to the `facemesh` directory:


### Running the App

Start the development server:

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

## Project Structure

- `src/App.js`: Main React component, handles webcam and facemesh logic.
- `src/utilities.js`: Contains mesh triangulation data and drawing utilities.
- `src/App.css`: Styling for the app.
- `public/`: Static assets and HTML template.

## Usage

- Allow webcam access when prompted.
- The app will display your webcam feed with a facial mesh overlay.

## License

This project is for educational and demonstration purposes.