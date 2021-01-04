## The Manta ROV

This is repository contains the necessary files to simulate our ROV named Manta.

The start_demo launch file depends on:

- The UUV simulator (the loaded world is from there)

- manta_description (image_view, robot_state_publisher, ...)

- manta_control (thruster_manager, ...)

The launch file for operating Manta (manta_simulator) is a part of the Vortex-AUV project

- use the pc.launch

Follow this template: https://github.com/uuvsimulator/rexrov2
