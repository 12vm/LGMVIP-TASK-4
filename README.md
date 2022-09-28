# LGMVIP-TASK-3
IMAGE TO PENCIL SKETCH USING PYTHON
cv2 library is required to be imported in the notebook.
THIS LIBRARY IS SPECIFICALLY USED FOR IMAGE PROCESSING , OBJECT DETECTION AND FACE DETECTION.
->Image is loaded into COLAB Notebook using cv2 library
->The image used in this model is present in the repository named as "tobey.jpg".
->The model image is then converted to grey scale image using CV2 library function and displayed using cv2_imshow() function.
->This grey scale image(255 levels) is then inverted .
->This inverted grey scale image is then blurred using Gaussian function present in cv2 library.
->This blurred image is then again inverted.
->Final sketch is produced by dividing the greyscale image value by value with inverted blurred image.
