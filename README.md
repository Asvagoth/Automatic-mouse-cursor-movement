# Automatic-mouse-cursor-movement written on python

import pyautogui is used to import the PyAutoGUI library.
"pyautogui" is a Python library that provides functions for automating mouse and keyboard interactions.
It allows you to programmatically control the mouse and keyboard to simulate user input or perform tasks such as moving the mouse to specific coordinates, clicking, typing, and more.

To break the code when pressing the keyboard key "Esc" you would need to have the "keyboard" library installed
You can install it by writing in the terminal: pip install keyboard  or manually installing it in the IDE you are using.
After that, you need to import it in the code -> import keyboard 

Quit the program by pressing  the keyboard key: "Esc" or by using the Fail-Safe

There is a FAIL-SAFE build-in pyautogui in which if you move manually the mouse cursor to one of your monitor angles, the program will trigger the fail-safe and stop working. 
You will see this or a similar message in your console:
"raise FailSafeException(
pyautogui.FailSafeException: PyAutoGUI fail-safe triggered from the mouse moving to a corner of the screen. To disable this fail-safe, set pyautogui.FAILSAFE to False. DISABLING FAIL-SAFE IS NOT RECOMMENDED.
"
