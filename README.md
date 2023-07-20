FIRST YEAR B.tech II SEMESTER

PYTHON-ASSIGNMENT-2
ASSIGNMENT GIVEN BY PROFF.CHENNA REDDY SIR

###PYTHON PROGRAMMING### GROUP DETAILS:

Y NIKHIL SOURI - 22001A0572
V.SRINIKETH -22001A0558
B.AJAY KUMAR REDDY - 22001A0578
Code Description This code is designed to automate the popular game "Chrome Dino" using the PyAutoGUI library. It continuously captures screenshots of the game screen, analyzes the pixels in the captured image to detect obstacles (cacti and birds), and performs appropriate actions (jumping or ducking) to avoid collisions.

Requirements: The following libraries are required to run this code:

pyautogui: It provides functions to control the keyboard and mouse. Pillow (Python Imaging Library): It is used for capturing screenshots and manipulating images. Functions click(key) This function simulates a key press event by sending a key-down event for the specified key.

Parameters: key (string): The key to press. isCollision(data) This function checks for collisions with obstacles (cacti and birds) based on the provided pixel data.

Parameters: data (PIL.ImagePixelAccess): Pixel data of the captured image. main The main entry point of the program.

Waits for 5 seconds before starting the game. Executes a jump action initially to start the game loop. Enters an infinite loop to continuously capture screenshots and detect collisions. Commented code can be used to visualize the obstacles by drawing rectangles around them. Requirements To run this code, you need to have the following requirements:

Python 3.x installed on your system. Install the required libraries by running the following commands in your terminal: Copy code pip install pyautogui pip install pillow Note Please ensure that you have the game window of "Chrome Dino" open and visible on your screen before running the code. Also, make sure that the game window is not obstructed or covered by other windows.

Please let me know if you need any further assistance!
