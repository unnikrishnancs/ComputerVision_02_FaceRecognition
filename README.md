# FaceRecognition

Recognising faces from an image using face_recognition pre-trained model.  This model takes an image and generates embeddings for each face present in that image. 
This embedding is a 128 dimensional vector which captures the unique features of a face.

In this project, I have trained the model on images of my face. An embedding pickle file is created. The second part, creates an embedding for the unknown face. This embedding is compared with the known embeddings on which the model was trained. Finally it predicts a name corresponding to the unknown face in the image. The trained model draws a bounding box and names the face in the image. Else it names the face as "unknown"

References : https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/

