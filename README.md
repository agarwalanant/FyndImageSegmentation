# FyndImageSegmentation
## Dataset discrepancy
Models were tained on different machines, Google Colab, DGX1, 1060 and tesla. The hardware belongs to my Prof. Dr Prashant Sigh Rana. I trained my models on the datasets created by me (Code included) and Publically datasets, I forgot to test the trained models on the data provided by Fynd, when Rishab pointed out that my saved models were deleted from my prof harware. Training the models from scratch was also not possible thus could not provide results on fynd data.
However I have detailed approach and my philosophy in the report. The related code is also available in the repository.

## Repo construction

1. Report.docx is thr document which has the why and how of my implementation.

2. train.py is the file that implements U-Net GAN based image segmentation.

3. Data Creation folder contains the scripts that were used to collect and prepare my data.

4. PytorchModel folder has the Pytoch implemetation of the Fast-RCNN model.

5. Results.docx file contains the results of the model that I implemented.



## Datasets

The datasets used can be found at https://drive.google.com/drive/folders/1m0McHaXVYqJcui-Qxcv5f53gZj15Hrr0?usp=sharing

Disclamer: Only public datasets were used and data was fetched from freely available public resourses.
