# YOLOv8 DNF Game Automation Documentation

## Project Overview
This project implements a game automation system using YOLOv8 for game detection and automation in the DNF (Dungeon & Fighter) game. It leverages deep learning techniques to automate tasks and improves the gaming experience.

## Module Descriptions

### 1. Detection Module
This module is responsible for detecting game objects in real-time using YOLOv8. It processes the game screen and identifies various elements needed for automation.

### 2. Action Module
This module controls the interaction with the game. It translates detected objects from the Detection Module into game actions such as clicking, moving, or executing specific game commands.

### 3. User Interface Module
This interface provides users with a way to configure settings, view detected items, and monitor the game automation process. It is user-friendly and allows easy customization.

### 4. Logging Module
Tracks and logs the actions taken by the automation system. This is essential for debugging and understanding the game's responses to the automated actions.

### 5. Configuration Module
Responsible for loading and saving user settings, such as which objects to detect, action mappings, and other preferences that affect the automation process.

## Dependencies
- Python 3.8+
- YOLOv8 (latest version)
- OpenCV
- NumPy
- PyAutoGUI

## Usage Instructions
1. Clone the repository: `git clone https://github.com/ly198912/yolov8_2.git`
2. Navigate into the project directory: `cd yolov8_2`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the application: `python main.py`

## System Requirements
- OS: Windows 10 or higher, Linux distributions supported
- RAM: Minimum 8 GB (16 GB recommended)
- Processor: Intel i5 or AMD Ryzen 5 (or equivalent)
- GPU: NVIDIA with CUDA support recommended for optimal performance.

## License
This project is licensed under the MIT License.