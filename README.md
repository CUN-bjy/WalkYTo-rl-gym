# WalkYTo-rl
Walk Yourself, Toddler! Toddlers can learn by deep reinforcement learning now.



## Environment Setup

#### Basic Environment

- ubuntu 18.04
- python 3.6

#### Including (core)packages

- [gym-0.15.4](https://github.com/openai/gym)
- [roboschool-1.0.48](https://github.com/openai/roboschool)



## Installation

#### Installation from Docker Image

you can get this environment by docker image, easily.

###### Pull image from the command line:

```bash
docker pull docker.pkg.github.com/cun-bjy/walkyto-rl/rl-gym:base
```

###### Use as base image in DockerFile:

```bash
FROM docker.pkg.github.com/cun-bjy/walkyto-rl/rl-gym:base
```



#### How to Run Container

```bash
docker run -it --name gym --env="DISPLAY" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" gym:base
```

설명:

​	`--env="DISPLAY" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw"`

​	: container내부의 환경을 host에서 GUI로 볼 수 있도록 설정



#### Test Code on Container

```bash
#on the container
cd $HOME; python ant_v1.py
```



<p styple="zoom:30%"><img src="./ant_v1.png" /></p>





## What's New

**2020-06-20** 

- **rl-gym** environemennt package pre-released

