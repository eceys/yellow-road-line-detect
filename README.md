# yellow-road-line-detect
This code can detect yellow road lines.
I use opencv and numpy library.
Artificial intelligence python code.
How to run code :
1. Download code and open with any python IDE ( suggestion : pycharm ).
2. Run this code.
Note : If you want change yellowLine.mp4, you should rename your video same name or change cv2.VideoCapture("here") in code.
In other road the color range may vary. If you're not getting exact results, try changing the color ranges in here 
    lower_yellow = np.array([here, here, here], dtype=np.uint8)
    upper_yellow = np.array([here, here, here], dtype=np.uint8)
