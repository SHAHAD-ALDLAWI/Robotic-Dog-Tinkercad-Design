# Basic Robotic Dog Mechanical Design

## Overview
This repository contains the initial 3D mechanical design of a simple robotic dog, created using Tinkercad. The objective of this project is to demonstrate the fundamental mechanical principles required for a quadruped robot to stand and walk.

## Mechanical Specifications

* **Body and Frame:** A rectangular, flat chassis designed to distribute weight evenly and simplify the overall structure.
* **Leg Design:** Straight legs consisting of two links (thigh and calf) to facilitate basic locomotion.
* **Joints and Degrees of Freedom (DOF):** The robot features 8 primary joints (2 per leg: hip and knee). Each joint provides 1 DOF, resulting in a total of 8 DOF.
* **Motor Selection:** MG996R Servo Motors are proposed due to their affordability, ease of programming, and sufficient torque for lightweight robots.
* **Estimated Joint Torque:** 
  - Assuming a total robot weight of W = 2 kg and a thigh link length of L = 0.1 m:
  - Force needed to stand: F = m × g = 2 × 9.81 ≈ 20 N
  - Required hip joint torque: T = F × L = 20 × 0.1 = 2 N.m
  - *(A servo motor providing around 20 kg.cm of torque is highly adequate).*
* **Stability and Center of Gravity:** The Center of Gravity (CoG) is positioned exactly in the middle of the rectangular chassis to prevent tipping over while standing.
* **Proposed Gait:** Creep Gait. The robot lifts and moves only one leg at a time, ensuring it is always supported by 3 legs for maximum stability.
* **Expected Mechanical Issues:**
  1. Potential slipping of the leg tips on smooth surfaces (can be mitigated by adding rubber feet).
  2. Motor overheating if the structural weight exceeds the servos' optimal load capacity.

## Design Screenshots

![Front View](image1.png)
![Side View](image2.png)
![Top View](image3.png)

## Files Included
* 3D Model file (`.stl` or `.obj`) exported from Tinkercad.
* Screenshots of the 3D design from different angles.
