```markdown
# Partial Face Recognition using MediaPipe

This project demonstrates partial face recognition using the MediaPipe Face Detection solution. The solution includes two models: a short-range model optimized for faces within 2 meters from the camera and a full-range model suitable for faces within 5 meters.

## Requirements

- Python 3.x
- mediapipe
- opencv-contrib-python

Install the required dependencies using:

```bash
pip install mediapipe
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/partial-face-recognition.git
   cd partial-face-recognition
   ```

2. Run the Python script:

   ```bash
   python partial_face_recognition.py
   ```

3. Follow the instructions to upload images containing faces within 2 meters and 5 meters from the camera.

4. View the results of face detection for each image.

## File Structure

- `partial_face_recognition.py`: The main Python script implementing face detection using the MediaPipe Face Detection solution.
- `requirements.txt`: List of dependencies.

## MediaPipe Face Detection

The face detection is powered by the MediaPipe Face Detection solution. For more information, refer to the [MediaPipe documentation](https://solutions.mediapipe.dev/face_detection).

## Results

The detected faces will be displayed, highlighting the regions of interest based on the specified distance range. Results for both short-range and full-range models are presented separately.

## Acknowledgments

- [MediaPipe](https://mediapipe.dev/): For providing the Face Detection solution.
