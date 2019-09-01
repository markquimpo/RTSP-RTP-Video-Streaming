Video Streaming with RTSP and RTP


Files:

README.txt
ClientLauncher.py
Client.py
ServerWorker.py
Server.py
RtpPacket.py
VideoStream.py
movie.Mjpeg


================================================================================
RUN:
================================================================================
Server:
$ python3 Server.py 2000

Client:
$ python3 ClientLauncher.py 127.0.0.1 2000 10500 movie.Mjpeg 
================================================================================



This Programming Assignment 6 is completely working.
First step I did is download the module of tKinter then PIL.

The video will run but there is some unknown error I encounter during the play of the video. The sequence number in Client side will stop at 217 and then lag. The jump to 237.
On the Server side, it say's "Connection Error". I have difficulty to fix this but I was able to complete the video and all button works.

Before to play the Video.
SETUP should be press first.
Then followed by PLAY.
PAUSE is also working. You can press pause whenever you want.
The end if the video is until sequence number of 500.
Once it reach to 500. Always press the PAUSE button first before pressing the 
TEARDOWN. Otherwise, it will shown an error. 
The optional part. I did not implement the STOP button. Which I could add but I don't have enough time.

:)
