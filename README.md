# CrowdHuman YOLOv5m - TFLite FP16

Person detection model trained on CrowdHuman dataset, exported to TFLite FP16 for mobile/edge deployment.

## Model Info

| Property | Value |
|----------|-------|
| Base model | YOLOv5m |
| Training dataset | CrowdHuman (15K images, 350K+ annotations) |
| Source | [mikel-brostrom/Yolov5_DeepSort_Pytorch](https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch) |
| Export format | TFLite FP16 |
| Input size | 640x640 |
| Classes | person (class 0) |
| Use case | Person detection in crowded scenes |

## Features

- Detects people in crowded scenes
- Handles back view, side view, partial occlusion
- FP16 quantized for efficient mobile inference

## Download

See [Releases](https://github.com/poiuy105/crowdhuman-yolov5m-tflite/releases) for pre-built TFLite models.

## CI/CD

This repository uses GitHub Actions to automatically:
1. Download the `crowdhuman_yolov5m.pt` model
2. Export to TFLite FP16 format
3. Upload as GitHub Release artifact

## License

The original model is from [mikel-brostrom/Yolov5_DeepSort_Pytorch](https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch). Please refer to the original repository for license details.
