# ISHANA_simpleMinds

## How to run?
* Open Folder Ishana_simpleMinds/Code
* Open code.py
* Run it as it is if new data is provided in the current directory only or Replace all the existing paths with new path of 60% data
<br>Line (34-35)<br>
![Screenshot 2021-10-01 at 3 34 58 PM](https://user-images.githubusercontent.com/72293452/135602851-afbcf00a-c735-4d7d-8755-96c4f56fbb6c.png)
<br>Line (44-45)<br>
![Screenshot 2021-10-01 at 3 35 10 PM](https://user-images.githubusercontent.com/72293452/135602857-dadf407f-e109-4db8-aac8-f3c0acd845b0.png)

* Run the python file
* A 'Submission.json' file will be created in the current working directory.

## Our Approach - 
* Extraction of endpoint and startpoint coordinates. Then checking if x-coordinates of start and end point and moving in that direction accordingly. Checking y-coordinates of start and end points and moving in that direction accordingly.

## Other Approaches we tried - 
* Using UNET image segmentation to extract the paths from the aerial images and then using it to find out shortest paths
* Using yolov3 model, training a self made dataset which identifies all the crossroads in the image, mark them as nodes of a graph, then apply Floyd Warshall algorithm to find shortest route

