# rai_interfaces

**`rai_interfaces`** is a ROS 2 package containing message and service interface definitions for communication within the [RAI](https://github.com/RobotecAI/rai) ecosystem.

These interfaces are designed to support integration and communication in robotics systems using ROS 2, and are compatible with the **ROS 2 Humble** and **Jazzy** distributions.

---

## Features

* Custom message and service definitions used across the RAI platform.
* Compatible with ROS 2 Humble and Jazzy.
* Lightweight and modular for easy reuse in other packages.

---

## Installation

### Prerequisites

* ROS 2 (Humble Hawksbill or Jazzy Jalisco) installed and sourced.
* `colcon` build system.
* `rosdep` for installing dependencies.

### Clone into a ROS 2 Workspace

1. Create a ROS 2 workspace (if you don’t have one):

   ```bash
   mkdir -p ~/rai_ws/src
   cd ~/rai_ws/src
   ```

2. Clone the `rai_interfaces` repository:

   ```bash
   git clone https://github.com/RobotecAI/rai_interfaces.git
   ```

3. Install dependencies:

   ```bash
   cd ~/rai_ws
   rosdep install --from-paths src --ignore-src -r -y
   ```

4. Build the workspace:

   ```bash
   colcon build
   ```

5. Source the workspace:

   ```bash
   source install/setup.bash
   ```

---

## Usage

After building and sourcing the workspace, the interfaces can be used within RAI as well as ROS 2 packages.
