

# Eye Disease Prediction System using YOLOV8

## Overview

The Eye Disease Prediction System is a machine learning-based application designed to detect and classify eye diseases from medical images. Utilizing YOLOv8, the system is capable of predicting five different classes of eye diseases with high accuracy.

## Features

- **Real-time Detection**: Provides real-time prediction of eye diseases from images.
- **Multi-Class Classification**: Detects and classifies up to five different types of eye diseases.
- **High Accuracy**: Leverages the power of YOLOv8 for precise and efficient predictions.
- **User-Friendly Interface**: Easy-to-use interface for uploading images and viewing predictions.

## Technologies Used

- **YOLOv8**: State-of-the-art object detection model used for disease prediction.
- **Python**: Programming language for developing the model and application.
- **TensorFlow/PyTorch**: Deep learning frameworks used for training and inference.
- **Flask**: Web framework for building the application interface.

## Classes

The system is capable of predicting the following five classes of eye diseases:

1. Diabetic Retinopathy
2. Glaucoma
3. Cataract
4. Age-related Macular Degeneration (AMD)
5. Normal (No Disease)

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/eye-disease-prediction.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd eye-disease-prediction
    ```

3. **Create a virtual environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

4. **Install the necessary dependencies**
    ```bash
    pip install -r requirements.txt
    ```

5. **Download the pretrained YOLOv8 model**
    - Follow the instructions in the `model/README.md` to download and set up the pretrained YOLOv8 model.

6. **Run the application**
    ```bash
    python app.py
    ```

## Usage

1. **Start the System**: Run the application and navigate to `http://localhost:5000` in your browser.
2. **Upload an Image**: Use the interface to upload an image of the eye.
3. **View Predictions**: The system will process the image and display the predicted eye disease along with the probability.

## Project Structure

```
eye-disease-prediction/
├── model/
│   ├── yolov8_model.pth
│   └── README.md
├── static/
│   ├── css/
│   └── images/
├── templates/
│   ├── index.html
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

- `model/`: Contains the pretrained YOLOv8 model and related files.
- `static/`: Contains static files such as CSS and images.
- `templates/`: Contains HTML templates for the web interface.
- `app.py`: Main application script.
- `requirements.txt`: List of dependencies.
- `README.md`: Provides information about the project.
- `LICENSE`: Contains the licensing information.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - rashmi04thewonder04@gmail.com

Project Link: [https://github.com/yourusername/eye-disease-prediction](https://github.com/yourusername/eye-disease-prediction)

---

Feel free to customize it as per your project's details and requirements!
