# oCam_1CGN_U_T
oCam_1CGN_U_T python capture codes by WITHROBOT

0. install opencv and numpy
	```
	pip3 install opencv-python
	pip3 install numpy
	```

1. install libv4l2-dev
	```
	sudo apt install libv4l2-dev
	```

2. install v4l2 modue
	```
   	pip3 install v4l2
   	```

3. repalce v4l2.py
	```	
 	## cp ./v4l2.py </.YOUR/(VIRTUAL)PYTHON/PACKAGE/DIR>
  	cp ./v4l2.py /.local/lib/python3.5/site-packages/.
	del ./v4l2.py
 	```

4. run
	```
	python3 oCam_1CGN_U.py 
	or
	python3 oCamS-1CGN_U.py
	```

