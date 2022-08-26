# 2022 Spring

## JTAG Interface with Boundary Scan Register

The IEEE std.1149.1 is also known as boundary scan, since it mainly consists of a scan register on the ports of a component for testing its interconnects and core logic. 

I wrote JTAG interface with Boundary Scan Register with SystemVerilog and verified using cocotb python verification framework, then create their assertions

![jtag](jtag.png)

## ASIC Implementation of Local Feature Detector in ORB-SLAM3

Image feature extraction and matching is a fundamental but computation intensivetask in machine vision. This project implements FAST feature point detection and BRIEF feature descriptor construction and matching.

The function of our design include FAST feature extraction and BRIEF feature matching.

 I am responsible for all content of FAST feature extraction.

Here is the result, the red point is feature point found by software and the blue point is the feature point found by hardware.

<img src="capstone/fast.jpeg" alt="fast" style="zoom:50%;" />

## Drowning Detection System Based on Yolo v5s

In 2019, an estimated 236,000 people died from drowning, making drowning a major global public health problem[1]. In the same year, drowning accounted for nearly 8% of global deaths. An efficient and responsive drowning detection system can effectively prevent the loss of life and property of swimmers. Based on a video database of swimmers in a pool, we build a deep learning-based object detection and classification system to judge whether an object in the camera is drowning.

![yolov5](yolov5.png)



## Course Project in Computer Architecture II

This course focus on computer architecture, and the assignment is using python to emulate hardware 

HW 2: Mystery Branch Predictor

HW3: ILP Scheduler

HW4: Mystery Caches

# 2022 Winter

## Simulation & Synthesis of IBEX RISC-V Core

Ibex is a production-quality open source 32-bit RISC-V CPU core written in SystemVerilog. The CPU core is heavily parametrizable and well suited for embedded control applications. Ibex is being extensively verified and has seen multiple tape-outs.

I performed floor-planning, placing and routing using , IC Compiler II, to generate a production-quality GDSII file,

We did synthesis for a range of clk periods both the dynamic power and the area decreases as the clk period increases From where the clk period is about 7 to 8 ns, the change becomes neglectable but to consider the performance, we decided to use the 7 ns as our clk period.  when the clk freq increases it will harm the performance

<img src="ibex.png" alt="ibex" style="zoom: 33%;" />

## A Brief Introduction of Digital Machine Learning Accelerator Design

In this course, I read 

[back](/)