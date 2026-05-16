# Hand Gesture Image Filter

An interactive, real-time Python application that uses your webcam to apply various image filters. The unique feature of this project is that you can switch between different filters simply by using a **pinch gesture** (bringing your index finger and thumb together) recognized via MediaPipe.

## Features
- **Real-time Hand Gesture Recognition**: Utilizes MediaPipe Hands to detect a pinch gesture.
- **13 Unique Image Filters**: Includes Normal, Black & White, Cartoon, Sepia, Thermal, Sketch, Blur, Emboss, Edges, Negative, Color Enhancement, Pixelate, and Mosaic.
- **Interactive UI**: Live webcam feed processing using OpenCV.

## Requirements
Make sure you have Python installed on your system. You will also need to install the following libraries:
- `opencv-python`
- `mediapipe`
- `numpy`

## Step-by-Step Run Process

1. **Clone or Download the Repository:**
   Make sure you have the `Code.py` script downloaded on your local machine.

2. **Install the Required Libraries:**
   Open your terminal or command prompt and run the following command:
   ```bash
   pip install opencv-python mediapipe numpy
   ```

3. **Run the Application:**
   Navigate to the directory where the code is located and run the script:
   ```bash
   python Code.py
   ```

4. **How to Use:**
   - Once the webcam window opens, show your hand to the camera.
   - Perform a **pinch gesture** by tapping your index finger and thumb together.
   - Every time you pinch, the application will cycle to the next image filter!
   - To exit the application, press the **`Esc`** key on your keyboard.

## Credits & Contact
**Developed by SAMEER NADAF**

Let's connect!
- **GitHub**: [Sameergudusabnadaf](https://github.com/Sameergudusabnadaf)
- **LinkedIn**: [Sameer Nadaf](https://www.linkedin.com/in/sameer-nadaf) *(Please update this link with your exact LinkedIn profile URL if needed)*
