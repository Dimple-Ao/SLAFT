# SLAFT

**Distance-Based Simultaneous Localization and Affine Formation Tracking for Second-Order Multi-Agent Systems**

Supplementary simulation videos for the SLAFT study.

## Overview

SLAFT couples distance-based position estimation with stress-matrix-based affine formation tracking for planar second-order multi-agent systems. Leaders provide global position references; followers use inter-agent distances, range rates, relative velocities, and states received from adjacent leaders. The framework considers translation, rotation, scaling, and shear of a nominal formation.

The videos accompany numerical simulations and a seven-Iris XTDrone software-in-the-loop study. This repository currently distributes video materials; simulation source code is not included.

## Videos

[Open the video release](https://github.com/Dimple-Ao/SLAFT/releases/tag/videos-v1.0)

| Video | Description | Size | Download |
| --- | --- | ---: | --- |
| Numerical Simulation | Numerical simulation demonstration | 10.74 MB | [MP4](https://github.com/Dimple-Ao/SLAFT/releases/download/videos-v1.0/Numerical.Simulation.mp4) |
| XTDrone SITL Experiment | Seven-Iris XTDrone software-in-the-loop experiment | 338.44 MB | [MP4](https://github.com/Dimple-Ao/SLAFT/releases/download/videos-v1.0/XTDrone_SITL_Experiment.mp4) |

Download the MP4 files and open them with a local video player. Sizes use decimal MB. Videos are distributed as Release assets so that the original files can be preserved without adding large binaries to Git history. GitHub may normalize spaces in uploaded asset names to periods.

See [the video manifest](videos/manifest.json) for exact byte sizes and [SHA256SUMS](videos/SHA256SUMS) for integrity checks. Cloning this repository or downloading its source ZIP does not include Release attachments.

## 中文说明

本仓库提供论文《Distance-Based Simultaneous Localization and Affine Formation Tracking for Second-Order Multi-Agent Systems》的仿真视频，研究二阶多智能体系统中基于距离的定位与仿射编队跟踪一体化方法。

- **数值仿真**：Numerical Simulation，约 10.74 MB。
- **XTDrone 软件在环仿真**：七架 Iris 无人机实验，约 338.44 MB。

请通过上表或 [Releases 页面](https://github.com/Dimple-Ao/SLAFT/releases/tag/videos-v1.0) 下载原始 MP4 视频。大视频超过 GitHub 普通 Git 文件的 100 MiB 限制，因此视频统一通过 Release 附件发布。仓库克隆及源码 ZIP 不包含视频附件。目前仓库仅提供视频材料，不包含仿真源代码。

## Integrity verification

On Windows PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 '.\Numerical.Simulation.mp4'
Get-FileHash -Algorithm SHA256 '.\XTDrone_SITL_Experiment.mp4'
```

Compare the results with `videos/SHA256SUMS`.
