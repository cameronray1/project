# Raspberry Pi 4 Facial Recognition


Materials: Raspberry Pi 4 and Webcam


Install Dependencies:
OpenCV
Imutils


Training the rasberry pi:
Copy the code for Facial Recognition

Create a new folder in "dataset"

Add photos of the person that you want the rasberry pi to recognitize and label the folder that persons name

Now, in the facial recognition folder, change headshots.py with the name

Using the camera and keyboard take photos of your face at multiple different angle (at least 10 photos)

In a new terminal type:
cd facial_recognition

Run the command to train the model:
python train_model.py

To test, type:
python facial_req.py


