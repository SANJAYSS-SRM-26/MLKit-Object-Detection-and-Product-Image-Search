# MLKit-Object-Detection-and-Product-Image-Search
  This repository contains an Android application designed to demonstrate object detection using Google's ML Kit and the implementation of a product image search feature based on the detected objects.

# Features
  Object Detection: Utilizes ML Kit's Object Detection API to detect objects in images captured from the camera or selected from the gallery.
  Clickable Object Detection Results: Renders detected objects as clickable dots on the displayed image. When a user clicks on a dot, the application crops the corresponding object from the image and provides it for further   processing.
  Product Image Search: Allows users to perform a reverse image search based on the detected objects. This feature enables users to find similar products online using images captured by the application.

# Components
  ImageClickableView: Customized ImageView component responsible for rendering clickable dots on detected objects and handling user interaction events.
  ObjectDetectorActivity: The main activity orchestrating the object detection process, image capture, and gallery image selection. It utilizes ML Kit's Object Detection API to identify objects in images.
  TransformedDetectionResult: Data class holding information about transformed detection results, including bounding box coordinates and center points.

# Usage
  Launching the Application: Users can launch the application on an Android device or emulator.
  Selecting Images: Users can choose images from the device's gallery or capture new images using the device's camera.
  Object Detection: Upon image selection or capture, the application performs object detection using ML Kit's Object Detection API.
  Clickable Detection Results: Detected objects are displayed as clickable dots on the image. Users can click on a dot to trigger the product image search feature.
  Product Image Search: When a user clicks on a dot, the application extracts the corresponding object from the image and initiates a product image search using the extracted object.
  Viewing Search Results: The application displays search results based on the detected object, enabling users to explore similar products available online.

# License
  This project is licensed under the Apache License, Version 2.0. See the LICENSE file for more details.
  
# Dependencies
  ML Kit Vision: Integrated for object detection functionality.
  AndroidX Libraries: Used for UI components and compatibility across Android devices.
  Google Material Design Components: Employed for consistent and modern UI design elements.

# Contributions
  Contributions to this project are welcome. Please feel free to fork the repository, make improvements, and submit pull requests for review.

# Acknowledgments
  Special thanks to the developers and contributors of ML Kit and the Android platform for providing powerful tools and frameworks for machine learning and mobile development.
