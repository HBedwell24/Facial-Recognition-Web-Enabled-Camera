# Arduino-Yun-Snapshot-Camera
A UVC compatible camera is triggered by a PIR motion sensor to store a .png image on an Arduino Yun. After this task has been completed, the image is then uploaded to Amazon S3 (to be compared on an image to image basis with existing records in the opposing S3 bucket).
