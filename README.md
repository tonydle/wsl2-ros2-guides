# WSL2 Setup Guides for Robotics Development with ROS 2

Step-by-step guides for connecting robotics hardware to ROS 2 running inside WSL2 on Windows.

Originally created for *41069 Robotics Studio 2 at UTS*, but the instructions may also be useful for anyone developing robotics applications with ROS 2 on Windows.

If you do not have WSL2 installed yet, start here:

[Install WSL2 (Microsoft)](https://learn.microsoft.com/en-us/windows/wsl/install)

## Guides

1. [USB Passthrough to WSL2](./usb-passthrough.md)  
   Connect USB devices directly to Ubuntu inside WSL2 (example: Intel RealSense cameras).

2. [WSL2 Mirrored Networking](./mirrored-networking.md)  
   Configure networking so WSL2 can communicate with devices on the same network (example: UR robots).

## Tested On

- Ubuntu 24.04 via WSL2 on Windows 11
- Ubuntu 22.04 via [distrobox](https://distrobox.it/) on Ubuntu 24.04 via WSL2 on Windows 11 *(virtualisation-ception?)*
