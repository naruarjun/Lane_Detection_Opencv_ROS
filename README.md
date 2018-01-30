# Lane_Detection_Opencv_ROS
The project detects lanes using basic image processing and than publishes the frames with lanes drawn across a topic called "chatter" and the coefficients of the lines depicting the lanes are published on a topic called "coeffs"

simpub.py - This is the file used to publish the frames of the video on the topic "chatter"

subscribevideo.py - This is the file used to subscribe to the topic chatter and then calculate the coefficients and then publish them on coeffs

video.msg - Custom message for coefficient publish
