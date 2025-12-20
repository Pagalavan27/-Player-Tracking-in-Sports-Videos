# Player Tracking and Pose Estimation in Sports Videos

This project implements a computer vision system to detect and track players in various sports videos using deep learning models. It features player detection and human pose (keypoint) estimation applied to dynamic sports environments like cricket, football, and rugby.

## 📌 Project Overview

The system analyzes short sports clips to automatically identify players and their body joints (hands, legs, etc.) to assist in sports performance analysis.

### Key Features

* **Player Detection:** Built using the **YOLOv8** object detection framework.


* **Pose Estimation:** Implements **YOLOv8-pose** to identify player keypoints and skeletal structures.


* **Multi-Sport Support:** Tested on cricket, football, and rugby footage.



## 📊 Dataset

* **Content:** 6 sports video clips (cricket, football, rugby).


  **Duration:** 5-10 seconds per clip.


* **Format:** Vertical/Portrait orientation.


* **Source:** Publicly available YouTube sports videos.



## 🛠️ Requirements & Installation

This project was developed using **Python** and **PyTorch**. To install the necessary libraries, run:

```bash
pip install ultralytics opencv-python torch torchvision

```

## 🚀 How to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/[your-username]/[your-repo-name].git

```


2. **Open the Notebook:** Run `Programming_Ass_02.ipynb` in Google Colab or a local Jupyter environment.


3. **Process Videos:** Ensure your videos are placed in the dataset folder. The script will process each frame and save the output with detection overlays.



## 📈 Results & Discussion

* **Performance:** The models showed high stability with an average inference speed of ~6-20ms per frame on a T4 GPU.


* **Limitations:** Detections may be less accurate for distant players or during moments of fast motion and partial occlusion.


* **Future Improvements:** Enhancements could include adding DeepSORT for identity tracking and using temporal smoothing to stabilize pose estimation.



## 👤 Author

* T. Pagalavan (DTS2435) 


* Post Graduate Institute of Science, University of Peradeniya
