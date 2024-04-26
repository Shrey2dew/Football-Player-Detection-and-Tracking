# Football-Player-Detection-and-Tracking

Football automated analytics ⚽ is hot topics in the intersection between AI and sports. In this project, we build a tool for detecting and tracking football players, referees and ball in videos. For this we use [YOLOv5](https://github.com/ultralytics/yolov5) (the latest version of the popular and fast object detector) for detecting the players in each frame of the video, and [ByteTrack](https://github.com/ifzhang/ByteTrack) a multi object detection model released in 2022 to identify the players and track their trajectory.

For the data, we use videos from the [DFL - Bundesliga Data Shootout](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data) competition on Kaggle for the demo. For training YOLOv8, we use the [football-players-detection](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc) dataset from Roboflow.

You can also use our dataset [football-players-detection-custom](https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Dataset/football-players-detection.v4i.yolov5pytorch.zip).

## 👨‍💻: Screenshots

# Output Result
<div align="left">
 
| Football PLayer Detection | Football PLayer Tracking | 
| :---         |     :---      |       
| <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Football_Detection_Result.jpg" width="500" height="auto" />  | <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Football_player_tracking.png" width="500" height="auto" />    

</div>

# Parametric Result
<div align="left">
 
|  | Football PLayer Tracking | 
| :---         |     :---      |       
| <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Football_Detection_Result.jpg" width="500" height="auto" />  | <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Football_player_tracking.png" width="500" height="auto" />    

</div>
