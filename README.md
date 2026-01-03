# Age Detection Using OpenCV and Caffe

This project implements an age detection system using OpenCV’s DNN module together with a pre-trained Caffe model. The system detects faces in an image and predicts the age group of each detected face.

---

## Requirements

To run this project, you will need:

- Python 3.7 or higher
- OpenCV 4.5 or higher
- NumPy
- Matplotlib

### Required Model Files

**Age Detection Model (Caffe):**
- `age_deploy.prototxt` – Network configuration file
- `mobilenet_iter_73000.caffemodel` – Pre-trained model weights

**Face Detection Model:**
- `haarcascade_frontalface_default.xml` – Haar Cascade classifier for face detection

