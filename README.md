# Motion dectection Program
This python program will allow you to detect motion and also store the time interval of the motion. It also plots the time interval at which the object entered the frame and left.
### Requirements :
This code is written in Visual Studio and the libraries used are **Pandas**, **Opencv**, **Numpy**, and **Bokeh**

### Main logic: 
> Videos can be treated as stack of pictures called frames. Here I am comparing different frames(pictures) to the first frame which should be static(No movements initially). We compare two images by comparing the intensity value of each pixels.

> The motion_detector.py will generate frames and store the time at which a moving object enters and leaves the frame. This file will be in csv extension. In this file the start time of motion and the end time of motion will be recorded. As you can see in the picture 
>  ![Screenshot 2022-03-26 173809](https://user-images.githubusercontent.com/100039012/160238830-39e78bdb-d86c-464f-95e9-29df55267e80.png)

> The motion_detector.py file acts as a library fro plotting.py file. We only need to run the plotting.py file to execute both of them. The plotting file gives us a bokeh plot which shows the time at which object entered and left. As you can see in the picture
> ![Screenshot 2022-03-26 173723](https://user-images.githubusercontent.com/100039012/160239072-489e0ad6-60a3-483a-b64b-0b1a1a80ab16.png)


