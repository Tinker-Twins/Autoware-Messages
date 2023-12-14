# Autoware Messages

![Autoware](https://user-images.githubusercontent.com/63835446/158918717-58d6deaf-93fb-47f9-891d-e242b02cba7b.png)

Autoware stack message definitions for debugging, publishing, and subscribing data from Autoware stack.

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

> **Note:** You can ignore the warnings regarding packages having `stderr output` (if any).

## Usage:
With the Autoware stack message definitions built and the workspace sourced, the messages published (live or from pre-recorded bag files) from Autoware-enabled systems can be subscribed, echoed, analyzed, visualized, and (re)recorded (bag, csv, etc.).

This workflow has been successfully tested with local (source) as well as Docker installations of Autoware with ROS 2 Galactic and Humble distributions.

## References:
https://autowarefoundation.github.io/autoware-documentation/main
