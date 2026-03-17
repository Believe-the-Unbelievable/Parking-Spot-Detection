
![tinywow_Screenshot 2026-03-17 133611_88637889](https://github.com/user-attachments/assets/afda0c0c-b7f3-45a9-a035-40a2df3181c9)

# Parking-Spot-Detection
A computer vision-based smart parking system that detects and classifies parking spots as empty or occupied using a trained machine learning model. It leverages OpenCV for image processing, connected component analysis for slot detection, and real-time video processing for efficient parking monitoring.

# 1. Install dependencies
pip install -r requirement.txt

# 2. Project structure
Make sure your folder looks like this:

project/
│── main.py
│── util.py
│── data/
│   ├── parking.mp4
│   ├── mask.png
│   └── model2.p

# 3. Run the main script
python main.py

# 4. What happens
Video file (parking.mp4) is loaded

Parking spots are detected using mask.png

Each spot is classified as empty or occupied

Green box → Empty

Red box → Occupied

Total available spots are displayed on screen

Press q to exit the window

