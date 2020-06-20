# WalkYTo-rl
Walk Yourself, Toddler! Toddlers can learn by deep reinforcement learning now.



## Environment Setup

![](./ant_v1.png)



#### Basic Environment

- ubuntu 18.04
- python 3.6

#### Including (core)packages

- [gym-0.15.4](https://github.com/openai/gym)
- [roboschool-1.0.48](https://github.com/openai/roboschool)



#### Docker Image

you can get this environment by docker image, easily.

###### Pull image from the command line:

```bash
docker pull docker.pkg.github.com/cun-bjy/walkyto-rl/rl-gym:base
```

###### Use as base image in DockerFile:

```bash
FROM docker.pkg.github.com/cun-bjy/walkyto-rl/rl-gym:base
```



