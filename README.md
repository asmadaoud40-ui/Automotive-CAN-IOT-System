# Automotive CAN & IoT Distributed Embedded System

## Overview

This project aims to design and develop an **automotive-inspired distributed embedded system** based on multiple STM32F407 microcontrollers communicating through a **CAN bus network**.

The objective is to understand how electronic systems inside modern vehicles are structured, where different **Electronic Control Units (ECUs)** are responsible for specific functions and exchange real-time information through an automotive communication network.

The system combines **low-level bare-metal programming**, **FreeRTOS real-time task management**, actuator control, IoT connectivity and data visualization.

---

# System Architecture

The system is composed of three STM32F407-based ECUs connected through a CAN bus, with an ESP32 IoT gateway and a Qt/C++ monitoring application.
