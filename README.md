# Age-and-Gender-Detection

The concept of detecting gender and age from
face photographs has become a hot topic in recent
years. Even if a person’s hairdo has been changed,
facial hair has been added or removed, and the facial
look of a person has been altered, a person’s identity
can be recognised by his or her eyes. These tasks,
can be easily completed by a human, but not by
machines that lack intelligence [8]. Furthermore, the
world is becoming increasingly reliant on machines.
As a result, it has become a trending topic in image
processing and computer vision. Face detection,
gesture detection, person recognition, motion capture
and detection are all in high demand due to the
security and authentication process’s reliability. For
detecting real time gender and age through webcam
we have developed a system which detects all the
faces from a scene and performs the gender and age
identification process on the faces from the scene.
We have decided to use concept of transfer learning
to implement the model. Through this research we
are learning a lot as we are progressing further.
Major learning for us is the transfer learning, which
is the trending methodology in the field of machine
learning and deep learning.

You can download the pre- trained models from following links.
1. gender_net.caffemodel: It is the pre-trained model weights for gender detection. Download: https://drive.google.com/file/d/1W_moLzMlGiELyPxWiYQJ9KFaXroQ_NFQ/view
2. deploy_gender.prototxt: is the model architecture for the gender detection model (a plain text file with a JSON-like structure containing all the neural network layer’s definitions). Download: https://drive.google.com/file/d/1AW3WduLk1haTVAxHOkVS_BEzel1WXQHP/view
3. age_net.caffemodel: It is the pre-trained model weights for age detection. Download: https://drive.google.com/file/d/1kiusFljZc9QfcIYdU2s7xrtWHTraHwmW/view
4. deploy_age.prototxt: is the model architecture for the age detection model (a plain text file with a JSON-like structure containing all the neural network layer’s definitions). Download: https://drive.google.com/file/d/1kWv0AjxGSN0g31OeJa02eBGM0R_jcjIl/view
5. res10_300x300_ssd_iter_140000_fp16.caffemodel: The pre-trained model weights for face detection. Download:  
6. deploy.prototxt.txt: This is the model architecture for the face detection model. https://raw.githubusercontent.com/opencv/opencv/master/samples/dnn/face_detector/deploy.prototxt
