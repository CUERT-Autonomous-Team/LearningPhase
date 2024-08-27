# Autonomous: General Learning Phase

## Objective

by the end of this learning phase you will have the following skills:

* You will get familier with linux Oprating System.
* You will be able to identify your role in the team.
* You will have a good overview about other subteams.
* You will get hands on experience in ROS.

**Duration**: 10 days
**Don't hesitate to ask for help, if you don't quite understand something.**

## Introduction

**Duration**: 1 day

The objective of this playlist is to gain a general understanding of the navigation system without needing to grasp every detail. It's sufficient to know that these components exist and how they contribute to the overall functionality.

Watch this [playlist](https://www.youtube.com/playlist?list=PLn8PRpmsu08rLRGrnF-S6TyGrmcA2X7kg) about:

* Autonomous Navigation
* Localization
* SLAM
* Path Planning
* Object Tracking

## Linux

**Duration**: 3 days

As a developer, it is important to have a basic understanding of Linux OS.

watch this course at [Coursera](https://www.coursera.org/learn/codio-unix-system-basics)

To summarize: Here are some of the most important Linux commands that you should know:

##### VsCode

* `code .` : opens Vscode from any directory you are in.

##### File and Directory Commands

- `ls`: List files and directories in the current directory.
- `cd`: Change directory.
- `pwd`: Print working directory.
- `mkdir`: Create a new directory.
- `touch`: Create a new file.
- `rm`: Remove a file or directory.
- `cp`: Copy a file or directory.
- `mv`: Move a file or directory.
- `chmod`: Change file permissions.

##### System Commands

- `ps`: Show running processes.
- `top`: Show system resource usage.
- `kill`: Stop a running process.
- `sudo`: Run a command with administrative privileges.
- `apt-get`: Install and manage packages.
- `source`: Used to execute a script or load environment variables from a file into the current shell session. It is commonly used with shell scripts and configuration files.
- `export`: Used to set environment variables in a shell session. These environment variables are accessible to processes running in the current session.

##### Networking Commands

- `ping`: Test network connectivity.
- `ifconfig`: Show network interface configuration.
- `netstat`: Show network connections and statistics.
- `ssh`: Connect to a remote server using SSH.

##### Text Editing Commands

- `nano`: A simple text editor.
- `vi`: A powerful text editor.

These are just some of the basic Linux commands that developers should know. By mastering these commands, you can perform common tasks on the command line and become more efficient in your work.
It's recommended to watch this course at [Coursera](https://www.coursera.org/learn/codio-unix-system-basics)

## ROS

**Duration**: 6 days

Choose one of the following choises:

1. Watch this [playlist](https://www.youtube.com/playlist?list=PLLSegLrePWgIbIrA4iehUQ-impvIXdd9Q) about **ROS Noetic Fundamentals**.
2. Take the first 4 sections in this course(at least) [EDX](https://www.edx.org/course/hello-real-world-with-ros-robot-operating-system)
3. Udacity Course **Recommended** (ask your head about it)
Make sure to follow along with the videos to acquire hands-on experience.

Some of the important ROS concepts that you now should be familiar with :

#### Nodes

* Nodes are individual processes that perform specific tasks. They communicate with each other by publishing and subscribing to topics.

#### Topics

* Topics are named buses over which nodes exchange messages. A node can publish a message to a topic, and any other node can subscribe to that topic to receive the message.

#### Messages

* Messages are the data structures that are sent over topics. They define the format and content of the data being exchanged between nodes.

#### Services

* Services are a way for nodes to request and receive data from each other. A node can provide a service, and any other node can call that service to request data.

#### Actions

* Actions are similar to services, but they allow for more complex interactions between nodes. They involve a goal, feedback, and result.

#### Parameters

* Parameters are a way for nodes to store and retrieve configuration data. They can be set dynamically at runtime or loaded from a configuration file.

#### Launch Files

* Launch files are used to start multiple nodes and set their parameters and configurations. They allow for easy configuration and deployment of ROS systems.

## Turtlebot3

Follow these three guides:

1. This [guide](https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/) about **Turtlebot3 Gazebo World**.
2. This [guide](https://emanual.robotis.com/docs/en/platform/turtlebot3/slam_simulation/) about **Turtlebot3 SLAM**.
3. This [guide](https://emanual.robotis.com/docs/en/platform/turtlebot3/slam_simulation/) about **Turtlebot3 Navigation**.

**Skip** any installation as you have already installed turtlebot3.
