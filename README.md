****Face Detection using MTCNN and OpenCV****

This project is a Jupyter Notebook implementation of face detection on an image. It uses the MTCNN (Multi-task Cascaded Convolutional Networks) for accurate face detection and OpenCV for image manipulation.

**Features**

-*Face Detection*: Utilizes the mtcnn library to detect human faces in an image.
-*Image Processing*: Employs opencv to read and process the image.
-*Facenet Compatibility*: The detected face is cropped and resized to 160x160 pixels, a standard input size for models like FaceNet.
-*Haarcascade*: Includes an option to download the haarcascade_frontalface_default.xml file, which is another common method for face detection.
