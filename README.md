# SLAM Frontier Exploration with Wavefront Planning
Author: Graham Clifford

This package uses breadth-first search to autonomously drive a differential-drive robot named "nubot"
around its environment, while simultaneously mapping that environment using slam_toolbox. Nav2 is used
to plan paths for nubot.

Here's some info on breadth-first search: https://www.personal.kent.edu/~rmuhamma/Algorithms/MyAlgorithms/GraphAlgor/breadthSearch.htm

## Quickstart
1. Clone nubot from https://github.com/m-elwin/nubot into the same workspace as this repository.
2. Build and source the workspace.
3. To have nubot map the environment autonomously, run:
    ```
    ros2 launch nubot_nav explore.launch.xml
    ```
4. To have nubot map the environment manually, with input from you, run:
    ```
    ros2 launch nubot_nav manual_gexplore.launch.xml
    ```

## Videos

Manual nubot:

https://github.com/ME495-EmbeddedSystems/homework4-gjcliff/assets/94981561/1004d0cb-0202-421a-9114-a6cc88ad87d3

Autonomous nubot:

https://github.com/ME495-EmbeddedSystems/homework4-gjcliff/assets/94981561/f3ed93a7-78f0-4ffd-a3fd-e0a91d3c57a1
