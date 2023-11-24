# Mr Paget's Python Demos
## A selection of files demonstrating methods which may be useful for A Level projects, or which I just think are fun.


## A Tkinter Database
This project uses sqlite3 to interact with a database file, and Tkinter to provide the GUI.
The program has a single Tkinter window, but has multiple Frames to represent the different screens (which can be login screen, user details screen, output views etc)
These Frames are created an independent classes, so they can even be stored in separate python files and imported. They are all loaded up when the app is created, and then we use grid_forget to hide them when they are not needed.

