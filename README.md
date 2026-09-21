# Vietnamese Traffic Sign Recognition

An Android application for detecting and managing Vietnamese traffic signs using on-device TensorFlow Lite inference. The app combines traffic sign recognition, detection history, search, account management, and traffic violation lookup in a mobile interface.

## Main Features

- Traffic sign detection using an on-device TensorFlow Lite model.
- Detect multiple traffic signs from captured or uploaded images.
- Display detected sign names, bounding boxes and confidence scores.
- Capture images directly from the device camera or select images from the gallery.
- Store detected signs with timestamps, confidence scores and cropped images.
- Search previous detections by traffic sign name.
- Traffic violation lookup by vehicle license plate.
- User registration, login and logout with Firebase Authentication.
- Multi-language interface with light and dark theme support.
- Local detection history and application settings.

## Tech Stack

**Platform:** Android  
**Language:** Java  
**Machine Learning:** TensorFlow Lite  
**Computer Vision:** On-device Object Detection  
**Authentication:** Firebase Authentication  
**Storage:** Local files / MediaStore  
**UI:** Android Fragments, RecyclerView, Material Design  
**Networking:** HttpURLConnection, WebView

## Project Structure

- `MainActivity.java` - Main navigation and application state
- `CameraActivity.java` - Camera/gallery input and TensorFlow Lite inference
- `Fragments/` - History, statistics, instructions, settings and violation lookup
- `Adapter/` - RecyclerView adapters
- `Models/` - Application data models
- `Helper/` - Shared application helpers
- `assets/` - TensorFlow Lite model and traffic sign labels
