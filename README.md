# AI.SLAM — Research Notes on Agricultural Mapping and Robotics

This repository is a **research and design notebook** exploring simultaneous localization and mapping (SLAM), perception, sensor selection, robotic autonomy, and safety considerations for outdoor agricultural environments.

**Scope:** The current public repository primarily contains Markdown research notes, design comparisons, links to references, and selected engineering documentation. **It is not a complete, runnable SLAM implementation.** In particular, it does not currently include a ROS 2 workspace, executable SLAM nodes, launch files, datasets, or an automated test suite.

## Topics covered

- Visual, visual-inertial, and LiDAR SLAM approaches, including their trade-offs for crop environments.
- Stereo cameras, IMUs, and edge-compute hardware.
- Robustness, safety, risk management, and autonomy concepts.
- Engineering research methods, evaluation ideas, and open questions.

## Where to start

- [`Research/SLAM/AI.SLAM/Approach.md`](Research/SLAM/AI.SLAM/Approach.md) — proposed SLAM architecture and sensor-processing concepts.
- [`Research/SLAM/AI.SLAM/ResearchResultSlamChoices.md`](Research/SLAM/AI.SLAM/ResearchResultSlamChoices.md) — comparison of mapping/localization approaches.
- [`Research/RiskManagement/STPA/STPA.md`](Research/RiskManagement/STPA/STPA.md) — system safety and hazard-analysis notes.
- [`Research/Hardware/`](Research/Hardware/) — hardware, camera, IMU and embedded-system research.
- [`Research/AutonomousRobustness/`](Research/AutonomousRobustness/) — robustness considerations.

## Status and interpretation

These materials document ongoing research and exploratory designs, **not validated performance results or a deployed autonomous system**. Some notes describe proposed components, potential integrations, or third-party approaches rather than software implemented in this repository. Claims from referenced external sources should be verified against those original sources.

No installation command is provided because this repository currently has no runnable application.

## Documentation and attribution

This collection includes research summaries and references to external tools, papers, projects and documentation. Third-party projects, names and source material remain the work of their respective authors. Check individual files and original references for attribution and usage rights.

## Privacy notice

Public documentation and Git history may include older technical research material. Do not assume that past commits were removed when a file was deleted from the latest branch. Publication rights for any employer-related hardware information, diagrams, datasets or research material must be reviewed separately.
