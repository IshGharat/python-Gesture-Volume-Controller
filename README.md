# Gesture Volume Controller Readme

This repository contains a Python script that uses the Mediapipe library to control the volume of the system using hand gestures captured from a webcam.

## Installation

1. Make sure you have Python installed on your system.
2. Clone this repository or download the script.
3. Install the required dependencies by running the following command:
   ```
   pip install opencv-python mediapipe pycaw comtypes
   ```

## Usage

1. Connect a webcam to your system.
2. Run the script `Volume Controller` using the following command:
   ```
   python "Volume Controller"
   ```
3. The script will use the default webcam and start capturing video frames.
4. Place your hand in front of the webcam with your palm facing the camera.
5. Move your thumb and index finger closer together or farther apart to control the volume. The distance between your thumb and index finger determines the volume level.
6. The volume control is visualized on the screen, including a volume bar and percentage indicator.
7. Press 'q' to quit the script and stop the webcam capture.

## Libraries Used

- OpenCV (cv2): Used for capturing video from the webcam and displaying the output.
- Mediapipe (mp): Provides hand tracking and landmark detection functionality.
- Math (math): Used for calculating the distance between thumb and index finger.
- NumPy (np): Used for data interpolation and manipulation.
- ctypes and comtypes: Used for interacting with the Windows Core Audio API (pycaw) to control the system volume.

## License

The script in this repository is released under the [MIT License](LICENSE).

Feel free to modify and use the code according to your needs. Contributions are also welcome!

## Disclaimer

This script is for demonstration purposes only. The volume control functionality may not work as expected in all environments. The accuracy of hand tracking and gesture recognition depends on various factors such as lighting conditions, camera quality, and hand positioning. Use at your own risk.