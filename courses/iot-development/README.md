- [Introduction to Internet of Things](#introduction-to-internet-of-things)
  - [What is the Internet of Things](#what-is-the-internet-of-things)
    - [Understanding the Internet of Things](#understanding-the-internet-of-things)
    - [Smart Things & Connected Things](#smart-things--connected-things)
    - [IoT Verticals](#iot-verticals)
  - [Prototype: Build an IoT Prototype](#prototype-build-an-iot-prototype)
  - [Architecture of IoT Solutions](#architecture-of-iot-solutions)
  - [Is IoT already here](#is-iot-already-here)
    - [Trending IoT Products](#trending-iot-products)
    - [How big is IoT?](#how-big-is-iot)
    - [IoT Ecosystem](#iot-ecosystem)
- [Understanding an IoT Device](#understanding-an-iot-device)
  - [IoT Product Teardown](#iot-product-teardown)
  - [Overview of building blocks](#overview-of-building-blocks)
  - [Sensors and Actuators](#sensors-and-actuators)
  - [Mixed signal interfaces](#mixed-signal-interfaces)
  - [Computation](#computation)
  - [Wireless connectivity](#wireless-connectivity)
    - [Power management](#power-management)
    - [Embedded software](#embedded-software)
  - [IoT Product Lifecycle](#iot-product-lifecycle)
    - [Problem Research](#problem-research)
    - [Proof-of-Concept](#proof-of-concept)
    - [Engineering](#engineering)
      - [Looks-like prototype](#looks-like-prototype)
      - [Works-like prototype](#works-like-prototype)
    - [Validation](#validation)
    - [Mass Production](#mass-production)
- [Getting Started with Prototyping](#getting-started-with-prototyping)
  - [IoT Hardware Development Platforms](#iot-hardware-development-platforms)
    - [Can microcontrollers fuel rapid prototyping?](#can-microcontrollers-fuel-rapid-prototyping)
    - [What is a DevBoard?](#what-is-a-devboard)
    - [The world of Arduino Dev Platform](#the-world-of-arduino-dev-platform)
    - [Wireless Dev Boards](#wireless-dev-boards)
    - [Single Board Computers](#single-board-computers)
    - [Hardware specifications](#hardware-specifications)
  - [IoT Software Development Platforms](#iot-software-development-platforms)
    - [Overview](#overview)
    - [Arduino IDE](#arduino-ide)
    - [Embedded Programming Platforms](#embedded-programming-platforms)
    - [Embedded Operating Systems](#embedded-operating-systems)
  - [Hello to IoT world](#hello-to-iot-world)
    - [Overview](#overview-1)
    - [Interfacing hardware](#interfacing-hardware)
    - [Basics of Arduino Programming](#basics-of-arduino-programming)
    - [Controlling LED output](#controlling-led-output)
    - [Blinking an LED](#blinking-an-led)
    - [Reading GPIO inputs](#reading-gpio-inputs)
    - [Working with serial library](#working-with-serial-library)
  - [Hello to sensors](#hello-to-sensors)
    - [Overview](#overview-2)
    - [Play with smartphone sensors](#play-with-smartphone-sensors)
    - [Interfacing a Temperature and Humidity sensor](#interfacing-a-temperature-and-humidity-sensor)
    - [Reading sensor data](#reading-sensor-data)
  - [Hello to actuators](#hello-to-actuators)
    - [Overview](#overview-3)
    - [Interfacing Servo Motor](#interfacing-servo-motor)
    - [Run the Servo Motor](#run-the-servo-motor)
  - [Deep Dive into Sensors](#deep-dive-into-sensors)
    - [Overview](#overview-4)
    - [Identify a sensor](#identify-a-sensor)
    - [Qualify a sensor](#qualify-a-sensor)
    - [Integrate a sensor](#integrate-a-sensor)
    - [Read sensor data](#read-sensor-data)
    - [Evaluate a sensor](#evaluate-a-sensor)
  - [Deep Dive into Actuators](#deep-dive-into-actuators)
    - [Overview of Actuators](#overview-of-actuators)
    - [Integrate an actuator](#integrate-an-actuator)
    - [Evaluate an actuator](#evaluate-an-actuator)
  - [Hardware Interfaces](#hardware-interfaces)
    - [I2C](#i2c)
    - [SPI](#spi)
    - [1-wire](#1-wire)
    - [UART](#uart)
    - [MODBUS](#modbus)
    - [DALI](#dali)
- [Going Wireless](#going-wireless)
  - [Connectivity in IoT](#connectivity-in-iot)
    - [Overview](#overview-5)
    - [Communication Technologies for IoT](#communication-technologies-for-iot)
  - [Add Wi-Fi Connectivity](#add-wi-fi-connectivity)
    - [Overview](#overview-6)
    - [Client-Server Communication](#client-server-communication)
    - [Install firmware packages](#install-firmware-packages)
    - [Connect to a Wi-Fi Network](#connect-to-a-wi-fi-network)
    - [Find the IP address of the device](#find-the-ip-address-of-the-device)
    - [Configure a client](#configure-a-client)
    - [Host a server](#host-a-server)
  - [Add BLE Connectivity](#add-ble-connectivity)
    - [Fundamentals of Bluetooth](#fundamentals-of-bluetooth)
    - [Master-slave communication](#master-slave-communication)
    - [Interfacing bluetooth communication module](#interfacing-bluetooth-communication-module)
    - [Configuration of bluetooth communication module](#configuration-of-bluetooth-communication-module)
    - [Establish serial communication](#establish-serial-communication)
- [Leveraging IoT Platforms](#leveraging-iot-platforms)
  - [The Concept of IoT platforms](#the-concept-of-iot-platforms)
    - [Overview](#overview-7)
    - [IoT platform technology stack](#iot-platform-technology-stack)
    - [Remote management](#remote-management)
    - [Data Visualization](#data-visualization)
    - [Device management](#device-management)
    - [Identity Management](#identity-management)
    - [Configuration Management](#configuration-management)
    - [Software Updates (OTA)](#software-updates-ota)
    - [Rule Engine](#rule-engine)
    - [Control Widgets](#control-widgets)
    - [Analytics](#analytics)
    - [Drag and Drop app development](#drag-and-drop-app-development)
  - [Trending platforms in the market](#trending-platforms-in-the-market)
  - [Develop an IoT solution: Mood Light](#develop-an-iot-solution-mood-light)
    - [Overview](#overview-8)
    - [Integrate the hardware](#integrate-the-hardware)
    - [Develop and IoT app](#develop-and-iot-app)
    - [Program the hardware](#program-the-hardware)
    - [Remotly manage and control the hardware](#remotly-manage-and-control-the-hardware)
  - [Develop an IoT solution: Smart Socket](#develop-an-iot-solution-smart-socket)
    - [Overview](#overview-9)
    - [Integrate the hardware](#integrate-the-hardware-1)
    - [Develop and IoT app](#develop-and-iot-app-1)
    - [Program the hardware](#program-the-hardware-1)
    - [Control the socket](#control-the-socket)
    - [Monitor sensor data](#monitor-sensor-data)
  - [Develop an IoT solution: Asset Tracker](#develop-an-iot-solution-asset-tracker)
    - [Overview](#overview-10)
    - [Condition Monitoring of an Asset](#condition-monitoring-of-an-asset)
    - [Track location](#track-location)
    - [Integrate services using NodeRed](#integrate-services-using-nodered)
    - [Develop a real-time IoT Dashboard](#develop-a-real-time-iot-dashboard)
    - [Program the hardware](#program-the-hardware-2)
    - [Monitor Events](#monitor-events)
    - [Trigger Alerts](#trigger-alerts)
- [Data Modeling and Processing](#data-modeling-and-processing)
  - [IoT Protocols](#iot-protocols)
    - [Overview](#overview-11)
    - [HyperText Transfer Protocol (HTTP)](#hypertext-transfer-protocol-http)
    - [Message Queue Telemetry Transport (MQTT)](#message-queue-telemetry-transport-mqtt)
    - [Constrained Application Protocol (CoAP)](#constrained-application-protocol-coap)
    - [Advanced Message Queuing Protocol (AMQP)](#advanced-message-queuing-protocol-amqp)
    - [Comparison of IoT Protocols](#comparison-of-iot-protocols)
  - [Data Modeling using HTTP](#data-modeling-using-http)
    - [Overview](#overview-12)
    - [HTTP Clients](#http-clients)
    - [HTTP Server](#http-server)
    - [Request Response Model](#request-response-model)
    - [Client - Server communication](#client---server-communication)
  - [Data Modeling using MQTT](#data-modeling-using-mqtt)
    - [Overview](#overview-13)
    - [MQTT Clients](#mqtt-clients)
    - [MQTT Brokers](#mqtt-brokers)
    - [PubSub Model](#pubsub-model)
    - [Clients - Broker communication](#clients---broker-communication)
  - [Develop an IoT Solution: COVID-19 Automated Occupancy Monitoring](#develop-an-iot-solution-covid-19-automated-occupancy-monitoring)
- [Architecting IoT Solutions](#architecting-iot-solutions)
  - [How to architect an IoT Solution?](#how-to-architect-an-iot-solution)
  - [Activity: Budding Architect](#activity-budding-architect)
  - [Essence of IoT Edge](#essence-of-iot-edge)
- [Developing IoT Edge Solutions](#developing-iot-edge-solutions)
  - [Getting Started with Raspberry Pi](#getting-started-with-raspberry-pi)
    - [Setting up Operating System on Pi](#setting-up-operating-system-on-pi)
    - [Pi as your personal computer](#pi-as-your-personal-computer)
    - [Adding and using software](#adding-and-using-software)
    - [Interfacing hardware to Pi](#interfacing-hardware-to-pi)
    - [Coding with Pi](#coding-with-pi)
    - [Remote access and security](#remote-access-and-security)
  - [Gesture controlled Robot buggy](#gesture-controlled-robot-buggy)
    - [Overview](#overview-14)
    - [Physical Computing using Python](#physical-computing-using-python)
    - [Working with GPIOs using Python library](#working-with-gpios-using-python-library)
    - [Interact with input and output components](#interact-with-input-and-output-components)
    - [Obstacle avoidance algorithms](#obstacle-avoidance-algorithms)
    - [Gesture control algorithms](#gesture-control-algorithms)
  - [IoT Edge](#iot-edge)
    - [Overview](#overview-15)
    - [Deploy code to a Linux device](#deploy-code-to-a-linux-device)
    - [Develop custom code modules](#develop-custom-code-modules)
    - [Machine Learning at the Edge](#machine-learning-at-the-edge)
    - [IoT Edge device as a Gateway](#iot-edge-device-as-a-gateway)
    - [Production Deployment Checklist](#production-deployment-checklist)
    - [Manage with DevOps Tools](#manage-with-devops-tools)

# Introduction to Internet of Things

## What is the Internet of Things

### Understanding the Internet of Things

### Smart Things & Connected Things

### IoT Verticals

## Prototype: Build an IoT Prototype

## Architecture of IoT Solutions

## Is IoT already here

### Trending IoT Products

### How big is IoT?

### IoT Ecosystem

# Understanding an IoT Device

## IoT Product Teardown

## Overview of building blocks

## Sensors and Actuators

## Mixed signal interfaces

## Computation

## Wireless connectivity

### Power management

### Embedded software

## IoT Product Lifecycle

### Problem Research

### Proof-of-Concept

### Engineering

#### Looks-like prototype

#### Works-like prototype

### Validation

### Mass Production

# Getting Started with Prototyping

## IoT Hardware Development Platforms

### Can microcontrollers fuel rapid prototyping?

### What is a DevBoard?

### The world of Arduino Dev Platform

### Wireless Dev Boards

### Single Board Computers

### Hardware specifications

## IoT Software Development Platforms

### Overview

### Arduino IDE

### Embedded Programming Platforms

### Embedded Operating Systems

## Hello to IoT world

### Overview

### Interfacing hardware

### Basics of Arduino Programming

### Controlling LED output

### Blinking an LED

### Reading GPIO inputs

### Working with serial library

## Hello to sensors

### Overview

### Play with smartphone sensors

### Interfacing a Temperature and Humidity sensor

### Reading sensor data

## Hello to actuators

### Overview

### Interfacing Servo Motor

### Run the Servo Motor

## Deep Dive into Sensors

### Overview

### Identify a sensor

### Qualify a sensor

### Integrate a sensor

### Read sensor data

### Evaluate a sensor

## Deep Dive into Actuators

### Overview of Actuators

### Integrate an actuator

### Evaluate an actuator

## Hardware Interfaces

### I2C

### SPI

### 1-wire

### UART

### MODBUS

### DALI

# Going Wireless

## Connectivity in IoT

### Overview

### Communication Technologies for IoT

## Add Wi-Fi Connectivity

### Overview

### Client-Server Communication

### Install firmware packages

### Connect to a Wi-Fi Network

### Find the IP address of the device

### Configure a client

### Host a server

## Add BLE Connectivity

### Fundamentals of Bluetooth

### Master-slave communication

### Interfacing bluetooth communication module

### Configuration of bluetooth communication module

### Establish serial communication

# Leveraging IoT Platforms

## The Concept of IoT platforms

### Overview

### IoT platform technology stack

### Remote management

### Data Visualization

### Device management

### Identity Management

### Configuration Management

### Software Updates (OTA)

### Rule Engine

### Control Widgets

### Analytics

### Drag and Drop app development

## Trending platforms in the market

## Develop an IoT solution: Mood Light

### Overview

### Integrate the hardware

### Develop and IoT app

### Program the hardware

### Remotly manage and control the hardware

## Develop an IoT solution: Smart Socket

### Overview

### Integrate the hardware

### Develop and IoT app

### Program the hardware

### Control the socket

### Monitor sensor data

## Develop an IoT solution: Asset Tracker

### Overview

### Condition Monitoring of an Asset

### Track location

### Integrate services using NodeRed

### Develop a real-time IoT Dashboard

### Program the hardware

### Monitor Events

### Trigger Alerts

# Data Modeling and Processing

## IoT Protocols

### Overview

### HyperText Transfer Protocol (HTTP)

### Message Queue Telemetry Transport (MQTT)

### Constrained Application Protocol (CoAP)

### Advanced Message Queuing Protocol (AMQP)

### Comparison of IoT Protocols

## Data Modeling using HTTP

### Overview

### HTTP Clients

### HTTP Server

### Request Response Model

### Client - Server communication

## Data Modeling using MQTT

### Overview

### MQTT Clients

### MQTT Brokers

### PubSub Model

### Clients - Broker communication

## Develop an IoT Solution: COVID-19 Automated Occupancy Monitoring

# Architecting IoT Solutions

## How to architect an IoT Solution?

## Activity: Budding Architect

## Essence of IoT Edge

# Developing IoT Edge Solutions

## Getting Started with Raspberry Pi

### Setting up Operating System on Pi

### Pi as your personal computer

### Adding and using software

### Interfacing hardware to Pi

### Coding with Pi

### Remote access and security

## Gesture controlled Robot buggy

### Overview

### Physical Computing using Python

### Working with GPIOs using Python library

### Interact with input and output components

### Obstacle avoidance algorithms

### Gesture control algorithms

## IoT Edge

### Overview

### Deploy code to a Linux device

### Develop custom code modules

### Machine Learning at the Edge

### IoT Edge device as a Gateway

### Production Deployment Checklist

### Manage with DevOps Tools
