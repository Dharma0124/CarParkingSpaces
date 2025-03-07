# Car Parking Space Detection

## Overview
This project uses image processing techniques to detect available parking spaces in a parking lot. It processes video and image data to analyze and identify open parking spots.

## Features
- Detects available parking spaces in a given image or video.
- Allows manual selection of parking regions using `ParkingSpacePicker.py`.
- Processes video frames in real-time for continuous monitoring.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CarParkingSpaces.git
   cd CarParkingSpaces
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(Ensure Python 3.x is installed.)*

## Usage
### 1. Selecting Parking Spaces
Before running detection, define parking spaces using `ParkingSpacePicker.py`:
   ```bash
   python ParkingSpacePicker.py
   ```
This script allows you to select and save parking spots manually.

### 2. Running the Main Detection Script
   ```bash
   python main.py
   ```
This processes the provided `carPark.mp4` and highlights available spots.

## Project Structure
```
CarParkingSpaces/
│-- main.py  # Main script for parking detection
│-- ParkingSpacePicker.py  # Tool to select parking spaces
│-- carPark.mp4  # Sample video file
│-- carParkImg.png  # Sample image for processing
│-- CarParkpos  # Stored parking space positions
│-- requirements.txt  # List of dependencies (to be added)
│-- README.md  # Documentation
```

## Future Enhancements
- Improve detection accuracy with ML-based models.
- Add a web interface for real-time monitoring.
- Integrate with cloud storage for remote access.

## License
This project is open-source under the MIT License.

