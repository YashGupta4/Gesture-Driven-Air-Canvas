# Gesture-Driven-Air-Canvas

A real-time application that allows you to draw in the air using hand gestures. This project leverages computer vision techniques and hand tracking to create a virtual drawing canvas.

## Features

- **Real-Time Hand Tracking:** Utilizes OpenCV and MediaPipe for accurate hand tracking.
- **Color Selection:** Select from four different colors (Blue, Green, Red, Yellow) to draw on the canvas.
- **Clear Canvas:** Easily clear the canvas with a gesture.
- **Adjustable Color Detection:** Fine-tune color detection using trackbars.

## Setup and Installation

### Prerequisites

- Python 3.7 or higher
- OpenCV
- NumPy
- MediaPipe

### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/YashGupta4/Gesture-Driven-Air-Canvas.git
    cd Gesture-Driven-Air-Canvas
    ```

2. **Create and Activate a Virtual Environment (Optional but Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the Required Packages:**
    ```bash
    pip install -r requirements.txt
    ```

## How to Run

1. **Run the Gesture-Driven-Air-Canvas Script:**
    ```bash
    python gesture_driven_air_canvas.py
    ```

2. **Adjust the Color Detection Settings:**
    - A window named "Color detectors" will appear with trackbars for adjusting the HSV values for marker color detection.
    - Tune the values to accurately detect your marker.

3. **Start Drawing:**
    - Use your hand gestures to draw on the canvas. 
    - Move your hand to the color buttons at the top of the screen to select different colors.
    - Move your hand to the "CLEAR" button to clear the canvas.

## Detailed Description

The Gesture-Driven-Air-Canvas is a virtual drawing application that allows you to draw in real-time using hand gestures. It combines the power of OpenCV for video processing and MediaPipe for precise hand landmark detection. The project features a virtual canvas where you can select different colors and draw using your hand as a marker.

### How It Works

1. **Hand Tracking:**
   - The application captures video frames from your webcam.
   - Using MediaPipe, it detects hand landmarks and tracks the position of the index finger and thumb.

2. **Drawing Logic:**
   - The application keeps track of the finger positions and draws lines on the canvas based on the detected movement.
   - You can select different colors by moving your hand to the color selection areas at the top of the screen.
   - The "CLEAR" button allows you to clear the canvas and start fresh.

3. **Color Detection:**
   - The application includes trackbars to fine-tune the HSV values for the marker color, ensuring accurate detection based on different lighting conditions.

## Screenshots
![image](https://github.com/user-attachments/assets/5fd39279-f5ad-44f2-b212-8e4c35f86e75)
![image](https://github.com/user-attachments/assets/b1d51e83-3146-423c-b2df-acde8e76d73a)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out to me at info.guptayash@gmail.com.
