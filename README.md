# yolov7-person-tracking

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

<img src="https://github.com/noorkhokhar99/people-tracking-yolov7/blob/main/Screen%20Shot%201444-03-24%20at%2010.01.33%20PM.png">

 ### References
 - https://github.com/WongKinYiu/yolov7

### My video file
- https://www.youtube.com/c/Pyresearch/videos

