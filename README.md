Security Camera with Motion Detection
This project is a simple security camera system built using Python. The system utilizes a webcam to capture footage and detects motion by comparing differences between consecutive frames. When motion is detected, an alarm sounds using the winsound library. The project leverages the powerful opencv library for video processing and motion detection.

Features
Real-time Motion Detection: Continuously captures video and compares consecutive frames to detect any motion.
Alarm System: Sounds an alarm using the winsound library when motion is detected.
Easy Setup: Simple and straightforward setup using a webcam and Python libraries.
Requirements
Python 3.x
OpenCV (opencv-python)
Winsound (standard library on Windows)
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/security-camera-motion-detection.git
Navigate to the project directory:
bash
Copy code
cd security-camera-motion-detection
Install the required dependencies:
bash
Copy code
pip install opencv-python
Usage
Run the script to start the security camera system:

bash
Copy code
python security_camera.py
How It Works
The webcam captures video footage.
Each frame is converted to grayscale and blurred to reduce noise.
The system compares the current frame with the previous frame to detect any differences.
If significant differences are found (indicating motion), the alarm sounds using the winsound library.
Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License.

