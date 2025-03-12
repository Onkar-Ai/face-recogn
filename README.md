# Face Recognition Project

This repository contains a project for face recognition, implemented in Python using machine learning techniques. The project is designed to detect and recognize human faces from images or videos.

---

## Features
- **Face Detection**: Identifies faces in images or video streams.
- **Face Recognition**: Matches detected faces against a known database.
- **Pre-trained Models**: Utilizes pre-trained machine learning models for accurate recognition.
- **Extensible Code**: Easy to add more faces or customize the recognition process.

---

## Prerequisites

Ensure you have the following installed:

- Python 3.7 or later
- Jupyter Notebook
- Required Python libraries (see [Requirements](#requirements))

---

## Requirements

Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

### Key Libraries Used
- `numpy`: For numerical computations
- `opencv-python`: For image and video processing
- `dlib`: For face detection and encoding
- `face_recognition`: Core library for face recognition

---

## Usage

### Step 1: Clone the Repository

```bash
[git clone https://github.com/Onkar-Ai/face-recogn/.git
]((https://github.com/Onkar-Ai/face-recogn.git
cd face-recognition
```

### Step 2: Setup

- Install the required libraries (see [Requirements](#requirements)).
- Place your training images in the `training_images/` folder.
- Run the Jupyter Notebook file:

```bash
jupyter notebook "face recognition (1).ipynb"
```

### Step 3: Run the Project

- Open the notebook in your browser.
- Follow the instructions in the notebook cells to load data, train models, and perform recognition tasks.

---

## File Structure

```
face-recognition/
├── training_images/        # Folder for training images
├── requirements.txt        # List of required Python libraries
├── face recognition (1).ipynb  # Main notebook file
└── README.md               # Project documentation
```

---

## Examples

Here are some examples of what this project can do:

1. **Face Detection**
   - Input: An image with multiple faces
   - Output: Annotated image with bounding boxes around detected faces.

2. **Face Recognition**
   - Input: An image or video
   - Output: Recognized faces labeled with their names.

---

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.


## Contact

For questions or support, please contact:
- **Your Name**: [kaleonkar97@gmail.com]
- GitHub: [Onkar-Ai](https://github.com/Onkar-Ai)
