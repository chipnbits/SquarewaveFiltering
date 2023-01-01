# SquarewaveFiltering
A novel filtering algorithm for squarewave signals

This repository contains files related to a project to develop a system that can detect and filter 10 kHz squarewave infrared signals, as well as determine their direction of origin.  The purpose of the sensor array was for navigating through a robotics competition course that uses IR beacons with different frequencies using PID control.  The solution incorporates a novel filtering algorithm for squarewave signals, as well as a custom PCB IR Phototransistor Array controlled through a demultiplexer. 

- C___Code.pdf – A C based implementation of a generalized filtering algorithm for square waves of any frequency
- IRDemuxCircuitSchematic.pdf – Circuit diagram for the IR Phototransistor Demux Array
- IRDemuxPCB.png – An image of the PCB layers from the IR Array
- pcb.png - A photo of the manfactured IR array PCB 
- squareWaveAnalysis.mlx – An explanation and analysis of the filtering algorithm developed for the competition, from DFT principles
- squareWaveAnalysis.pdf – PDF copy of the Matlab livescript analysis

A video demonstration of the device can be found by clicking the image below:

[![Video Demonstration](https://img.youtube.com/vi/aBa5nf1EYEI/0.jpg)](https://www.youtube.com/watch?v=aBa5nf1EYEI)
