# Autoware Messages

![Autoware](https://user-images.githubusercontent.com/63835446/158918717-58d6deaf-93fb-47f9-891d-e242b02cba7b.png)

Autoware stack message definitions for debugging, publishing, subscribing, echoing, analyzing, visualizing, and recording data from Autoware-enabled systems.

## Installation:
1. Make a directory `ROS2_WS` to act as your ROS 2 workspace.
    ```bash
    $ mkdir -p ~/ROS2_WS/src/
    ```
2. Clone this repository into the source space `src` of your ROS 2 workspace `ROS2_WS`.
    ```bash
    $ git clone https://github.com/Tinker-Twins/Autoware-Messages.git
    ```
3. Build the packages.
    ```bash
    $ cd ~/ROS2_WS
    $ colcon build
    ```
4. Source the `setup.bash` file of your `ROS2_WS`.
    ```bash
    $ echo "source ~/ROS2_WS/install/setup.bash" >> ~/.bashrc
    $ source ~/.bashrc
    ```

> **Note:** You can ignore the `stderr` warnings (if any) during the `colcon` build process.

## Usage:
With the Autoware stack message definitions built and the workspace sourced, the messages published (live or from pre-recorded bag files) from Autoware-enabled systems can be subscribed, echoed, analyzed, visualized, and (re)recorded (bag, csv, etc.).

This workflow has been successfully tested with local (source) as well as Docker installations of [Autoware](https://autoware.org/) with ROS 2 [Galactic](https://docs.ros.org/en/galactic/index.html) and [Humble](https://docs.ros.org/en/humble/index.html) distributions.

## References:
- For Autoware's general documentation, see [Autoware Documentation](https://autowarefoundation.github.io/autoware-documentation/).

- For detailed documents of Autoware Universe components, see [Autoware Universe Documentation](https://autowarefoundation.github.io/autoware.universe/).

- For the official Autoware installation guide, see [Autoware Installation Guide](https://autowarefoundation.github.io/autoware-documentation/main/installation/).
  - [Autoware Local (Source) Installation](https://autowarefoundation.github.io/autoware-documentation/main/installation/autoware/source-installation/)
  - [Autoware Docker Installation](https://autowarefoundation.github.io/autoware-documentation/main/installation/autoware/docker-installation/)
    - [Quick Start Version Installation](https://autowarefoundation.github.io/autoware-documentation/main/installation/autoware/docker-installation-prebuilt/)
    - [Development Version Installation](https://autowarefoundation.github.io/autoware-documentation/main/installation/autoware/docker-installation-devel/)

- For the official Docker installation guide, see [Get Docker](https://docs.docker.com/get-docker/), and particularly for Ubuntu, see [Docker Ubuntu Installation](https://docs.docker.com/desktop/install/ubuntu/).
