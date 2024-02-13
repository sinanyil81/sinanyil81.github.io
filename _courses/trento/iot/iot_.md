# Embedded Software for the Internet of Things
**Instructor:** Dr. Kasım Sinan Yıldırım  

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
The objective of the course is to expose students to languages, operating systems and, in general, programming techniques geared towards Internet of Things (IoT) applications. These applications run on devices that are often embedded in the environment (e.g., to operate sensors and/or actuators) therefore requiring modes of interaction significantly different from traditional, user-driven applications. Further, these devices are usually small, battery-powered, and constrained in terms of computation and communication resources, therefore posing peculiar system-level challenges. The course will provide a general context on IoT applications before delving in the illustration of paradigmatic approaches to IoT programming. Some of the latter will be further explored hands-on in laboratory sessions, where students will have the opportunity to build their own applications using real IoT hardware.

## Lectures

### Introduction to Embedded Software [Weeks 1--3]

- [Week 1: Introduction](.) 
  - Application Examples, Platforms, Programming Languages, Operating Systems...
  - ARM Cortex Processors and TI MSP432 microcontroller
- [Week 2-3: Embedded Software Basics](.)
  - Embedded systems initialization and boot sequence
  - Assemblers, linkers, compilers (GCC), debuggers (GDB), programming interfaces (JTAG...) 
  - Target binary, memory map and symbol table
  - Creating libraries and linking, Makefiles
  - TI Code Composer Studio (CSS) and integrated development environment
  - C Programming Review: Pointers, function pointers, finite state machines, data types and casting
  - ARM Assembly Review: Registers, basic Instructions, bit and memory manipulation
  - Components for embedded programs: state machines, circular buffers, queues
  
### Bare Metal Programming [Weeks 4--7]

- [Week 4-5: Microcontroller and Sensor Interfacing](.)
  - Ports and I/O  
  - Polling/Interrupt Management
  - Timers and timer services
  - ADC/DAC, DMA 
  - Dynamic memory management
  - Serial Communication (UART), SPI, I2C   
  - Reading temperature and reading accelerometer data
- [Week 6: Sensor data processing](.)  
  - Noise, filtering and smoothing, FFT
  - Activity recognition via accelerometers/gyroscopes 
  - ECG (electrocardiogram) sensing and interpretation
  - Image processing (via CNN) with low-resolution cameras
- [Week 7: Communication](.)    
  - Wireless communication via low-power modules
  - BLE, Zigbee using Smarthphone
  - * Kalman and Bayesian Filtering
  - * RSSI Localization 
  
### IoT Software Design and Testing [Week 8--12]

- [Week 8-9: Embedded Operating Systems](.)
  - Tasks and threads
  - OS services and preemptive/non-preemptive scheduling
  - Real-time concepts and scheduling
  - Concurrency management
  - FreeRTOS API 
  - Other operating systems: Contiki, TinyOS, ARM MBed OS
- [Week 10: Code optimization, Testing and Debugging](.)  
  - Premature optimization is evil: functional and non-functional requirements
  - Tools: testing, coverage and handling memory bugs
  - Performance analysis and optimization
  - Energy and power analysis and optimization
  - Analysis and optimization of program code size
  - Program validation and testing
- [Week 11-12: Systems Design and Development](.)
  - Hardware/Software co-design
  - Modular design: partitioning software, mapping to hardware
  - Code formatting, interface design, naming conventions
  - hardware-independent code vs hardware dependent code, cohesion
  - Embedded software design patterns

  
## Laboratories

We will use ARM-based [TI MSP432 Launchpad](http://www.ti.com/tool/MSP-EXP432P401R?DCMP=ep-mcu-msp-432-en&HQS=beginmsp432launchpad#1); a state-of-the-art embedded system development kit that features a low-power and high performance micro-controller of modern IoT applications.

### Project Assignments
