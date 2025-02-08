# Photo-Editing-Application
SnapFilterEditor is an AI-powered image editing application that provides real-time GPU-based filters for high-performance image processing. The app allows users to apply a variety of filters, capture images, and save edited versions with ease.
Features

📷 Image Capture & Selection: Load images from the gallery or capture new ones using the camera.

🎨 AI-Powered Filters: Apply real-time GPU-based filters for high-performance editing.

🚀 OpenGL Shader Processing: Uses OpenGL ES for smooth and lag-free filter application.

💾 Save & Share: Save edited images and share them instantly.

🔄 Dynamic UI: Fragment-based navigation for seamless user experience.


****Installation*****

1. Clone this repository:
2. Open the project in Android Studio.
3. Connect an Android device or use an emulator.
4. Build and run the project.

*****How It Works*****

1. Image Loading & Processing

- Users can select images from the gallery or capture them using the camera.

- The app processes images using BitmapFactory and OpenGL-based rendering.

2. Filter Application

- The app uses GPUImageFilter to apply real-time filters.

- Each filter is defined using fragment shaders, modifying pixel data directly.

- Filters are queued in LinkedList, ensuring smooth application without lag.

3. Saving & Sharing

- Edited images are stored using MediaStore API.

- Users can share the images directly from the app.

*****Technology Stack*****

Language: Java (Android Studio)

Graphics: OpenGL ES, GPUImageFilter

Storage: MediaStore API, FileProvider

UI: Fragments, RecyclerView

****Future Enhancements****

📌 Add more AI-driven filters.

🎭 Implement facial recognition for effect-based enhancements.

📲 Integrate social media sharing options

*****License*****

This project is licensed under the Apache License 2.0.

Developed by [Sakib Aslam Sankeshwarkar]
