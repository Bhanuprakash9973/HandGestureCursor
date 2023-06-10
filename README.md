# HandGestureCursor

This project utilizes computer vision and hand gesture recognition to control the mouse cursor and perform mouse actions using hand movements. The application captures the video stream from a webcam, processes it using the Mediapipe library, and maps specific hand gestures to mouse actions.

## Installation

To use this project, you need to have the following dependencies installed:

- OpenCV (`cv2`)
- Mediapipe (`mediapipe`)
- PyAutoGUI (`pyautogui`)

You can install the dependencies using pip:

pip install opencv-python
pip install mediapipe
pip install pyautogui


## Usage

1. Connect a webcam to your computer.

2. Run the `execute_mouse()` function from the provided code. This function captures the video stream, processes the hand gestures, and performs corresponding mouse actions.

3. Perform the following hand gestures to control the mouse:

   - **Gesture 1:** Move the middle finger close to the index finger to trigger a left-click action.
   - **Gesture 2:** Move the middle finger away from the index finger within a certain range to move the mouse cursor smoothly.
   - **Gesture 3:** Touch the thumb and ring finger together to perform a scroll-up action.
   - **Gesture 4:** Touch the thumb and little finger together to perform a scroll-down action.

4. The application will display a window titled "MouseCam" showing the video stream with the hand gestures and mouse actions overlaid.

5. Press the "Esc" key to stop the application.

## Contributing

Contributions to this project are welcome. If you find any issues or want to add new features, feel free to open a pull request.

## Acknowledgements

This project was created using the following libraries:

- OpenCV - [https://opencv.org/](https://opencv.org/)
- Mediapipe - [https://mediapipe.dev/](https://mediapipe.dev/)
- PyAutoGUI - [https://pyautogui.readthedocs.io/](https://pyautogui.readthedocs.io/)

## Contact

For any inquiries or questions, please contact [bhanuprakasheenadula@gmail.com].
