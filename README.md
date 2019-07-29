## FaceRecognizer

A face recognition algorithm written in Python.  From https://github.com/SnShine/FaceRecognizer

Real-Time detection & prediction of subjects/persons in video recording with built-in camera.

If there is any intruder (known/ unknown subjects) attack, it automatically posts on your Facebook timeline to notify you and your friends/neighbors.


## Usage of available files

|File Name|Used to|
|---------|-------|
|build_csv.py|build a csv file with paths to train images with labels.|
|detect_save_images.py|detect faces and save cropped images to output folder.|
|face_detect_recognition.py|detect & recognize faces in images and display them.|
|**face_detect_video.py**|detect & recognize intruders in real-time video.|
|face_recognition.py|train eigen_model & recognise faces in pre-cropped images|
|resize_rotate_images.py|pre-process images and saves output to output_folder|
