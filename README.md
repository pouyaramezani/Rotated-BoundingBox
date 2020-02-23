# Rotated-BoundingBox
Produce rotated bounding boxes from the binary masks <br>
## Set the path of binary masks: <br>
this_path = os.path.dirname('/home-local/poram.extra.nobkp/VOT/DAVIS/Annotations/480p/') <br>
<br>
It counts the different objects in the first frame and make a folder mask-i for i th object and copy binary mask for each object and then produce the rotated bounding boxes and save a text file and also a new image which show bounding boxes on binary image.<br>
NOTES:<br>
- It returns [[0,0],[0,0],[0,0],[0,0]] when it can not find the object in the frame. <br>
- consider the order of the corners of bounding boxes. the first is the lowest corner and then it goes CW <br>

![](\0.png)
