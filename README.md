<!--![alt text](https://github.com/nittaya2mu/DR-Screening_CNN/blob/main/kuse_startup_logo.jpg?raw=true,width=150)-->
<p align="center"><img src="https://github.com/nittaya2mu/DR-Screening_CNN/blob/main/figure1.png" /></p>

# DR-Screening_CNN
diabetic retinopathy screening using CNN
This project aims to study on diabetic retinopathy prior screening algorithm using CNN.
  * Input dataset (cropped & augmented RGB) - normal / abnormal
  * Preprocessing - NLMD & CLAHE
  * Convert RGB into HSV, YCrCb, and LAB
  * Texture feature extraction - GLCM & LBP
  * Model construction - SVM, Decision Tree, Logistic Regression
  * Extended experiments on CNN + LSTM

# Digital Image Processing Tutorial
 * [Introduction to Digital Image Processing](https://drive.google.com/file/d/1QzgfdkCQlCbBt8BiCMCFtCJGu3SnkKVf/view?usp=drive_link) by Nittaya
 * Colab : [Python Image Processing Tutorial Using OpenCV](https://colab.research.google.com/drive/1zW4fspYezZ4VIdg0B4y00tNdZtS6hiXu?usp=sharing)
 * [Digital Image Processing Basics](https://www.geeksforgeeks.org/digital-image-processing-basics/) source: Geeksforgeeks
# Code Book
  * NLMD & CLAHE - [NLMD.ipynb](/NLM.ipynb)<br />
    1.ใช้เทคนิคภาพขาวดำ<br />
      1.1 แยกสีเขียว green channel<br />
      1.2 ลด noise (Non-local Means Denoising)<br />
      1.3 ปรับแสง (Contrast Limited Adaptive Histogram Equalization-CLAHE)<br />

      รันเฉพาะ 01 without_augmentation ทำขั้นตอน 1.1-1.3<br />
      
<br />
<br />
<img src="https://th.bing.com/th/id/R.b1993d56b9eca21776b32cb3f175b58f?rik=bMtsN7cSPcBJxw&riu=http%3a%2f%2flocnguyen.com.au%2fwp-content%2fuploads%2f2015%2f12%2fPage-Break.png&ehk=zruL%2f8GBWo7gw6rqEZi4hh8B7EToMPDcCof39ly%2bJdg%3d&risl=&pid=ImgRaw&r=0" height="50" />
<sup>Powered by DR Team, Faculty of Science and Engineering, Kasetsart University, Sakon Nakhon, Thailand</sup><br />
<sup>Contact us: [DR Team Contact](mailto:nittaya.mu@ku.th)</sup>
