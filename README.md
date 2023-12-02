# Cephalogram Landmark Detection

This repository contains the code and output of our project

### Team

Rakesh Kumar K S - 20BAI1055

Jayasurya S - 20BAI1004

Ayyappan T - 20BAI1305

### Major Frameworks

- PyTorch - For everything related to deep learning
- Numpy - For some array manipulation and algebra
- Matplotlib - For visualization

### Dataset used

- We have used the popular ISBI 2015 Grand Challenge dataset for cephalometric landmark detection. It contains 400 images of which 150 is for training , 150 and 100 are two test sets. We have used one of them for validation and one for testing
- All the required data will download itself (`downloaded_processed_data()` function) 

### Steps to run

- In Cloud/Kaggle/Colab **(recommended)**
  - You can just run the notebook as is, in Kaggle (with GPU enabled) or Colab as they'd have most prerequisites installed. Other packages that maybe required are installed in the first cell of the notebook

- Local (Linux required for the code to automatically download the dataset)
  - Install PyTorch with cuda enabled, numpy, pillow, matplotlib alongside everything in the first cell
  - Make sure there is sufficient VRAM (8 GB) and RAM (8 GB) with atleast 1 GB of free disk space

### Results

57.00% SDR < 2 mm 

83.37% SDR < 3 mm

93.26% SDR < 4 mm

### Sample Output:
red = predicted, blue = true

![Sample Output](https://i.imgur.com/9rqoyyP.png)