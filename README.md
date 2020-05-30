# cs230

This project is for the machine learning course.
* model dir contains a Caffe model
* test_img dir contains 10 test images

We provide you with a trained Caffe model for recognizing handwritten numbers. You are required to transfer the Caffe model to the Huawei Shengteng AI platform for inference, and correctly predict the labels of the provided 10 test images.

## Note
You can refer to four examples on Shengteng AI platform for inference.  
Here are some suggestions for you.

* For input:  
The input image should be scaled to 28*28, normalized to [0,1], and set to numpy float32 type.

* Inference:  
Predict the classification of the 10 images.

* For output:  
The output is the classification result and corresponding confidence.
