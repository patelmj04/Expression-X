# Expression-X
Expression-X is a real-time mood detection system that uses facial recognition to analyze emotions through a webcam feed. Built with a pretrained model from DeepFace and a simple Tkinter-based UI, it detects moods such as happiness, sadness, anger, and more, displaying results with confidence scores.

## Features
- **Real-Time Mood Detection**: Analyzes emotions from live webcam video.
- **Pretrained Model**: Leverages DeepFace for accurate emotion recognition (happy, sad, angry, surprise, fear, disgust, neutral).
- **User-Friendly Interface**: Includes a live video feed, mood display, confidence percentage, and control buttons.
- **Visual Feedback**: Draws bounding boxes around detected faces with mood labels.
- **Threaded Processing**: Ensures smooth UI performance during detection.

## Prerequisites
- Python 3.7 or higher
- A working webcam
- Good lighting conditions for optimal face detection

## Installation

1. **Clone the Repository** (or download the code):
   ```bash
   git clone https://github.com/patelmj/Expression-X.git
   cd Expression-X
   ```

2. **Install Dependencies**:
   Ensure you have `pip` installed, then run:
   ```bash
   pip install deepface opencv-python pillow tkinter
   ```

3. **Verify Webcam Access**:
   Make sure your webcam is connected and accessible by the system.

## Usage

1. **Run the Application**:
   ```bash
   python Expression-X.py
   ```

2. **Interface Guide**:
   - **Start Detection**: Click to begin real-time mood analysis.
   - **Stop Detection**: Pause the mood detection process.
   - **Quit**: Exit the application.
   - The video feed displays your face with a bounding box, mood label, and confidence score.

3. **Example Output**:
   - Mood: Happy
   - Confidence: 92.34%

## Requirements
- `deepface`: For pretrained emotion detection models
- `opencv-python`: For video capture and image processing
- `pillow`: For image conversion in Tkinter
- `tkinter`: For the graphical user interface

## Limitations
- Works with a single face at a time.
- Performance may vary based on hardware and lighting conditions.
- Requires a stable internet connection for initial DeepFace model downloads.

## Troubleshooting
- **Webcam Error**: Ensure your webcam is connected and not in use by another application.
- **Module Not Found**: Verify all dependencies are installed correctly.
- **Poor Detection**: Adjust lighting or face position for better results.

## Future Enhancements
- Support for multiple face detection.
- Mood history tracking.
- Color-coded emotion indicators.
- Photo capture and analysis functionality.

## Contributing
Feel free to fork this repository, submit issues, or create pull requests with improvements!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Built with [DeepFace](https://github.com/serengil/deepface) for emotion detection.
- Powered by [OpenCV](https://opencv.org/) and [Tkinter](https://docs.python.org/3/library/tkinter.html).

---

Developed by [Your Name] | March 2025
```

### Notes:
- Replace `https://github.com/yourusername/Expression-X.git` with your actual repository URL if you host it online.
- Add your name or handle in the "Developed by" section.
- If you choose a different name (e.g., "EmoteSense"), update all instances of "Expression-X" accordingly.
- You can create a separate `LICENSE` file with the MIT License text if you want to include it.

To use this:
1. Save it as `README.md` in your project directory.
2. Customize it as needed (e.g., add screenshots with `<img src="screenshot.png" alt="Expression-X Screenshot">` if you have them).

Let me know if you'd like to tweak anything specific!
