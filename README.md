# KLH-CSE-2026-Team-ProcessMonitor


# Linux Process Monitoring and Control System

## Project Information

**Project Title:** Linux Process Monitoring and Control System

**Course:** Operating Systems and Systems Programming (OSSP)

**Platform:** Linux / Ubuntu

**Programming Language:** C

---

## Team Members

| Name     | ID Number |
| -------- | --------- |
| Bammidi Yashwanth Sai | 2520030036 |
| Dhanvin gupta | 2520030604 |
| Naga Pranadeep | 2520030390 |


---

## Supervisor

**Supervisor Name:** [Harika]

---

## Abstract

The Linux Process Monitoring and Control System is a C-based Linux system programming project designed to monitor and control running processes. The system collects process information from the Linux `/proc` filesystem and displays important details such as Process ID (PID), Parent Process ID (PPID), process state, CPU usage, and memory usage.

The system also provides process control operations using Linux signals, allowing an administrator to stop, continue, and terminate selected processes. It detects processes that exceed predefined CPU or memory limits and records important process and control activities in log files.

The project demonstrates important Operating Systems and Linux system programming concepts including process management, the `/proc` filesystem, signals, system calls, resource monitoring, process control, and logging.

---

## Objectives

* Monitor currently running Linux processes.
* Display PID, PPID, process state, CPU usage, and memory usage.
* Read process information from the Linux `/proc` filesystem.
* Detect processes exceeding predefined resource limits.
* Control processes using Linux signals.
* Support stopping, continuing, and terminating processes.
* Monitor process creation and termination.
* Maintain logs of monitoring and process-control activities.
* Provide a continuously updated monitoring interface.

---

## Technologies Used

* C Programming
* Linux / Ubuntu
* Linux `/proc` Filesystem
* POSIX System Programming
* Linux Signals
* Process Management
* File Handling
* Makefile
* GCC Compiler

---

## Project Structure

```text
Linux-Process-Monitoring-and-Control-System/
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
│   └── Screenshots, outputs and test results
│
└── reports/
    └── Project reports
```

---

## Setup Instructions

### Requirements

* Ubuntu or another Linux-based operating system
* GCC compiler
* Make
* Terminal

### Installation

Clone the repository:

```bash
git clone [PASTE YOUR REPOSITORY URL HERE]
```

Move into the project directory:

```bash
cd [KLH-CSE-2026-Team-ProcessMonitor]
```

Compile the project using the provided Makefile:

```bash
make
```

---

## Execution Instructions

After compilation, run the process monitoring program:

```bash
./process_monitor
```

The program will display information about currently running processes and provide options for monitoring and controlling processes.

---

## Main Features

### 1. Process Monitoring

Displays:

* Process ID (PID)
* Parent Process ID (PPID)
* Process state
* CPU usage
* Memory usage

### 2. Resource Monitoring

The system monitors CPU and memory usage and generates warnings when predefined resource limits are exceeded.

### 3. Process Control

The system allows authorized users to:

* Stop a process
* Continue a stopped process
* Terminate a process

### 4. Process Tracking

The system monitors process creation and termination events.

### 5. Logging

Important monitoring and process-control activities are recorded in log files.

### 6. Continuous Monitoring

The system provides continuously updated process information.

---

## OS Concepts Demonstrated

This project demonstrates the following Operating Systems and Systems Programming concepts:

* Process Management
* Process IDs and Parent Process IDs
* Linux `/proc` Filesystem
* Signals
* Process Control
* System Calls
* File Handling
* Resource Monitoring
* Process Creation and Termination
* Linux/POSIX System Programming

---

## Current Phase Status

**Current Phase:** Phase 1

**Status:** In Progress

### Completed

* Project topic selected
* GitHub repository created
* Project folder structure created
* README created

### In Progress

* Project design
* Process monitoring implementation
* Linux `/proc` integration

### Pending

* Process control
* CPU and memory monitoring
* Resource-limit detection
* Logging
* Testing
* Final documentation
* Final demonstration

---

## Testing and Results

Test cases and experimental results will be added to the `results/` directory as development progresses.

---

## Team Contribution

Each team member will contribute to the project using their own GitHub account. Contributions will be tracked through the GitHub commit history.

---

## Project Status

**Development Status:** In Progress

**Final Version:** To be completed
