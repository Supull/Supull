# Open Source Contributions

A summary of merged pull requests contributed to open source projects.

---

## 1. Rename `Type::Unit` to `Type::Nominal` — [sage](https://github.com/adam-mcdaniel/sage)

- **PR:** [adam-mcdaniel/sage#84](https://github.com/adam-mcdaniel/sage/pull/84)
- **Status:** Merged — May 18, 2026
- **Description:** Renamed the internal compiler type `Type::Unit` to `Type::Nominal` in the [Sage programming language](https://github.com/adam-mcdaniel/sage), a systems language targeting multiple backends. This addressed [issue #38](https://github.com/adam-mcdaniel/sage/issues/38), which identified that the old name was semantically misleading.
- **Impact:** Improved clarity of the type system's naming conventions, making the codebase more intuitive for contributors and users.

---

## 2. Warn about missing `noble-updates`/`backports` on Ubuntu 24 installs — [ros2_documentation](https://github.com/ros2/ros2_documentation)

- **PR:** [ros2/ros2_documentation#6854](https://github.com/ros2/ros2_documentation/pull/6854)
- **Status:** Merged — May 24, 2026 (into `kilted` branch; tagged for backport to `jazzy`)
- **Description:** Added a documentation warning block for Ubuntu 24.04 users whose apt sources only include the base `noble` suite (missing `noble-updates` and `noble-backports`). This causes a broken package dependency error when attempting to install `ros-dev-tools`. The fix provides clear steps to check and update apt sources before proceeding, closing [issue #6853](https://github.com/ros2/ros2_documentation/issues/6853).
- **Impact:** Prevents a confusing installation failure for ROS 2 users on fresh Ubuntu 24.04 systems, improving the onboarding experience for the robotics community.
