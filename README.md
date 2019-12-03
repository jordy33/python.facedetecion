# Facial Detection
this reporsitory has two ways to do a a facial detection on:
- Image
- Video

## Requirements
- Install the following in the Jetson Nano:

```
sudo apt-get install libcanberra-gtk-module
```

- Python >= 3.x
- OpenCV > 3.x

## Run
this following in the way to run the code

- To run in an image

    ```
    python face_detect.py images/howresearch_4.jpg
    ```
- to run in video
    ```
    python face_detect-webcam.py
    ```
