# posture-detecter
A simple browser-based posture detection app that uses TensorFlow.js and PoseNet to give real-time feedback on your sitting or standing posture via webcam. Built during my first year of BTech CSE to explore machine learning in web development.
Posture Alert* is a browser-based application that leverages machine learning to monitor and assess user posture in real time using a webcam. Built using TensorFlow.js and the PoseNet model, it provides instant visual feedback to help users maintain good sitting or standing posture.

---

## Features

- Real-time posture detection via webcam
- Feedback messages such as:
  - "Good posture"
  - "Sit straight!"
  - "You're slouching"
- Lightweight and installation-free — runs directly in the browser
- Designed with simplicity and accessibility in mind

---

## How It Works

- The application accesses the user's webcam and processes video frames in real time.
- PoseNet identifies key body points such as shoulders and hips.
- Based on the relative vertical positions of these points, the app determines posture quality.
- Feedback updates continuously to encourage proper alignment.

---

## Technologies Used

- TensorFlow.js – Browser-based machine learning
- PoseNet – Real-time human pose estimation
- HTML5 and JavaScript – Frontend logic and rendering
- Canvas API – Drawing keypoints and live video frames

---

