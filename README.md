# Flatland 2

This is a fork of [Flatland](https://github.com/avidbots/flatland) modified to
work on [ROS 2](https://docs.ros.org/en/humble/The-ROS2-Project.html) natively
(not using [ROS 1 bridge](https://github.com/ros2/ros1_bridge)). The development
targeted [ROS 2 Humble](https://docs.ros.org/en/humble/The-ROS2-Project.html),
which was the latest release of
[ROS 2](https://docs.ros.org/en/humble/The-ROS2-Project.html) at the time of
writing.

## What is Flatland?

- Flatland is a performance centric 2D robot simulator
- It is useful for simple simulations that don't require 3D capabilities
- It allows for time acceleration, which is useful for reinforcement learning

## How do I get set up?

1. Install [git](https://git-scm.com)
2. `git clone` this repository into your project's workspace's `src` folder
3. Install the required dependencies using
   `rosdep install -i --from-path src --rosdistro humble -y`

### Do you have any working example?

- Optionally check out
  [turtlebot_flatland](https://github.com/avidbots/turtlebot_flatland) and run
  the turtlebot nav stack

## Who do I talk to?

- Please direct any questions to @josephduchesne

## Documentation

- How to use: http://flatland-simulator.readthedocs.io
- Doxygen: http://flatland-simulator-api.readthedocs.io
- For a quick start use: https://github.com/avidbots/turtlebot_flatland

## License

All Flatland code is BSD 3-clause licensed (see LICENSE for details)

Flatland uses a number of open source libraries that it includes in its source
tree:

- [ThreadPool](https://github.com/progschj/ThreadPool) Copyright (c) 2012 Jakob
  Progsch, Václav Zeman (zlib license)
- [Tweeny](https://github.com/mobius3/tweeny) Copyright (c) 2016 Leonardo
  Guilherme de Freitas (MIT license)
- [Box2d](https://github.com/erincatto/Box2D) Copyright (c) 2006-2017 Erin Catto
  [http://www.box2d.org](http://www.box2d.org) (zlib license)
