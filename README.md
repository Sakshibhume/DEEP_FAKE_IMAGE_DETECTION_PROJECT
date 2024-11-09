# DEEP_FAKE_IMAGE_DETECTION_PROJECT
This project aims to detect deep fake images using a convolutional neural network (CNN) model trained on synthetic and real images. It analyzes image features to distinguish between real and AI-generated faces with high accuracy.
Deep Fake Image Detection: Identifying Synthetic and Real Images with Precision

Detecting deep fake images using a CNN model trained to distinguish between AI-generated and authentic faces. This project offers a reliable solution to identify manipulated visuals, enhancing trust and accuracy in digital media analysis.
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
  ## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sakshibhume/Deep-Fake-Image-Detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Deep-Fake-Image-Detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ``
   Model Architecture
The CNN-based model uses convolutional layers for feature extraction, designed to capture facial patterns indicating deep fakes.
   ## Usage
   

To test the model on an image:
```bash
python detect_deepfake.py --image_path <path_to_image>

## Results

- **Accuracy:** 94%
- **Precision:** 92%
- **Recall:** 93%

Below are example outputs of real and fake images identified by the model:

![Example Output](images/output_example.png)


Dataset
The model is trained on images from the Celeb-DF and DeepFake Detection datasets.

Results
Accuracy: 94%
Precision: 92%
Recall: 93%
