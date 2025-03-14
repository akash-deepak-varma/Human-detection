# YOLOv11 Human Detection Model

This repository contains a human detection model trained using YOLOv11 on the **Human Dataset v2** from Roboflow. The model is designed to detect human figures in images and videos efficiently.

## 📌 Dataset Information
- **Dataset Name:** Human Dataset v2
- **Source:** [Roboflow Universe](https://universe.roboflow.com/human-v2/human-dataset-v2)
- **Author:** Human v2
- **Annotations:** Bounding boxes
- **Format:** YOLO medium
- **License:** Open Source
- **Publication Year:** 2022

## 🛠 Model Training
- **Architecture:** YOLOv11
- **Framework:** PyTorch 
- **Hardware:** GPU T4 x2
- **Training Epochs:** 30
- **Batch Size:** 32

## 📥 Installation
Clone the repository:
```bash
git clone https://github.com/your-username/yolo-human-detection.git
cd yolo-human-detection
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage
### Run Inference on an Image
```bash
python detect.py --source path/to/image.jpg --weights best.pt --conf 0.5
```

### Run Inference on a Video
```bash
python detect.py --source path/to/video.mp4 --weights best.pt --conf 0.5
```

### Run Inference on Live Webcam
```bash
python detect.py --source 0 --weights best.pt --conf 0.5
```

## 📊 Evaluation Metrics
- **mAP (Mean Average Precision):** mAP50:0.365
- **Inference Speed:** 11 FPS

## 🔗 Citation
If you use this dataset, please cite it as follows:
```bibtex
@misc{
    human-dataset-v2_dataset,
    title = { Human Dataset v2 Dataset },
    type = { Open Source Dataset },
    author = { Human v2 },
    howpublished = { \url{https://universe.roboflow.com/human-v2/human-dataset-v2} },
    url = { https://universe.roboflow.com/human-v2/human-dataset-v2 },
    journal = { Roboflow Universe },
    publisher = { Roboflow },
    year = { 2022 },
    month = { apr },
    note = { visited on 2025-03-14 },
}
```
## 🤝 Contributing
Feel free to submit issues or pull requests to improve the model and this repository.

---
Made with ❤️ by Akash.

