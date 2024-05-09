# Hand Gesture Paint

Hand Gesture Paint is a simple Python application that allows you to paint on a canvas using hand gestures captured through your webcam. You can draw lines of different colors by moving your hand in front of the camera. 

## Features

- **Real-time Painting**: The application provides a real-time painting experience where you can draw lines on a canvas as you move your hand.
- **Multiple Colors**: You can choose from four different colors (blue, green, red, yellow) to draw on the canvas.
- **Clear Canvas**: There's an option to clear the canvas with a single gesture, allowing you to start over.
- **Interactive UI**: The user interface includes boxes representing different colors and a clear button for easy interaction.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- Mediapipe

## Installation

1. Clone the repository:
```python
git clone https://github.com/yourusername/hand-gesture-paint.git
```

2. Install the required Python packages:

```python
pip install opencv-python numpy mediapipe
```

## Usage

1. Run the `AirCanvas.py` file:
```python
python AirCanvas.py
```

2. A window will open displaying the webcam feed along with a paint canvas. Move your hand in front of the camera to start painting.
3. Use the fingers to select colors or clear the canvas.
4. To quit the program, press the 'q' key.

## How it Works

The application uses the Mediapipe library to detect hand landmarks from the webcam feed. Based on the position of specific landmarks (e.g., thumb and forefinger), it determines whether to draw lines or change colors on the canvas.

## Demo

![Hand Gesture Paint Demo](demo.png)

## Contributing

This project was contributed to by Siddharth Maithani ([Siddharth Maithani](https://github.com/SidM24)). 

Contributions are welcome! If you have any ideas for improvements or bug fixes, feel free to open an issue or submit a pull request.

