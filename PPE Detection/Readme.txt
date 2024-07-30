Data Source Link: https://universe.roboflow.com/roboflow-universe-projects/construction-site-safety/dataset/28

# To train the data model and get the best weights
!yolo task=detect mode=train model=yolov8l.pt data=..path_to_file epochs=50, imgsz=640