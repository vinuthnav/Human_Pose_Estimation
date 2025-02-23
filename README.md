# Human Posture Estimation using MediaPipe and OpenCV

This project uses **MediaPipe's Pose solution** and **OpenCV** to estimate human posture in real-time via webcam input. The solution provides keypoint detection for **33 body landmarks**, making it suitable for applications like **fitness tracking**, **ergonomic monitoring**, and **gesture recognition**.

---

## Features
- **Real-time human posture detection** using webcam input.
- **Identification and visualization of 33 body landmarks**.
- Highly customizable **detection and tracking confidence thresholds**.
- **Lightweight and efficient solution** leveraging MediaPipe.

---

## Technologies Used
- **Python**: Primary programming language for the project.
- **MediaPipe**: For pose estimation and landmark detection.
- **OpenCV**: For video capture and image processing.

---

## Installation

### 1. Clone the Repository
git clone https://github.com/vinuthnav/Human_Pose_Estimation.git
cd human-posture-estimation
2. Set Up a Python Environment
  
3. Install Dependencies
bash
Copy
pip install -r requirements.txt
4. Verify Installation
Ensure Python 3.7+ is installed:

python --version
Ensure OpenCV and MediaPipe are installed:

python -c "import cv2, mediapipe; print('Setup complete!')"
Usage
Run the Posture Estimation Script

python posture_estimation.py
Instructions
Ensure your webcam is connected and functioning properly.
A window displaying the webcam feed with pose landmarks will open.
Press 'q' to exit the application.
File Structure
human-posture-estimation/
│
├── HUMAN_Estimation_Live(1).ipynb  
├── Video_estimation.ipynb           
├── requirements.txt                 
├── Video.mp4                       
├── Pos_image.png                    
├── README.md                       
Requirements
Python 3.7 or higher
OpenCV
MediaPipe
A functional webcam or external camera
To install dependencies:
pip install -r requirements.txt
Customization
You can adjust the following parameters in the code to fine-tune the performance:

min_detection_confidence: Confidence for detecting a person.
min_tracking_confidence: Confidence for tracking landmarks.
Frame size: Resize for faster processing.
Output
The real-time feed displays:

Detected body landmarks.
Pose connections drawn using MediaPipe Drawing Utilities.
Applications
Fitness Tracking: Analyze posture during workouts.
Ergonomic Monitoring: Maintain proper posture while working.
Gesture Recognition: Detect body poses for interactive applications.
Sports Analytics: Enhance sports performance with pose estimation.
Known Issues
Requires sufficient lighting for accurate detection.
Low tracking accuracy for extremely fast movements.
May not perform efficiently on older hardware.
Future Enhancements
Integrate a GUI for user interaction.
Save detected poses for post-processing and analysis.
Incorporate custom actions or pose alerts.
