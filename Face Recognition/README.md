# Face Recognition using Deep Learning

----

* In this project, we go through the concepts of Face Verification and Face Recognition and how they can be used.
* Many of the ideas presented here are from [FaceNet](https://arxiv.org/pdf/1503.03832.pdf),  [DeepFace](https://research.fb.com/wp-content/uploads/2016/11/deepface-closing-the-gap-to-human-level-performance-in-face-verification.pdf). 
* FaceNet learns a neural network that encodes a face image into a vector of `128` numbers.
* By comparing two such vectors, you can then determine if two pictures are of the same person.
* We'll use the CNN architecture `InceptionV2` for building the model described in the FaceNet paper.
* This datasets and files used in this project is a part of the deeplearning.ai's Specialization, Course 4: Convolutional Neural Networks.
