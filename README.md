# Examples

## Package

```shell
go get github.com/yam8511/go-onnxruntime@v1.3.0
```

## YOLOv8 Object Detection

- [YOLOv8](https://docs.ultralytics.com/tasks/detect/)

```shell
go build -v -o run_od.exe ./yolov8_od

# Windows
./run_od.exe -lib your/onnxruntime.dll
# Linux
./run_od.exe
```

## YOLOv8 Classify

- [YOLOv8](https://docs.ultralytics.com/tasks/classify/)

```shell
go build -v -o run_cls.exe ./yolov8_cls

# Windows
./run_cls.exe -lib your/onnxruntime.dll
# Linux
./run_cls.exe
```

## YOLOv8 Segment

- [YOLOv8](https://docs.ultralytics.com/tasks/segment/)

```shell
go build -v -o run_seg.exe ./yolov8_seg

# Windows
./run_seg.exe -lib your/onnxruntime.dll
# Linux
./run_seg.exe
```

## YOLOv8 Pose

- [YOLOv8](https://docs.ultralytics.com/tasks/pose/)

```shell
go build -v -o run_pose.exe ./yolov8_pose

# Windows
./run_pose.exe -lib your/onnxruntime.dll
# Linux
./run_pose.exe
```
