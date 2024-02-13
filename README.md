# Parking Car Detection with YOLOv5

This project detects cars in a parking lot using YOLOv5, a popular object detection model. The code reads a video file, processes each frame, and identifies cars within a specified parking area. It then draws bounding boxes around the detected cars and displays the number of cars parked in the area.

## How it Works

1. **Initialization**: The code loads a pre-trained YOLOv5 model for object detection.

2. **Video Capture**: It opens a video file (e.g., `parking.mp4`) to process each frame.

3. **Detection**: For each frame, it detects cars using the YOLOv5 model. If a car is detected within the specified parking area, a bounding box is drawn around it.

4. **Display**: The processed frame with bounding boxes and the number of cars detected in the parking area are displayed.

5. **User Interaction**: The program continues processing frames until the user presses the 'Esc' key to exit.

## Requirements

- Python 3.x
- PyTorch
- OpenCV
- YOLOv5 (pretrained weights)
- GPU (recommended for faster inference)

## Usage

1. Clone the repository and install dependencies.
2. Download the pre-trained YOLOv5 model weights.
3. Place your video file in the same directory as the code.
4. Define the parking area polygon in the code.
5. Run the script.
6. Press 'Esc' to exit the video display.
