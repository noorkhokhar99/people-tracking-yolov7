# yolov7-object-tracking

### New Features
- Added Label for Every Track
- Code can run on Both (CPU & GPU)
- Video/WebCam/External Camera/IP Stream Supported


### Steps to run Code
- Clone the repository.
```
git clone https://github.com/noorkhokhar99/people-tracking-yolov7.git
```
- Goto the cloned folder.
```
cd yolov7-object-tracking
```
- Create a  envirnoment (Recommended, If you dont want to disturb python packages)
```
### For Linux Users
python3 -m pip install -r requirements.txt

### For Window Users
cd yolov7objtracking
python3 -m pip install -r requirements.txt


```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Run the code with mentioned command below (by default, pretrained [yolov7](https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt) weights will be automatically downloaded into the working directory if they don't already exist).
```
# for detection only
python detect.py --weights yolov7.pt --source "your video.mp4"

#if you want to change source file
python detect_and_track.py --weights yolov7.pt --source "your video.mp4"

#for specific class (person)
python detect_and_track.py --weights yolov7.pt --source "your video.mp4" --classes 0
```

- Output file will be created in the ```working-dir/runs/detect/obj-tracking``` with original filename


### Results
<table>
  <tr>
    <td>YOLOv7 Detection Only</td>
    <td>YOLOv7 Object Tracking with ID</td>
    <td>YOLOv7 Object Tracking with ID and Label </td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/62513924/196107891-bb8124de-99c6-4039-b556-2ade403bd985.png"></td>
    <td><img src="https://user-images.githubusercontent.com/62513924/185798283-0455ce49-4359-4e52-8d69-fd30dd61c5b4.png"></td>
     <td><img src="https://user-images.githubusercontent.com/62513924/191241661-ed5b87eb-5c8c-49bc-8301-531ee86f3b38.png"></td>
  </tr>
 </table>


 ### References
 - https://github.com/WongKinYiu/yolov7

### My video file
- https://www.youtube.com/c/Pyresearch/videos

