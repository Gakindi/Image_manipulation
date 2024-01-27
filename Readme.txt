FaceSwap Dataset Download

Overview

This code is designed to facilitate the preparation of a dataset for FaceSwap, a face-swapping application. It includes the downloading and organization of videos and images needed for training and testing. The code creates a structured directory, downloads videos and masks from the EU2 server, organizes the data into training, testing, and validation sets, and extracts images for FaceSwap.

Instructions
Before running the code, ensure that the required dependencies are installed. Additionally, set the appropriate permissions for the "dataset" directory. If needed, adjust the number of videos and images to be downloaded and modify the server location.

External Files
The code relies on two external scripts:

Faceforencic_download_script.py: Used for downloading videos and masks.
extract_images.py: Used for extracting and cropping images from the dataset.