# Unitree Z1 Isaac Sim Extension

This extension imports the Unitree Z1 robot (with gripper) into Isaac Sim and provides an RMPflow-based target following controller.

## Features
- **URDF Import**: Loads the Z1 robot with gripper from URDF.
- **Joint Control**: UI buttons to set joint angles and control gripper.
- **RMPflow Control**: Integration with Isaac Sim's RMPflow for collision-aware target following.

## Installation
1. Clone this repository.
2. In Isaac Sim, go to `Window > Extensions`.
3. Click the **Gear icon** (Settings) and add the `exts` folder of this repository to the **Extension Search Paths**.
4. Search for "Z1" and enable the `Import Z1` extension.

## Usage
1. Open the extension via `Isaac Examples > Import Robots > Z1 URDF`.
2. Click **Load Robot** to spawn the Z1 arm.
3. Click **RMPflow Follow Target** to enable the follow mode. A target cube will appear.
4. Move the target cube to control the robot end-effector.

