# SurveillanceMonitor
Repo for RTSP camera matrix for Raspberry Pi based surveillance monitor or video matrix

These shell scripts are designed for IP camera streams.  The script works by calling multiple instances
of omxplayer using 'screen'.  I am specifically using RTSP and calling the substream of each camera, allowing primary streams
availability for other services.  

For raspberry pi, I am running a Pi 3 Model B.  I have tested this script all the way back on Pi 1 Model B.  It will run, but
not all 9 cameras at once.  There are only enough resources on the board for 6-7 cameras and even then you will only want 
to run your cameras at 10 fps.  

These two are formatted for a 9 camera, 3x3 setup, for either 1920x1080, or 1920x1200.  

Good luck!
