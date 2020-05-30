# cs230

This project is for the machine learning course.
* model dir contains a Caffe model
* test_img dir contains 10 test images

We provide you with a trained Caffe model for recognizing handwritten numbers. You are required to transfer the Caffe model to the Huawei Shengteng AI platform, and test the model on the 10 test images we provide.

### note
-----
You can refer to four examples on Shengteng AI platform for inference.  
Here are some suggestions for you.

* for input:  
image size should be 28x28  
normalize image data to [0,1] and set it to numpy float32 type

* inference:  
predict the categories of the 10 images

* for output:  
classification result and confidence of the 10 images
