# The Manta Model

This repo contains the need files to load the simulated ROV and it's control system with launch files.
For good examples look at this: https://github.com/uuvsimulator/rexrov2

## Folders and their contents

### manta_description

Mesh.

### manta_control

Configs.

### manta_gazebo

Launch files for the simulator in Gazebo.

## Example: start_demo.launch

Dependencies:

1. Installed UUV simulator

This is where the world is saved and loaded from.

2. The description of the ROV: manta_description

It has the needed files for simulation.

3. The configuration of the ROV: manta_control

It controls the thruster manager, and movable thrusters and all that.
