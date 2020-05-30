# Face-Recognition
Now a days face recognition is the trending topic for researchers. It is a process of automatic identifying the faces from the digital camera or any video frame or any images.To develope a working Face Recognition System, we need to focus on four modules given below:

1.Face Detection:- This is the first step to achieve our goal. In this case, we will focus on finding face from the image or video. It will be achieved by haar-cascade-classifier.

2.Data Acquisition:- Once we have detected the face in the image then it will be stored in the directory. We will take atleast 100 images for each id. Every id is associated with a person.

3.Train the Recognizer:- On this phase, we will train our recognizer(LBPH algrothim) and it will produce .yml file after training. .yml file is a trained file which will be used in Recognition phase.

4.Face Recognition:- On this phase, we will capture a fresh photo. If this photo is already registered then our recognizer will make a prediction in the form his/her name.
