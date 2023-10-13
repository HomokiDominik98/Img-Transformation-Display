# Img-Transformation-Display
Image displayer application, that enables the user to select from different image transformation methods, which will be applied to the original image and displayed next to each other.

Requirements:
python 3.11.5
PyQt5            5.15.9
opencv-python    4.8.1.78
imutils          0.5.4

You can find all the libraries and their specific versions used in the virtual environment in the requirements.txt file. You only need to install the libaries listed above, the rest will be automatically installed along them

Running the display application:
- Setup the virtual environment for python
- Install the libraries
- Run Display_app.py

I used Qt desginer (which was downloaded along with the PyQt5 library) for creating the layout of the GUI. The MyUI.ui file was added to the workspace of the project in Visual Studio Code. There it was converted to .py file using the following formula: pyuic5 -x MyUI.ui -o Display_app.py. Later on UI's code was modified a bit to fit better to my preferences.


