# Document Scanner

In this Project, we made a simple document scanning scripts using OpenCV and Python.

NOTE : We implemented this project on the following system specification :

       Python Version 2.7.12 | Anaconda 4.1.1 (64-Bit)

       OpenCV Version 2.4.13
       
__Here, the key Algorithms used in document scanning are :__

__1__: Edge detection.

__2__: Use the edges in the image to find the contour (outline) representing the piece of paper being scanned.

      PS : The outline of the document in the image must be sharp and easily distinguishable from the background.

__3__: Apply a perspective transform to obtain the top-down view of the document.

__To run this Document scanner on your system follow these steps :__ 

__1__. Locate the image to be scanned on your PC.

__2__. Open the Terminal.

__3__. Navigate to the project directory in the Terminal.

__4__. execute the following : 

`python doc_scanner_main.py --image image.jpg`
   
where _image.jpg_ is the full path of your image
   
__5__. The scanned image obtained will be saved in the same project directory.
