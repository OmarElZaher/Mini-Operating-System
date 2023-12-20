## Project Objective

The primary goal of this project is to deepen my understanding of Operating Systems by constructing a simulation. Emphasis is placed on architecting a system that mirrors real-world OS functionalities.

---

## Description

The interpreter will read program files (representing processes) from text files and execute their respective code. The system encompasses:

- Memory management
- Process control
- System calls
- Mutexes for resource management
- Round Robin scheduling algorithm for process execution

---

## System Calls

Processes communicate with the OS via system calls. My implementation supports:

1. Reading from disk
2. Writing to disk
3. Printing to screen
4. User text input
5. Memory read and write operations

---

## Memory Management

- Memory size: 40 memory words.
- Memory segments allocated for code lines, variables, and PCBs.
- Processes are allocated space upon arrival.
- Memory management includes offloading processes to disk when memory is insufficient and reloading them when necessary.

---

## Process Control Block (PCB)

Each process is associated with a PCB containing:

1. Process ID
2. Process State
3. Program Counter
4. Memory Boundaries

---

## Programs

Three primary programs include functionalities such as:

1. Printing numbers between given ranges.
2. Writing data to files.
3. Displaying file contents on the screen.

---

## Program Syntax

Instructions include:

- Print
- Assign
- writeFile
- readFile
- printFromTo
- semWait
- semSignal

---

## Mutual Exclusion (Mutexes)

Three mutexes to manage:

1. File access
2. User input
3. Screen output

---

## Scheduler

Implementing the Round Robin algorithm for process scheduling, each process gets a fixed time slice for execution.

---

## Queues

- Ready Queue: Processes ready for execution.
- Blocked Queue: Processes awaiting resource availability.

---
