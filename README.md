# Cephalogram Landmark Detection using Coordinate Attention Module

This repository contains the code, output of our project as well as the report, survey (DA-1 and survey paper draft), presentation. Read below for more info

### Team

Rakesh Kumar K S - 20BAI1055

Jayasurya S - 20BAI1004

Ayyappan T - 20BAI1305

### Major frameworks

- PyTorch - For everything related to deep learning
- Numpy - For some array manipulation and algebra
- Matplotlib - For visualization

### Dataset used

- We have used the popular ISBI 2015 Grand Challenge dataset for cephalometric landmark detection. It contains 400 images of which 150 is for training , 150 and 100 are two test sets. We have used one of them for validation and one for testing
- **All the required data will download itself** *(`downloaded_processed_data()` function)*
- If needed, you can download the processed dataset (TIFF format to JPEG) from [here](https://drive.google.com/file/d/1gTmP4u4CGPKjEC0OFcx6TsIgtdC2U33Y/view?usp=sharing)

### Referred papers

All of the referred papers can be found [here](https://drive.google.com/drive/folders/12PASfQ3OOASef5D28ket3ESV918OGmD8?usp=sharing)

- All the papers referred in our project report is listed in the parent folder with their file name being the same as their reference number in the report. I.e. 12.pdf for the reference [12]
- Additionally, there is another folder named "All papers" inside the above folder. This folder contains the papers that we referred to while doing the literature survey for the project at the beginning (which we submitted as DA-1) 

### Steps to run

- In Cloud/Kaggle/Colab **(recommended)**
  - You can just run the notebook as is, in Kaggle (with GPU enabled) or Colab as they'd have most prerequisites installed. Other packages that maybe required are installed in the first cell of the notebook
  - All the cells will execute without any error, though the model will be retrained with randomly initialized weights each time you run the notebook. So the results reported and the results obtained might slightly vary

- Local (Linux required for the code to automatically download the dataset)
  - Install PyTorch with cuda enabled, numpy, pillow, matplotlib alongside everything in the first cell
  - Make sure there is sufficient VRAM (8 GB) and RAM (8 GB) with atleast 1 GB of free disk space

### Results

57.00% SDR < 2 mm 

83.37% SDR < 3 mm

93.26% SDR < 4 mm

### Sample output:
red = predicted, blue = true

![Sample Output](https://i.imgur.com/9rqoyyP.png)
