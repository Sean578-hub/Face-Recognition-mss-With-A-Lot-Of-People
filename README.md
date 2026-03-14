# Face Recognition System (Python)

## Project Description
This project detects and identifies faces in real time using a webcam feed.
It can recognize multiple people simultaneously using image encoding.

## Technologies
- Python
- OpenCV
- face_recognition library
- NumPy

## How It Works
1. The webcam captures live video frames.
2. Faces are detected in each frame.
3. The face_recognition library converts faces into numerical encodings.
4. The encodings are compared with stored images of known people.
5. If a match is found, the person's name is displayed on the screen.

## How to Run

Install the required libraries:

pip install opencv-python  
pip install face_recognition  
pip install numpy  

Run the program:

python main.py

## Example Output
The program opens the webcam and detects faces in real time.
Detected faces are highlighted with a rectangle and labeled with names.

## Author
Sean Michaeli
