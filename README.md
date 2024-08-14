# Attendence-using-face-recognition-in-python
## Instructions

### Prerequisites
- Python 3.x
- Install the required Python packages:
  ```bash
  pip install opencv-python face-recognition numpy
  ```

### Setup

1. **Prepare Images**: 
   - Place images of individuals in the `ImagesAttendance` folder.
   - Ensure that each image file is named after the person it represents (e.g., `JohnDoe.jpg`).

2. **Run the System**:
   - Execute the script to start the face recognition and attendance logging:
     ```bash
     python main.py
     ```

### How It Works
- The system will start your webcam and continuously scan for faces.
- When a face is recognized, it will display the person's name on the video feed and log their name and the current time in `Attendance.csv`.

### Output
- An `Attendance.csv` file will be created/updated in the project directory, recording the attendance with timestamps.
