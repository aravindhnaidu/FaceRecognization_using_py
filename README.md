# FaceRecognization_using_dlib
Sure! Here's a concise and informative description for your GitHub repository on face recognition using `dlib`:

---

# Face Recognition Using `dlib`

This repository demonstrates a face recognition system using the powerful `dlib` library. The project involves detecting faces in images, extracting facial landmarks, and generating face encodings to recognize individuals.

## Features

- **Face Detection**: Utilizes `dlib`'s pre-trained HOG (Histogram of Oriented Gradients) based face detector.
- **Landmark Detection**: Extracts 68 facial landmarks using `dlib`'s shape predictor.
- **Face Encoding**: Generates 128D face descriptors for unique identification using `dlib`'s face recognition model.

## Requirements

- Python 3.6+
- `dlib`
- `scipy`
- `scikit-learn`
- `numpy`
- `imageio`
- `pillow`
- `cmake` (for building `dlib`)

## Installation

1. Install `cmake` and ensure it's added to your PATH.
2. Install required Python libraries:

    ```bash
    pip install dlib scipy scikit-learn numpy imageio pillow --user
    ```

3. Download the pre-trained model files:
    - [shape_predictor_68_face_landmarks.dat](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)
    - [dlib_face_recognition_resnet_model_v1.dat](http://dlib.net/files/dlib_face_recognition_resnet_model_v1.dat.bz2)

## Usage

Run the `face_recognition.py` script to detect and recognize faces in an image:

```bash
python face_recognition.py --image path_to_your_image.jpg
```

## Acknowledgements

- [dlib](http://dlib.net) for providing the pre-trained models and comprehensive library.

Feel free to contribute, report issues, or fork this repository to enhance the face recognition capabilities. Enjoy exploring the power of `dlib` for facial recognition!

---

This description provides an overview of the project, lists the main features, outlines the requirements and installation steps, and explains how to use the repository. It also invites contributions and acknowledges the `dlib` library.
