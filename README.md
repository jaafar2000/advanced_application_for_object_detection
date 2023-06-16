# advanced_application_for_object_detection

Steps to execute the project:
1.	Extract the zip file
2.	Install Python (version 3.7.2) from: https://www.python.org/ftp/python/3.7.2/python-3.7.2-amd64.exe
3.	Now, install the dependencies for the project using the following steps:
o	Open the command prompt (cmd)
o	Go to the project folder using the “cd _project_path_” command in cmd
o	Now type the command 
	pip install --upgrade pip
	pip install numpy
	pip install opencv-python
4.	Now double click on the file (App.py) or run it using cmd by typing (python App.py)
5.	Click on object detection button to start object detection
6.	Click on dimensions check to start the object dimensions measurement
Note-1: it is better to use external camera. To do that you need to change the camera source in the following files (App.py, camruler.py, frame_capture.py) from 0 to 1.
Note-2: for the dimensions measurement system you should follow this instruction:
  a.	The camera should be completely vertical to the object being measured.
  b.	The camera should have high quality with auto focus feature.
  c.	You need specify the range of the camera.
  d.	You need to have a good contrast between the object and the background so it’s better to have a white background.
  e.	You have to provide a suitable lighting condition to prevent the shadows of the object.
