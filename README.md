[![Typing SVG](https://readme-typing-svg.demolab.com?font=Poppins&size=18&pause=1000&color=F7B21E&random=false&width=435&lines=Football+Player+Detection+and+Tracking+%F0%9F%8F%88)](https://git.io/typing-svg)

Football automated analytics ⚽ is hot topics in the intersection between AI and sports. In this project, we build a tool for detecting and tracking football players, referees and ball in videos. For this we use [YOLOv5](https://github.com/ultralytics/yolov5) (the latest version of the popular and fast object detector) for detecting the players in each frame of the video, and [ByteTrack](https://github.com/ifzhang/ByteTrack) a multi object detection model released in 2022 to identify the players and track their trajectory.

For the data, we use videos from the [DFL - Bundesliga Data Shootout](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data) competition on Kaggle for the demo. For training YOLOv8, we use the [football-players-detection](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc) dataset from Roboflow.

You can also use our dataset [football-players-detection-custom](https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Dataset/football-players-detection.v4i.yolov5pytorch.zip).

## 👨‍💻: Screenshots

### ● Output Result
<div align="left">
 
| Football PLayer Detection | Football PLayer Tracking | 
| :---         |     :---      |       
| <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Football_Detection_Result.jpg" width="500" height="auto" />  | <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Football_player_tracking.png" width="500" height="auto" />    
| _Note : Check results folder tracking video_ |

</div>

### ● Parametric Result
<div align="left">

| Results (Graph) |
| :---         |   
 <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Parametric%20Results/results.png" width="auto" height="auto" />   | 

| Results |
| :---         |   
 <img src="https://github.com/Shrey2dew/Football-Player-Detection-and-Tracking/blob/main/Result/Parametric%20Results/Results(text).png" width="auto" height="auto" />   | 

</div>

## Technologies Used ⚙️
1. Ultralytics YOLOv5m (Model)
2. ByteTrack (Video Tracking)
3. Roboflow Supervision (Video Processing)

## Project Structure
```
├─── Dataset/
├─── Detection and Tracking Files/
│     └─── Football_Player_Detection(Upload_from_Comp).ipynb
│     └─── football_player_tracking.ipynb
├─── Results/
│     └─── Football_Tracking_Result.mp4
│     └─── Parametric Results
├─── Weights/
│     └─── best.pt
├─── Runtime change.gif/
├─── README.md
├─── Project Report Sem VI.pdf
├─── LICENSE
└─── .gitignore
```
## License

Distributed under the MIT License. See [License](https://choosealicense.com/licenses/mit/) for more information.

Please adhere to this project's `code of conduct`.

## Conclusion
In conclusion, this project leverages the power of Ultralytics YOLO models and ByteTracking
for detection and tracking of football players , football , referee and goalkeeper help football associations to carefully monitor and analyse each and every player.
