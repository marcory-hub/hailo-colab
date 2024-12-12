# hailo-colab: Deploy Your Custom Object Detection Model on Raspberry Pi 5 with Hailo-8L AI Kit

**Key Benefit:** Train your model entirely within a Google Colab notebook environment, eliminating the need for a local NVIDIA GPU or x86 processor.

## 1. From Dataset to YOLO11 ONNX file
This Colab notebook, [dataset_yolo_onnx.ipynb](https://github.com/marcory-hub/hailo-colab/blob/main/dataset_yolo_onnx.ipynb), guides you in 6 steps: prepare your dataset, train a YOLO11 model, and convert it to an ONNX file (used for part 2).

1. **Prepare Files** - Download a dataset in yolo format or create your own.
2. **Zip and Upload** - Zip your dataset and upload it to your Google Drive.
3. **Colab Access** - Unzip the dataset in your Colab notebook environment.
4. **Train YOLO11** - Use the provided code to train a YOLO11 model.
5. **Convert to ONNX** - Convert the trained model best.pt to ONNX format best.onnx for Hailo's Dataflow Compiler.
6. **Save model** - Zip training folders with the best.pt and best.onnx in the folder weights.

## 2. Convert ONNX to HEF



