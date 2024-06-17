# ODM_Samar_lines

## How to set up hand tracking module:

1. Install python and a Python IDE (eg. PyCharm[recommended]).
2. Open the folder "/samar_lines/hand_and_tracking/" with the Python IDE.
3. Configure the python interpreter.
4. Select the option "Create virtual environment using requirements.txt" on the yellow notification that shows up in Pycharm and create a new virtual environment.
5. Wait for the installation of the required packages *OR* manually install the following packages: "cvzone", "mediapipe" e "MediaPipeTools"

> **Note:** In case there is more than one webcam connected to the computer, change the ID(set as 0) on line 11 ("cap = cv2.VideoCapture(0)").


## How to run:

1. Install processing.
2. Open the processing sketch inside the folder "samar_lines".
3. Run the sketch.
4. Run the python code to activate hand input.
5. And it's done!
