# Apple_Counting_In_Orchard

Dataset: MinneApple: A Benchmark Dataset for Apple Detection and Segmentation https://conservancy.umn.edu/handle/11299/206575

This is a code to count number of apple in an apple orchard for yield estimation. 

The code is divided into two files:
  1. A Classification CNN model traind over counting folder of mentioned dataset. It classifies number of apples in an apple patch.
  2. And, A U-Net Semantic Segmantaion model to find the location of apples in an orchards and using above model to count total apples.

The CNN model provides an accuracy of around 97% and the U-Net model predicts location with an accuracy of 98%. 
Overall the system predicts the total apples with a decent accuracy which can be impoved by tuning the CNN model more. 

Reference: Häni, N., Roy, P. and Isler, V., 2020. MinneApple: a benchmark dataset for apple detection and segmentation. IEEE Robotics and Automation Letters, 5(2), pp.852-858.
