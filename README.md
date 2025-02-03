# zephyrrtos-docker
A docker image that can be used as a development environment with VS Code for developing projects that use Zephyr RTOS.

## Introduction
This docker image uses the [CI image provided by the Zephyr Project](https://github.com/zephyrproject-rtos/docker-image) as it's base. This insalls the dependencies to use Zephyr RTOS. It also installs the Zephyr Toolchain as well as the nRF Connect SDK toolchain.

The actual Zephyr and nRF Connect SDK code must be referenced in the West manifest that belongs to the project.