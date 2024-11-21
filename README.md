# Yoga Vision

**Yoga Vision** is an innovative mobile application built with **Java** in **Android Studio**. It harnesses **MediaPipe** for real-time body movement tracking and a **TensorFlow Lite** model for exercise detection. The app accurately identifies yoga poses or exercises and counts repetitions, making it a valuable companion for fitness enthusiasts and yoga practitioners.

---

## Features

- **Exercise Detection**: Automatically recognizes yoga poses and exercises.
- **Repetition Counting**: Tracks and counts exercise repetitions accurately.
- **Real-Time Tracking**: Leverages MediaPipe for precise body movement analysis.
- **Lightweight Performance**: Powered by TensorFlow Lite for efficient mobile operation.
- **User-Friendly Interface**: Designed for ease of use with a clean and intuitive layout.

---

## Technology Stack

- **Programming Language**: Java  
- **Development Platform**: Android Studio  
- **Body Tracking**: MediaPipe  
- **Machine Learning Model**: TensorFlow Lite  

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/yoga-vision.git
2. Sync the Gradle files and resolve any dependencies.
3. Build and run the app on an Android device or emulator.

---

## Usage

1. Launch the **Yoga Vision** app on your Android device.
2. Grant camera permissions for real-time body tracking.
3. Perform your exercise or yoga routine in front of the camera.
4. View the detected exercise type and repetition count on the screen.

---

## How It Works

### MediaPipe Integration
- Captures video input through the device camera.
- Tracks body landmarks to understand movements in real time.

### Exercise Detection
- Utilizes a pre-trained TensorFlow Lite model to classify exercises based on movement patterns.

### Repetition Counting
- Identifies the start and end of repetitions using motion analysis and provides an accurate count.

---

## Project Structure

- **`src/main/java`**: Contains Java source files.
- **`src/main/res`**: Contains resource files like layouts, drawables, and strings.
- **`assets/model.tflite`**: Includes the TensorFlow Lite model used for exercise detection.

---

## Dependencies

- **MediaPipe**: For body movement tracking.  
- **TensorFlow Lite**: For lightweight machine learning inference.  
- **CameraX** *(Optional)*: For optimized camera handling.  

---

## Future Enhancements

- Add support for more exercises and yoga poses.  
- Provide detailed analytics and progress tracking for users.  
- Enhance the UI with additional visual feedback for better engagement.
