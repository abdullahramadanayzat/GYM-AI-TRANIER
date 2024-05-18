# GYM-AI-TRANIER
An AI model used to help with the training  by keeping track of counts and movement using the mediapipe
Certainly! Below is a README file to help you set up and run your exercise analysis program in a Jupyter notebook using Anaconda and MediaPipe.

Exercise Analysis Program
This program uses MediaPipe and OpenCV to analyze specific exercises by calculating the angles between body parts and providing real-time feedback. The exercises currently supported are "Raise Hand" and "Chest Exercise".

Prerequisites
Before running the program, make sure you have the following installed:

Anaconda: You can download and install Anaconda from here.

Jupyter Notebook: Jupyter comes pre-installed with Anaconda. You can launch it from the Anaconda Navigator.

Required Python Packages: Install the following packages in your Anaconda environment.

Run the code cell by cell. When prompted, select the exercise type by typing either "Raise Hand" or "Chest Exercise".

Follow the on-screen feedback to perform the exercise correctly.

Understanding the Code
Imports: Necessary libraries for computer vision, pose estimation, and image display are imported.

Utility Functions:

calculate_angle(a, b, c): Calculates the angle between three points.
get_coordinates(landmarks, body_part): Retrieves the (x, y) coordinates of the specified body part from the landmarks.
Exercise Analysis Functions:

analyze_raise_hand(landmarks): Analyzes the "Raise Hand" exercise and provides feedback.
analyze_chest_exercise(landmarks): Analyzes the "Chest Exercise" and provides feedback.
Main Loop:

Captures video frames.
Processes each frame to detect pose landmarks.
Analyzes the exercise based on the selected type and provides feedback.
Displays the feedback and a counter on the video frame.
Notes
Ensure your webcam is properly connected and functioning.
The program runs in a loop, capturing video frames until the capture device is manually stopped.
For any further questions or issues, feel free to consult the MediaPipe documentation and the OpenCV documentation.

