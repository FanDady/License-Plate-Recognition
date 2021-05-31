# License-Plate-Recognition
## Introdution
The main content of this project is to identify the license plates of Chinese vehicles. We use cascaded classifiers to extract license plates and We use deep learning for character extraction.
![车牌识别](https://www.hualigs.cn/image/60b4a13e021a4.jpg)

## Requirement
- Tensorflow2.0
- A machine with NVIDIA GPU
- keras
- opencv
- PIL
- numpy
- importlib

## Quick Start
- Download the project
- Run the ```demo.py```

## Content
```
|-- README.md
|-- __pycache__
|-- demo.py        # 运行测试程序（只能识别蓝色车牌）
|-- detect.py      # 车牌提取和模型等函数
|-- model          # 模型文件
|   |-- cascade.xml
|   |-- model12.h5
|   |-- ocr_plate_all_gru.h5
|   |-- platech.ttf
|-- test_images
```

## Results
![](https://www.hualigs.cn/image/60b4a4f47a1db.jpg)
