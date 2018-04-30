# Team 47's Notes
### Fork used for weight training
Commands
* ./darknet detector train cfg/obj.data cfg/yolo-obj.cfg darknet19_448.conv.23
* ./darknet detector demo cfg/obj.data cfg/yolo-obj.cfg [path/to/weight]

Useful Links
* https://timebutt.github.io/static/how-to-train-yolov2-to-detect-custom-objects/
* https://timebutt.github.io/static/understanding-yolov2-training-output/
* https://github.com/AlexeyAB/darknet#when-should-i-stop-training

Notes
* convert.py is used to convert BBox-Label-Tool text files to YOLO format
* process.py is used to separate your dataset into training and testing datasets.
