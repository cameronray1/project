# Raspberry Pi 4 Facial Recognition


Materials: 

   + Raspberry Pi 4 
   + Webcam



Install Dependencies:

   
   + OpenCV
   + Mutils
   

Once Opencv and the necessary facial recognition files are downloaded:

1. Create a folder and name it with whatever face you would like to detect

2. Go to the headshots_picam.py file and change the name within it to whatever the person's name is

3. Upload photos (atleast 10 photos are necessary) with different angles of their respective face

4. In a new terminal type:
cd facial_recognition
    -This is done in order to access the facial_recognition folder that contains all of the respective files and code

5. Training the raspberry pi is necessary using the 10 photos
    - using the code "python train_model.py" which is a line of code that accesses the file within the facial_recognition folder
      the raspberry pi becomes familiar with the person's face and will be able to detect it

6. To see if the code actually works, type:
python facial_req.py
-If you see a live video feed with your face and a yellow box with your name underneath it, like in IMG_0364, this means that you have successfully completed all the steps
Another way to see if it only detects your face, show the camera another face and if you have completed all the steps correctly it should show a yellow box with unknown underneath. Like seen in IMG_0365.jpg


