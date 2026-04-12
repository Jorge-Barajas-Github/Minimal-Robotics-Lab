# Minimal Robotics Lab

A Python-based project for learning robotics, dynamics, control, optimization, and reinforcement learning through progressively more advanced methods applied to very simple systems.

The goal of this repository is to build intuition first, then deepen understanding by implementing and comparing different techniques on the same small set of models. Instead of jumping straight into complex robots, this project focuses on simple dynamical systems where the mathematics and behavior are easier to understand clearly.

## Project Idea

This repository is designed as a progressive robotics learning lab.

The main idea is:

- keep the **models simple**
- change the **techniques**
- compare how each method behaves

By holding the system mostly fixed and changing the method, it becomes much easier to understand what each robotics or control technique is actually doing.

## Goals

This project aims to help build a deeper understanding of:

- dynamical system modeling
- numerical simulation
- linearization
- classical control
- optimal control
- trajectory optimization
- model predictive control
- reinforcement learning

It is also intended to serve as a professional portfolio project that demonstrates applied robotics and control knowledge in code.

## Planned Systems

The systems in this repository are intentionally simple. Planned examples include:

- 1D point mass
- double integrator
- pendulum
- cart-pole
- simple mobile robot

These systems are simple enough to understand mathematically, but rich enough to demonstrate many important robotics techniques.

## Planned Methods

The same systems will be revisited using increasingly advanced methods, such as:

- open-loop simulation
- proportional / PID-style control
- state feedback control
- linearization
- LQR
- energy shaping
- trajectory optimization
- MPC
- reinforcement learning

## Repository Structure

```text
minimal-robotics-lab/
├── README.md
├── requirements.txt
├── notebooks/
├── src/
│   ├── dynamics/
│   ├── controllers/
│   ├── optimization/
│   ├── simulation/
│   ├── plotting/
│   └── utils/
├── results/
│   ├── figures/
│   └── gifs/
└── tests/
