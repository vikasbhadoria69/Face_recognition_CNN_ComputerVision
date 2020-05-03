The purpose of this project is to make facial recognition (identifying a face)  simple.

Whether it's for security, smart homes, or something else entirely, the area of application for facial recognition is quite large, so let's learn how we can use this technology.

requirements:
pip install face_recognition

In case you have issues installing it, then try installing cmake.
Install c++ from visual studio building tools and then pip install dlib.
After thet you should be good to go.

In this project I used face_recognition to find faces and compare them the results are very accurate but feel free to play around with tolerance. You have to chooose tolerance very carefully depending on the number of faces you want to detect. 
I used openCV to draw the rectangles and put text. 

Try running this using GPU as in CPU it might be slow. 
