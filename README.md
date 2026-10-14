<div align="center">

# GLIO2

### [GLIO2: A GPU-Parallelized Tightly-Coupled LiDAR–Inertial–GNSS System for Robust and Real-Time Global Localization and Mapping](https://arxiv.org/abs/2610.12411)

[![arXiv](https://img.shields.io/badge/arXiv-2610.12411-B31B1B?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2610.12411)
[![Code](https://img.shields.io/badge/Code-Coming%20Soon-9E9E9E?style=flat-square)](#2-code-release)
[![Demo](https://img.shields.io/badge/Video-Demos-E53935?style=flat-square&logo=youtube&logoColor=white)](#11-demo-video)
[![ROS](https://img.shields.io/badge/ROS-Noetic-22314E?style=flat-square&logo=ros&logoColor=white)](#)
[![CUDA](https://img.shields.io/badge/CUDA-GPU%20Accelerated-76B900?style=flat-square&logo=nvidia&logoColor=white)](#)

</div>

### 📢 News

- 📄 **2026-10-08**: Paper released on [arXiv](https://arxiv.org/abs/2610.12411).

### 📄 Related Papers

- [GLIO2: A GPU-Parallelized Tightly-Coupled LiDAR–Inertial–GNSS System for Robust and Real-Time Global Localization and Mapping](https://arxiv.org/abs/2610.12411)
- [GLIO: Tightly-Coupled GNSS/LiDAR/IMU Integration for Continuous and Drift-free State Estimation of Intelligent Vehicles in Urban Areas](https://ieeexplore.ieee.org/document/10285475/)

## 1. Introduction

GLIO2 is a GPU-parallelized, tightly-coupled LiDAR–inertial–GNSS system for robust and real-time global localization and mapping in challenging environments such as long bridges and urban canyons.

<div align="center">
  <img src="assets/figures/system-overview.png" width="100%" alt="GLIO2 system overview">
</div>

### 1.1 Demo video

<table>
  <tr>
    <td align="center" width="50%">
      <a href="assets/videos/bridge.mp4"><img src="assets/gifs/bridge.gif" width="100%" alt="Bridge demo"></a>
      <br><b>🌉 Cross-Sea Bridge</b>
      <br><sub>LiDAR degeneracy · high-speed driving</sub>
    </td>
    <td align="center" width="50%">
      <a href="assets/videos/urban.mp4"><img src="assets/gifs/urban.gif" width="100%" alt="Urban canyon demo"></a>
      <br><b>🏙️ Urban Canyon</b>
      <br><sub>Severe GNSS multipath</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="assets/videos/facade-uav.mp4"><img src="assets/gifs/facade-uav.gif" width="100%" alt="Facade-cleaning UAV demo"></a>
      <br><b>🚁 Facade-Cleaning UAV</b>
      <br><sub>Autonomous cleaning on a 110 m high-rise facade</sub>
    </td>
    <td align="center" width="50%">
      <a href="assets/videos/guide-dog.mp4"><img src="assets/gifs/guide-dog.gif" width="100%" alt="Guide-dog demo"></a>
      <br><b>🐕 Robotic Guide Dog</b>
      <br><sub>Globally referenced navigation in pedestrian scenes</sub>
    </td>
  </tr>
</table>

### 1.2 Applications

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/figures/uav-application.png" width="100%" alt="Facade-cleaning UAV application">
      <br><b>Autonomous Facade-Cleaning UAV</b>
    </td>
    <td align="center" width="50%">
      <img src="assets/figures/guide-dog-application.png" width="100%" alt="Guide-dog navigation application">
      <br><b>Robotic Guide-Dog Navigation</b>
    </td>
  </tr>
</table>

## 2. Code Release

The code will be open-sourced once the paper is accepted.

## 3. Acknowledgements

GLIO2 builds on these excellent open-source projects:
[GLIO](https://github.com/XikunLiu-huskit/GLIO),
[GLIM](https://github.com/koide3/glim),
[GTSAM](https://github.com/borglab/gtsam),
[gnss_comm](https://github.com/HKUST-Aerial-Robotics/gnss_comm), and
[RTKLIB](https://github.com/tomojitakasu/RTKLIB).
We also thank the authors of the [UrbanNav dataset](https://github.com/IPNL-POLYU/UrbanNavDataset).

## 4. Contact

For further inquiries or assistance, please contact [qiiiii.zhang@connect.polyu.hk](mailto:qiiiii.zhang@connect.polyu.hk).
