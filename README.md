# ROS Message Fuzzer

This repository contains Alias Robotics's ROS message fuzzer.

[![PyPI version](https://badge.fury.io/py/ros1_fuzzer.svg)](https://badge.fury.io/py/ros1_fuzzer)   
[![Documentation Status](https://readthedocs.org/projects/ros1_fuzzer/badge/?version=latest)](https://ros1_fuzzer.readthedocs.io/en/latest/?badge=latest)   


This fuzzer aims to help developers and researchers to find bugs and vulnerabilities in ROS nodes by performing fuzz tests
over topics that the target nodes process. This fuzz cases consist in pseudorandom data that is optimized to cover all
possible limit cases, in order to test the correct behaviour of the nodes against data that would otherwise not show 
in normal testing cases or normal behaviour of the target robot.

The full documentation is available on [ReadTheDocs](https://ros1_fuzzer.readthedocs.com)

This project has been funded by the [ROSIN Project](http://rosin-project.eu/) as part of the REDROS-I project.
Contract agreement No.: 732287

Based on the original idea and Hypothesis-ROS project by [Florian Krommer](https://github.com/fkromer/hypothesis-ros)

