![Zoomed Face GIF Example 1](https://github.com/sourceduty/Face_Zoom_GIF/assets/123030236/fc57bf21-e28a-4be4-a0a6-ad039fcf9ab3)

> Create a GIF that zooms in on a detected face within an image.

#

This Python program is a graphical user interface (GUI) application designed to create a GIF that zooms in on a detected face within an image. The GUI is built using the Tkinter library, which is a standard Python interface to the Tk GUI toolkit. The application window is set to a default size of 650x350 pixels, with a gray background and a black area designated for displaying progress messages in yellow text. The main components of the interface include two buttons: "Load Image" for selecting an image file and "Create GIF" for processing the loaded image. When an image is loaded, the program reads it using the Pillow library and prepares it for processing.

The core functionality of the program revolves around face detection and the creation of a zoom-in effect, which is implemented using the OpenCV library. Once an image is loaded, the "Create GIF" button initiates the process of detecting a face within the image using a pre-trained Haar Cascade classifier. If a face is detected, the program calculates the coordinates of the face's center and progressively crops and resizes the image to create a zoom-in effect. This effect is achieved through a series of steps, where each step involves a larger crop around the face, resulting in a smooth zooming motion when the images are played sequentially.

After generating the frames for the zoom-in effect, the program saves them as a GIF file in a directory named "GIFs". The program ensures that this directory exists and creates it if necessary. The generated GIF maintains the original size of the loaded image, providing a clear and detailed zoom-in on the face. Throughout the process, the application updates the user with progress messages displayed in the designated black area of the GUI. These messages inform the user about the current step of the processing and notify them once the GIF has been successfully saved. This user-friendly feedback mechanism enhances the overall usability and ensures that the user is aware of the program's status at all times.

#
### Related Links

[Sliced GIF Maker](https://github.com/sourceduty/Sliced_GIF_Maker)

***
Copyright (C) 2024 [Sourceduty] - All Rights Reserved.
