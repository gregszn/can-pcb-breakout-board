# CAN PCB Breakout Board

## Overview

This project focuses on the design and implementation of a custom CAN bus breakout board for embedded system communication and prototyping. The board enables reliable CAN communication between microcontrollers and external devices.

## Motivation

Modern embedded systems rely on robust communication protocols like CAN. This project was developed to gain hands-on experience with hardware design, PCB layout, and system-level debugging of communication interfaces.

## System Architecture

The system consists of a microcontroller connected to a CAN transceiver, enabling message transmission over a CAN bus.

* Microcontroller → CAN Controller → CAN Transceiver → CAN Bus

## Hardware Design

* Designed schematic and PCB layout using (KiCad / Altium)
* Integrated CAN transceiver for differential signaling
* Added headers for easy interfacing with development boards
* Included basic protection and filtering components

## Firmware Integration

* Implemented CAN communication (send/receive messages)
* Configured communication parameters (baud rate, message ID)
* Verified communication between nodes

## Debugging & Challenges

* Issue: CAN communication not initializing
  → Fix: Incorrect wiring between controller and transceiver

* Issue: No data observed on bus
  → Fix: Missing termination resistor on CAN lines

* Issue: Unstable signals
  → Fix: Improved grounding and wiring layout

## Results

* Successfully transmitted and received CAN messages
* Verified communication reliability across nodes
* Demonstrated proper bus behavior with termination

## Images

(Add photos of your PCB, setup, or test environment here)

## Future Improvements

* Add ESD protection and improved filtering
* Design a multi-node CAN test setup
* Integrate with automotive-style applications
