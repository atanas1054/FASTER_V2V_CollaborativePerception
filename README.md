# V2V Collaborative LiDAR Perception Dataset

A Vehicle-to-Vehicle (V2V) collaborative LiDAR perception dataset for research in cooperative autonomous driving.

## Overview

This dataset contains synchronized LiDAR point cloud data captured from two vehicles simultaneously, designed for collaborative perception algorithms.

## Dataset Structure

For each timestamp, every vehicle provides:
- **Point Cloud** — Raw LiDAR scan (`.pcd` or `.bin`)
- **Pose File** — A `.yaml` file describing the LiDAR pose

```
dataset/
├── vehicle_1/
│   ├── 000000.pcd
│   ├── 000000_lidar_pose.yaml
│   ├── 000001.pcd
│   ├── 000001_lidar_pose.yaml
│   └── ...
└── vehicle_2/
    ├── 000000.pcd
    ├── 000000_lidar_pose.yaml
    ├── 000001.pcd
    ├── 000001_lidar_pose.yaml
    └── ...
```

## Format

This dataset follows the **V2V4Real** data format. Please refer to the original paper for full format specifications:

> *V2V4Real: A Real-world Large-scale Dataset for Vehicle-to-Vehicle Cooperative Perception*
> Runsheng Xu et al., CVPR 2023
> [[Paper]](https://arxiv.org/abs/2303.07601) · [[Project Page]](https://mobility-lab.seas.ucla.edu/v2v4real/)

## Download

> ⏳ **Dataset will be uploaded soon.** Stay tuned!


## License

Please check back when the dataset is released for licensing information.
