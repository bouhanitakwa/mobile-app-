This project is a mobile application developed during my first internship at Airbus. The app is designed to automatically detect missing supports (C-parts) in industrial panels using image comparison techniques.

The system takes two photos of a panel as input and predicts the differences between them, highlighting missing supports. This helps quality control teams identify errors quickly and efficiently.

Features

Input: Two photos of the same panel

Output: Visualization of missing supports or differences between the images

Backend: Processes images using computer vision techniques

Mobile App: Built with Flutter using Dart

Real-time Analysis: Fast processing to assist inspection teams

Technical Details
Frontend

Framework: Flutter (Dart language)

Functionality:

Upload or capture two images from the mobile device

Send images to the backend for processing

Display highlighted differences (missing supports)

Backend

Function: Image processing and difference detection

Techniques Used:

Image alignment

Feature matching

Difference detection algorithms to identify missing supports

Integration: Backend communicates with Flutter frontend via API or direct method calls

Workflow

User captures or uploads two panel photos in the app

Images are sent to the backend for processing

The system compares the images and detects missing supports

Results are returned to the app and displayed visually

Benefits

Reduces manual inspection time

Increases accuracy in detecting missing parts

Can be integrated into the production line quality control
