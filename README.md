# HTC
computer vision and twitter sentiment analysis

- Question 1 refer to 'yolov5 Detect.ipynb'
- Question 2a refer to 'Twitter - EDA.ipynb'
- Question 2b refer to 'Twitter - NLTK.ipynb'

- The best train model details for Question 1 is in exp18 folder.

- Brief explaination for Question 1:
1. Find the logo centre coordinate, width and height logo using Paints app.
2. Build train and test dataset. Then, put in the respective train and test folder.
3. Sample 1 and Sample 2 would be train data. I duplicate it 20 times each sample.
4. Sample 3 would be validation data. (But I also put sample 1 and 2 as val data to see the result)
5. Train the data using YOLOv5 small model. 
6. Tuning hyperparameter: image size and epochs.
7. Found out that img=640 and epochs=100 give a good detection already.
8. For the futher research, can try add more different samples as train data. 
9. Recommended by ultralytics: Images per class.≥ 1500 images per class. Start with 300 epochs and increase it. (Due to the time constrain and my personal laptop specs limitation, did not manage to follow the recommendation by them)
