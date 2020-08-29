# Traffic sign classification

This is a traffic sign classifier trained using CNN in keras wit tensorflow as the backend. It is having 43 different classes. The index of the different classes are given below. The trainig is done on google colab platform.

0 = Speed limit (20km/h) 

1 = Speed limit (30km/h)

2 = Speed limit (50km/h) 

3 = Speed limit (60km/h)

4 = Speed limit (70km/h) 

5 = Speed limit (80km/h)

6 = End of speed limit (80km/h)

7 = Speed limit (100km/h)

8 = Speed limit (120km/h)

9 = No passing

10 = No passing for vehicles over 3.5 metric tons

11 = Rightofway at the next intersection

12 = Priority road

13 = Yield

14 = Stop

15 = No vehicles

16 = Vehicles over 3.5 metric tons prohibited

17 = No entry

18 = General caution

19 = Dangerous curve to the left

20 = Dangerous curve to the right

21 = Double curve

22 = Bumpy road

23 = Slippery road

24 = Road narrows on the right


25 = Road work

26 = Traffic signals

27 = Pedestrians

28 = Children crossing 

29 = Bicycles crossing

30 = Beware of ice/snow

31 = Wild animals crossing

32 = End of all speed and passing limits

33 = Turn right ahead

34 = Turn left ahead

35 = Ahead only

36 = Go straight or right

37 = Go straight or left

38 = Keep right

39 = Keep left

40 = Roundabout mandatory

41 = End of no passing

42 = End of no passing by vehicles over 3.5 metric tons 

## Model performance 

Train loss      : 0.93   Train accuracy      : 0.99

Validation loss : 2.94   Validation accuracy : 0.98

Test loss       : 14.54  Train accuracy      : 0.95


## 1. Development Environment
- Google colaboratory
- tensorflow 2.0

__Step 1: Download the data set__

Download  the dataset and upload to the google drive from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip)

It is already having three .p files of 32x32 resized images:

    - train.p: The training set.
    - test.p: The testing set.
    - valid.p: The validation set.

We will use Python pickle to load the data.

__Step 2: Run the jupyter notebook__

upload and run all the cells of the jupyter notebook in google colab.
