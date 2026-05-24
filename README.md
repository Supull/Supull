### Open Source Contributions

---

**[adam-mcdaniel/sage#84](https://github.com/adam-mcdaniel/sage/pull/84)** — Rename `Type::Unit` to `Type::Nominal`
Renamed a misleadingly named compiler type in the Sage programming language, resolving [issue #38](https://github.com/adam-mcdaniel/sage/issues/38).
`Merged · May 18, 2026`

---

**[ros2/ros2_documentation#6854](https://github.com/ros2/ros2_documentation/pull/6854)** — Warn about missing `noble-updates`/`backports` on Ubuntu 24 installs
Spotted and fixed a gap in the ROS 2 installation docs ([issue #6853](https://github.com/ros2/ros2_documentation/issues/6853)): on Ubuntu 24.04 systems where apt sources only include the base `noble` suite, installing `ros-dev-tools` fails with a broken `libbz2` dependency. Added a warning block with steps to add `noble-updates` and `noble-backports` before proceeding.
`Merged · May 24, 2026 · kilted · tagged for backport to jazzy`

---
