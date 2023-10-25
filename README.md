# UAV-Path-Planning

This project we find safe path for UAV in a dynamic hostile environment. Using real-time detection model to locate position of each obstacles which use for mapping and path planning.

## Requirements
```
matplotlib=3.8.0=pypi_0
numpy=1.26.0=pypi_0
opencv-python=4.8.0.76=pypi_0
pandas=2.1.1=pypi_0
python=3.11.5=h955ad1f_0
torch=2.0.1=pypi_0
torchvision=0.15.2=pypi_0
ultralytics=8.0.183=pypi_0

```

## Installation

You can set up the required environment using the following command:

```
$ conda install requirements.txt
```

## Usage

...

## Folders

* `data`: Contains codes for data preprocessing and the original video data in the `video` subfolder (sourced from the [Stanford Drone Dataset](https://cvgl.stanford.edu/projects/uav_data/)).
* `path_planning`: Includes codes related to path planning, path visualization, and execution time calculation.
* `training`: Contains codes related to YOLO (You Only Look Once) for object detection.

## Video Result
A*

[![Watch the video](https://img.youtube.com/vi/jSYJiCu5KPU/1.jpg)](https://www.youtube.com/watch?v=jSYJiCu5KPU)

Tangent point

[![Watch the video](https://img.youtube.com/vi/d4k2MfiVOoI/1.jpg)](https://www.youtube.com/watch?v=d4k2MfiVOoI)

## Contact

Contributors names and contact info

* Akkapatch Thouchamongkol - 63011098@kmitl.ac.th
* Hong-Yi Chen - u09210012@ccu.edu.tw
* Yan-Hao Wang - u09520083@ccu.edu.tw
* Quan Tran Dinh Dai - tranquan687@gmail.com
* Van-Linh Nguyen - nvlinh@cs.ccu.edu.tw

## License
