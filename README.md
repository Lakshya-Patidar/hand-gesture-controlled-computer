AI Hand Gesture Control System for PC 🖐️💻

An advanced, real-time computer vision project that allows users to control their Windows PC completely touchless using hand gestures. Powered by Python, OpenCV, and MediaPipe, this system enables smooth interaction through hand movements and finger tracking.

🚀 Key Features

Left Hand Control (Media & Display):

Volume Control: Adjust the system volume using the distance between the Thumb and Index finger.

Brightness Control: Regulate screen brightness using the distance between the Thumb and Middle finger.

Right Hand Control (Mouse & Navigation):

Cursor Movement: Move the mouse cursor smoothly across the screen by tracking the Index finger.

Mouse Click: Perform a left-click by bringing the Thumb and Index finger close together (pinch gesture).

Performance & Optimization:

Uses downscaled camera resolution (640x480) and frame-throttling to prevent system lag and freezing.

Clean resource management with safe exit handling ('q' key).

🛠️ Tech Stack & Dependencies

Language: Python (v3.11+)

Environment: Jupyter Notebook / Visual Studio Code

Core Libraries:

opencv-python — For webcam video capture and frame processing.

mediapipe (v0.10.9) — For real-time hand landmark detection and tracking.

pyautogui — For automated mouse cursor control and media key triggers.

screen-brightness-control — For direct screen brightness adjustments.

numpy — For mathematical calculations and coordinate mapping.

📦 Installation & Setup Guide

Ensure Python 3.11 is installed on your Windows system.

Open your terminal or command prompt and install the required libraries:

pip install opencv-python mediapipe==0.10.9 pyautogui screen-brightness-control numpy ipykernel


Open the project inside Jupyter Notebook or VS Code.

Run the code cells sequentially from Cell 1 to Cell 3.

Press the 'q' key while the camera window is active to safely stop the program.

🌟 Project Importance & Real-World Impact

Touchless technology is becoming a major part of modern computing and Human-Computer Interaction (HCI). This project serves several important purposes:

Health, Safety, and Hygiene:

Traditional input devices like keyboards and mice are shared in offices, schools, and public spaces, making them common carriers for bacteria and viruses. A touchless system eliminates physical contact entirely, promoting better personal hygiene.

Assistive Technology & Accessibility:

For individuals with physical disabilities, motor impairments, or repetitive strain injuries (RSI) who find it difficult to use a standard mouse or keyboard, gesture-based control provides an alternative and empowering way to interact with computers.

Industrial and Medical Applications:

In sterile environments such as hospital operating rooms, laboratories, or manufacturing units where workers have wet, dirty, or gloved hands, touchless computer control allows operators to interact with screens without risking contamination or breaking sterile rules.

Convenience and Modern Experience:

It offers a futuristic, hands-free experience for media consumption, presentations, and everyday computer usage from a distance, reducing physical strain and improving user comfort.