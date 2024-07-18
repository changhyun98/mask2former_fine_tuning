# mask2former_fine_tuning

Goal : Prediction of plant growth

Method

1. Segment the image including background
/ Segmentation technique : mask2former
<img width="529" alt="image" src="https://github.com/user-attachments/assets/0f50f3cc-0114-40d3-a063-6eb1df850952">

2. Extract the main instance
The object closest to the center is the main instance.
<img width="529" alt="화면 캡처 2024-07-18 133106" src="https://github.com/user-attachments/assets/08f6bbc2-498e-43fd-82ab-261232cb26cf">


3. Combine the original image with masked image
![crop_sesame_w6_45_059625_background_mask](https://github.com/user-attachments/assets/a7bdb41d-768f-4277-b46b-28842b0def96)


4. Regression
Simple CNN model 


