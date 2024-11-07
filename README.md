# ML Fire Detection

ML Fire Detection is a machine learning project designed to integrate with surveillance cameras for real-time fire detection. By analyzing video feeds, the system can promptly identify fire incidents, enhancing safety measures in monitored environments.

## Technologies Used
- **Python**: Core programming language for developing the detection algorithms.
- **PyTorch**: Deep learning framework utilized for building and training the fire detection model.
- **OpenCV**: Library for real-time computer vision tasks, employed here for video processing.
- **YOLOv5**: Object detection model used to accurately identify fire in video frames.

## Features
1. **Real-Time Fire Detection**: Processes live video streams to detect fire incidents promptly.
2. **Integration with Surveillance Systems**: Designed to work seamlessly with existing camera setups.
3. **High Accuracy**: Utilizes advanced deep learning models to minimize false positives and negatives.
4. **Scalability**: Can be deployed across multiple cameras and locations for extensive monitoring.

## Installation Guide

### Prerequisites
- **Python 3.6** or higher
- **PyTorch**
- **OpenCV**
- **YOLOv5**

### Steps

1. **Clone the Repository**  
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/vansh-2905/ML-fire-detection.git
   cd ML-fire-detection
   ```

2. **Set Up Virtual Environment**  
   Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install Dependencies**  
   Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download YOLOv5 Model**  
   Download the pre-trained YOLOv5 model weights and place them in the project directory.

5. **Run the Detection Script**  
   Execute the fire detection script:
   ```bash
   python fire.py --source 0  # Replace 0 with the video source index or path
   ```

## Usage
- **Live Video Detection**: Connect to a live camera feed to monitor for fire incidents in real-time.
- **Video File Analysis**: Analyze pre-recorded video files for fire detection.
- **Alert System Integration**: Extend the system to trigger alerts upon fire detection for immediate response.

## Contributing
Contributions are welcome! Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request for review.
