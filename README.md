# Lab 3 – CPU Cycle Counting and Timing on PYNQ-Z2

## Overview
This lab explores **CPU timing and performance measurement** on the PYNQ-Z2 (ARM Cortex-A9) platform. The objective is to measure the number of CPU cycles elapsed during a known delay interval and compare hardware cycle counts with a Linux-based software timer.

The lab demonstrates:
- Command-line argument handling
- CPU cycle counting
- High-resolution timing
- Makefile-based C++ builds on an embedded Linux system

---

## Objectives
- Build a C++ application using a Makefile on the PYNQ-Z2
- Accept a delay value from the command line
- Measure elapsed CPU cycles over a specified delay
- Compare hardware cycle counts to a Linux timer
- Understand limitations of low-level timing on Linux user space

---

## Project Structure
clock_example/
├── include/
│ ├── cycletime.h
│ ├── timer.h
│ └── main.h
├── src/
│ └── main.cpp
├── objs/
│ └── *.o
├── Makefile
└── README.md
