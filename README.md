Dependencies:

    pip install numpy
    pip install pandas
    pip install tensorflow
    pip install keras
    pip install opencv-python

Download kaggle dataset from here => https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

Download haarcascades file from here=> https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml


You will have to convert the images in the dataset into width* height pixels(in our case 48*48) and then have to label them based on emotions.after this part you can use the model as it is from the part where we feed data to our Conv2D model.
