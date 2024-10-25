# GUI4LocalAnnotation
gui for 2d points annotation

## Installation
```bash
conda create -n tracker python=3.11
conda activate tracker
pip install PYQT5
```

## Data preparation
Download the required cfg data from: https://drive.google.com/drive/folders/1j72t0TYPMby-XYy2hrKBJX4QEgrLinfg?usp=drive_link
```
cd GUI4LocalAnnotation
mkdir anno_data
```

Place the downloaded data in the `anno_data` and the folder should be organized follow the structure below:
```
anno_data
├── cfg_0001
├── cfg_0002
│   ├── task_0026_user_0003_scene_0002_cfg_0002
│   │   ├── cfg_0002_cam_036422060215.mp4
│   │   ├── cfg_0002_cam_037522062165.mp4
│   │   ├── cfg_0002_cam_104122061850.mp4
│   │   ├── cfg_0002_cam_104122063678.mp4
│   │   ├── cfg_0002_cam_104422070044.mp4
│   │   ├── cfg_0002_cam_105422061350.mp4
│   │   └── joint_angle_info.pkl
│   ├── task_0028_user_0003_scene_0008_cfg_0002
│   ├── ...
├── cfg_0003
│   ├── ...
├── ...

```

## Usage
```bash
python gui_local.py
```

## Description of keypoints annotation for each cfg

#### cfg_0001: flexiv+ag_95
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/ag95_demo.gif" alt="keypoints of ag_95" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_12.png" alt="keypoints labeling of ag_95 in cfg_0001" width="45%">
</div>
<!-- ![keypoints of ag_95](./doc/gripper_kpt_anno_demo/ag95_demo.gif)
![keypoints labeling of ag_95 in cfg_0001](./doc/gripper_kpt_position/cfg_12.png) -->

#### cfg_0002: flexiv+ag_95
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/ag95_demo.gif" alt="keypoints of ag_95" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_12.png" alt="keypoints labeling of ag_95 in cfg_0002" width="45%">
</div>
<!-- ![keypoints of ag_95](./doc/gripper_kpt_anno_demo/ag95_demo.gif)
![keypoints labeling of ag_95 in cfg_0002](./doc/gripper_kpt_position/cfg_12.png) -->

#### cfg_0003: ur5+wsg_50
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/wsg50_demo.gif" alt="keypoints of wsg_50" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_3.png" alt="keypoints labeling of wsg_50 in cfg_0003" width="45%">
</div>
<!-- ![keypoints of wsg_50](./doc/gripper_kpt_anno_demo/wsg50_demo.gif)
![keypoints labeling of wsg_50 in cfg_0003](./doc/gripper_kpt_position/cfg_3.png) -->

#### cfg_0004: ur5+robotiq_85
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/robotiq85_demo.gif" alt="keypoints of robotiq_85" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_4.png" alt="keypoints labeling of robotiq_85 in cfg_0004" width="45%">
</div>
<!-- ![keypoints of robotiq_85](./doc/gripper_kpt_anno_demo/robotiq85_demo.gif)
![keypoints labeling of robotiq_85 in cfg_0004](./doc/gripper_kpt_position/cfg_4.png) -->

#### cfg_0005: franka
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/franka_demo.gif" alt="keypoints of franka" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_5.png" alt="keypoints labeling of franka in cfg_0005" width="45%">
</div>
<!-- ![keypoints of franka](./doc/gripper_kpt_anno_demo/franka_demo.gif)
![keypoints labeling of franka in cfg_0005](./doc/gripper_kpt_position/cfg_5.png) -->

#### cfg_0006: kuka+robotiq_85
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/robotiq85_demo.gif" alt="keypoints of robotiq_85" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_67.png" alt="keypoints labeling of robotiq_85 in cfg_0006" width="45%">
</div>
<!-- ![keypoints of robotiq_85](./doc/gripper_kpt_anno_demo/robotiq85_demo.gif)
![keypoints labeling of robotiq_85 in cfg_0006](./doc/gripper_kpt_position/cfg_67.png) -->

#### cfg_0007: kuka+robotiq_85
<div style="display: flex; justify-content: space-around;">
    <img src="./doc/gripper_kpt_anno_demo/robotiq85_demo.gif" alt="keypoints of robotiq_85" width="45%">
    <img src="./doc/gripper_kpt_position/cfg_67.png" alt="keypoints labeling of robotiq_85 in cfg_0007" width="45%">
</div>
<!-- ![keypoints of robotiq_85](./doc/gripper_kpt_anno_demo/robotiq85_demo.gif)
![keypoints labeling of robotiq_85 in cfg_0007](./doc/gripper_kpt_position/cfg_67.png) -->