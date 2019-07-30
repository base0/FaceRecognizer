## FaceRecognizer

A face recognition algorithm written in Python.  From https://github.com/SnShine/FaceRecognizer but edit the code for Raspbian 10 and OpenCV 3.

## How to Use

- create 3 folders.  input_images, output_images, sorted_output_images
- put all pictures in **input_images**
- run **detect_save_images.py**.  the output will be in output_images folder
- create folder for each person in **sorted_output_images** and copy files from **output_images** to those folder.  For example, if there are 3 people, create folder **ann**, **bob**, **cindy** in **sorted_output_images**.
- run **face_detect_video.py**
