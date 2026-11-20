<div align="center">

# 🏸 TheTrajectoryOfFeathers (羽迹)

**An open-source vision for computer vision and biomechanics in badminton video analysis.**

[English](README.md) | [简体中文](README_zh.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

## ✨ Why TheTrajectoryOfFeathers?

Badminton footage is challenging to analyze: fast shuttlecocks, motion blur, occlusion and limited frame rates can obscure the action. TheTrajectoryOfFeathers aims to bring computer vision, kinematics and AI together to turn match or training videos into useful insights for players and coaches.

**Status: planning.** This repository currently contains documentation only; no analysis features have been implemented.

## 🎯 Planned capabilities

- **Shuttlecock tracking:** explore multi-frame tracking and trajectory reconstruction when the shuttle is blurred or occluded. TrackNet and Kalman filtering are candidate approaches.
- **Movement and footwork:** explore pose estimation and player tracking to study movement, court coverage, reaction and body coordination. YOLOv8-Pose and ByteTrack are candidates.
- **Court calibration and measurements:** investigate mapping image coordinates to standard court dimensions (13.4 m × 6.1 m), with estimates of movement distance and speed where the video and calibration support them. Shuttle speed and force-related insights are longer-term research goals.
- **AI coach and reports:** explore structured analysis, training suggestions, visual reports and annotated videos.

These are goals, not established capabilities or a fixed architecture. Video-derived measurements depend on camera angle, calibration, frame rate and other conditions. A single camera cannot be assumed to accurately measure physical force or real shuttle speed; estimates would need validation and appropriate uncertainty.

Candidate libraries and models have their own licenses and terms, which must be reviewed before use or distribution. The MIT license here applies to this repository, not automatically to third-party dependencies or model weights.

## 🚀 Quick Start

```bash
git clone https://github.com/chzisnull/TheTrajectoryOfFeathers.git
cd TheTrajectoryOfFeathers
```

The project is in the planning stage. There is no application, dependency installation or model download to run yet.

## 🗺️ Roadmap

- Define use cases, datasets, evaluation methods and privacy considerations.
- Explore court calibration, player pose and shuttle tracking on representative footage.
- Investigate validated movement and shuttle measurements, including their limits.
- Explore AI-generated coaching suggestions, visual reports and annotated videos.

The order and scope may change as research progresses.

## 🤝 Contributing

Ideas, research references and constructive discussion are welcome. Open an issue to propose a change or discuss a substantial idea before submitting a pull request. Please respect the rights and privacy of people appearing in any shared footage.

## License

[MIT](LICENSE)
