# ISHANA_simpleMinds

## How to run?
* Open Folder Ishana_simpleMinds/Code
* Open ishana.ipynb
* Replace all the existing paths with new path of 60% data![Screenshot 2021-10-01 at 2 28 10 PM](https://user-images.githubusercontent.com/72293452/135594516-4d83b890-56a8-4d79-9438-058474f4e1f2.png)
![Screenshot 2021-10-01 at 2 28 18 PM](https://user-images.githubusercontent.com/72293452/135594540-c70465f0-f497-4eaa-9b68-27567fbd36a0.png)
![Screenshot 2021-10-01 at 2 28 25 PM](https://user-images.githubusercontent.com/72293452/135594549-feb7bf96-c379-4b81-9a96-b06d974fc6ab.png)
* Run whole python Notebook
* A 'Submission.json' file will be created in the current working directory.

## Other Approaches we tried - 
* Using UNET image segmentation to extract the paths from the aerial images and then using it to find out shortest paths
* Using yolov3 model, training a self made dataset which identifies all the crossroads in the image, mark them as nodes of a graph, then apply Floyd Warshall algorithm to find shortest route

