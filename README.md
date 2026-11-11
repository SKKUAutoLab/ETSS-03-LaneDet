


<div align="center">

### Automation Lab, Sungkyunkwan University
  
# Lane Detection for CCTV-cameras with UI (v3.1)

## Installation

```Shell
conda create --name edgetss_lane_exhibition1 python=3.10 -y

conda activate edgetss_lane_exhibition1

pip install -U ultralytics sahi

git clone https://github.com/mikel-brostrom/yolo_tracking.git
cd yolo_tracking
pip install -e .

pip install torch==2.4.1 torchvision==0.19.1 torchaudio==2.4.1 --index-url https://download.pytorch.org/whl/cu121

pip install shapely

pip install PyQt6
```

## Getting Started

cd /path/LaneDet

bash run_demo_file.sh

## Evaluation

The result are shown in lane_detection/results
