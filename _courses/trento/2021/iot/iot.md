---
layout: page
permalink: /courses/trento/2021/iot/
title: Embedded Software for the Internet of Things
nav: false
horizontal: false
---

###  Fall 2021 University of Trento
**Instructor:** Dr. Kasım Sinan Yıldırım  

<span style="color:red">All students are required to enrol on the course website:</span> [Embedded Software for the Internet of Things](https://didatticaonline.unitn.it/dol/enrol/index.php?id=22948)


## Textbook

The following book will serve as the core text:
- [Computers as Components: Principles of Embedded Computing System Design, 4th Edition](https://www.elsevier.com/books/computers-as-components/wolf/978-0-12-805387-4), Marilyn Wolf, Morgan Kaufmann  

The following (supporting) books build up a nice literature on embedded systems. 
- [Embedded System Interfacing: Design for the Internet-of-Things (IoT) and Cyber-Physical Systems (CPS)](https://www.elsevier.com/books/embedded-system-interfacing/wolf/978-0-12-817402-9), Marilyn Wolf, Morgan Kaufmann  
- [Embedded Systems: A Contemporary Design Tool, 2nd Edition](https://www.wiley.com/en-it/Embedded+Systems:+A+Contemporary+Design+Tool,+2nd+Edition-p-9781119457558), James K. Peckol, Wiley
- [An Embedded Software Primer 1st Edition by David E. Simon](https://www.amazon.com/Embedded-Software-Primer-David-Simon/dp/020161569X)
- [Real-time Concepts for Embedded Systems](https://www.crcpress.com/Real-Time-Concepts-for-Embedded-Systems/Li-Yao/p/book/9781578201242), Qing Li, CRC Press
- [Programming Embedded Systems, 2nd Edition](https://proquest.safaribooksonline.com/book/programming/0596009836), Michael Barr, Anthony Massa 

## Objectives
Contemporary Internet of Things (IoT) systems comprise embedded computing devices that enable perceiving information about anything, at any time and from anywhere. These devices are interconnected, often embedded in the environment, small in size, battery-powered, and constrained in terms of computation and communication resources. These properties pose peculiar system-level challenges to develop IoT applications.

The objective of this course is to expose students to programming languages, hardware platforms, operating systems, and, in general, the necessary software tools and techniques geared towards the development of IoT applications. By the end of this course, the students are expected to acquire the theoretical and practical skills to interface with state-of-the-art embedded computing platforms. They will be equipped with the fundamentals to design and develop IoT applications, including, but not limited to, electrocardiogram sensing and interpretation, image processing with low-resolution cameras, machine learning on the edge, wireless localization, and many more.

Upon successful completion of this module, students should be able to:
- Characterize the main architectural components of microcontroller-based IoT platforms
- Use the development environments and toolchains to program and debug microcontrollers
- Design, implement and test embedded software by following the fundamental methodologies for IoT systems
- Assess IoT application performance and understand the techniques used for optimizing systems execution
- Characterize the basics of real-time scheduling and the main components of embedded real-time operating systems

## Lectures

An Introduction to Embedded Computing
- Embedded Computing and the Internet of Things
- Microprocessor-based Application Examples
- Embedded Systems Design Process

Embedded Computing Platforms
- Computer Architecture Review
- CPUs and Instruction Sets
- ARM Processor Architecture
- Embedded Platform Hardware and Software
- Development Environments, Debugging
I/O, Interrupts, Memory System, Performance, Power Management

Embedded Software Design
- Basic program elements
- State machines, basic data structures, circular buffers, queues
- Code generation
- Assembly, linking, object code, memory map, symbol table, creating libraries and linking, Makefiles
- Compiler optimizations, performance analysis, power analysis
- Validation and testing

Embedded Operating Systems
- Tasks, processes, scheduling
- Interprocess communication
- Real-time operating systems
- deadlines, priorities, priority inversion

Internet-of-Things Systems
- Applications, architectures
- Network protocols
- Bluetooth and Bluetooth Low Energy, ZigBee, Wi-Fi

In the meantime, some lectures will be dedicated to the following hands-on activities:

Software Tools for Texas Instruments IoT platform
- Code Composer IDE for code development
- MSP-EXP432P401R SimpleLink MSP432 LaunchPad
- BOOSTXL-EDUMKII Educational BoosterPack
- CC3100 BoosterPack

Bare Metal Programming
- C programming for Embedded Systems
- Microcontroller Interfacing
- Ports and I/O
- Polling/Interrupt Management
- Timers and timer services
- ADC/DAC, DMA
- Serial Communication (UART), SPI, I2C
- Reading sensor data
- Application examples
- Sensor data processing
- Noise, filtering and smoothing, FFT
- Activity recognition via accelerometers/gyroscopes

Programming using an RTOS
- Introduction to FreeRTOS API
- Code and application examples

  
## Laboratories

We will use ARM-based [TI MSP432 Launchpad](http://www.ti.com/tool/MSP-EXP432P401R?DCMP=ep-mcu-msp-432-en&HQS=beginmsp432launchpad#1); a state-of-the-art embedded system development kit that features a low-power and high performance micro-controller of modern IoT applications.
