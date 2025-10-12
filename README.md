<img width="934" height="105" alt="image" src="https://github.com/user-attachments/assets/7ded79b9-96ea-4fa9-be9e-bfee830cccd3" />

<img width="1320" height="192" alt="image" src="https://github.com/user-attachments/assets/71bc7ebc-b7cf-4f9f-8550-55de1aaf2cfb" />


# Face recognition is a method of identifying or verifying the identity of an individual using their face. Face recognition systems can be used to identify people in photos, video, or in real-time. 

# Use case:
1. Preventing crime
2. Unlock device
3. Blind assistance
4. Attendance system
5. Payments   
# Modules:
1. pip install opencv-contrib-python
2. import cv2, numpy, os
# Must use:
1. 'haarcascade_frontalface_default.xml' Cascade file for detecting faces
2. 'datasets' Folder containing the training data

# Full proccess:
1. download this repo & install 'opencv-contrib-python' in your system through terminal by this command "pip install opencv-contrib-python".
2. open the create_data.py file then add the name at "sub_data='name'" according to the person or subject  that you're going to use, then run it. It will open local camera, take 100 pictures of the subject whom you want to recognize & save those pics in the 'datasets' folder as your given 'name'.
3. Now just open the face_recognize.py file and run it, it will open the cam. Now just put the person or subject infront of camera & **instantly it will easily recognize the person by his/her name that you gave**.    
     
