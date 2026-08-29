# Flight Simulator Control & Monitoring System

## Project Information

**Project Title:** Flight Simulator Control & Monitoring System

**Course:** Operating Systems and Systems Programming (OSSP)

**Programming Language:** C

**Platform:** Linux / Ubuntu

---

## Team Members

| Name | ID Number |
|---|---|
| Bammidi Yashwanth Sai | 2520030036 |
| Dhanvin Gupta | 2520030604 |
| Naga Pranadeep | 2520030390 |

---

## Supervisor

**Supervisor Name:** Harika

---

## Abstract

The Flight Simulator Control & Monitoring System is a Linux-based C application that simulates important flight control and monitoring operations using Operating System concepts.

The system consists of multiple simulated components such as altitude monitoring, speed monitoring, engine monitoring, and navigation. These components communicate with a central flight controller using Linux inter-process communication mechanisms such as pipes and FIFOs.

The system uses signals to handle important flight events and emergency conditions. Shared memory and synchronization mechanisms are used where required for communication and coordination between processes. The system also maintains logs of important flight events and system activities.

The project demonstrates important Operating Systems and Linux system programming concepts including process creation, inter-process communication, pipes, FIFOs, signals, shared memory, synchronization, dynamic memory management, and process monitoring.

---

## Objectives

- Simulate important flight control and monitoring operations.
- Monitor simulated altitude, speed, engine, and navigation data.
- Implement communication between different processes.
- Use pipes and FIFOs for inter-process communication.
- Use signals to handle emergency and abnormal flight conditions.
- Implement synchronization between processes.
- Monitor process status and system activity.
- Maintain logs of important flight events.
- Provide a controlled Linux-based flight simulation environment.

---

## Technologies Used

- C Programming
- Linux / Ubuntu
- GCC Compiler
- POSIX System Programming
- Processes
- Pipes
- FIFOs
- Signals
- Shared Memory
- Synchronization
- Dynamic Memory Allocation
- File Handling
- Makefile

---

## Project Structure

```text
Flight-Simulator-Control-and-Monitoring-System/
│
├── README.md
│
├── src/
│   └── Source code
│
├── docs/
│   └── Project documentation
│
├── data/
│   └── Data source information
│
├── results/
│   └── Screenshots and test results
│
└── reports/
    └── Project reports
