# RockPaperScissor_Game_Project :

This repository contains a Python script RockPaperScissors.py that implements a simple Rock Paper Scissors game using hand gestures detected by a webcam. Below is an overview of the script along with instructions on how to run it.


Script Overview :
The RockPaperScissors.py script utilizes the OpenCV library to capture video frames from the webcam and detect hand gestures. It uses the cvzone and HandTrackingModule libraries for hand detection and gesture recognition. The game involves the player making a gesture representing either rock, paper, or scissors, and the computer randomly selects its move. The winner is determined based on the rules of the game.


Usage :

Upon execution, the script will open a window displaying the video feed from the webcam. Once the game starts, the player can make gestures representing rock, paper, or scissors. The computer's move will be displayed, and the winner will be determined based on the game rules.

Dependencies :

The script requires the following Python libraries:
cv2 (OpenCV)
cvzone
mediapipe

Notes :
Make sure you have a working webcam connected to your system.
Ensure that your hand is well-illuminated and clearly visible to the webcam for accurate detection.
The game may need to be run with elevated privileges to access the webcam.
Press the 's' key to start the game and the 'q' key to quit.
That's it! You should now be able to play the Rock Paper Scissors game using hand gestures detected by the RockPaperScissors.py script.
