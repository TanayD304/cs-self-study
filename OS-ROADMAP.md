# Operating Systems Roadmap (Interview Focused)

> Primary Resource: TakeUForward (TUF+) Operating Systems
> Goal: SDE Interviews (Google, Amazon, Microsoft, Meta, Uber, Atlassian, etc.)

---

# Legend

✅ Covered in TUF+

➕ Additional (Important)

⭐ Must Know

💡 Good to Know

🔹 Optional / Advanced

---

# Phase 1 — Operating System Foundations ⭐⭐⭐

## OS Basics

- [ ] ✅⭐⭐⭐ What is an Operating System?
- [ ] ✅⭐⭐⭐ Why Operating Systems Exist
- [ ] ✅⭐⭐⭐ Functions of an Operating System
- [ ] ✅⭐⭐⭐ Types of Operating Systems
- [ ] ✅⭐⭐ Batch Operating System
- [ ] ✅⭐⭐ Multiprogramming
- [ ] ✅⭐⭐ Multitasking
- [ ] ✅⭐⭐ Multiprocessing
- [ ] ✅⭐ Distributed Operating Systems
- [ ] ✅⭐ Clustered Operating Systems
- [ ] ✅⭐ Embedded Operating Systems
- [ ] ✅⭐⭐ Program vs Process vs Thread

---

## ➕ Additional

- [ ] ➕⭐⭐ User Space vs Kernel Space
- [ ] ➕⭐⭐ Monolithic Kernel vs Microkernel
- [ ] ➕⭐ Hybrid Kernel
- [ ] ➕⭐ Kernel Responsibilities

---

# Phase 2 — Process Management ⭐⭐⭐⭐⭐

## Process Basics

- [ ] ✅⭐⭐⭐ Process
- [ ] ✅⭐⭐⭐ Process States
- [ ] ✅⭐⭐⭐ Process State Diagram
- [ ] ✅⭐⭐⭐ Process Control Block (PCB)
- [ ] ✅⭐⭐⭐ Context Switching
- [ ] ✅⭐⭐⭐ User Mode vs Kernel Mode

---

## Scheduling

- [ ] ✅⭐⭐⭐ Scheduling Queues
- [ ] ✅⭐⭐⭐ Long-Term Scheduler
- [ ] ✅⭐⭐⭐ Medium-Term Scheduler
- [ ] ✅⭐⭐⭐ Short-Term Scheduler

---

## Scheduling Algorithms

- [ ] ✅⭐⭐⭐ FCFS
- [ ] ✅⭐⭐⭐ SJF
- [ ] ✅⭐⭐⭐ SRTF
- [ ] ✅⭐⭐ HRRN
- [ ] ✅⭐⭐ Round Robin
- [ ] ✅⭐⭐ Priority Scheduling
- [ ] ✅⭐⭐ Multilevel Queue

---

## Threads

- [ ] ✅⭐⭐⭐ Threads
- [ ] ✅⭐⭐⭐ User-Level Threads
- [ ] ✅⭐⭐⭐ Kernel-Level Threads
- [ ] ✅⭐⭐⭐ Multithreading Models

---

## ➕ Important Additions

### Process Creation

- [ ] ➕⭐⭐⭐ fork()
- [ ] ➕⭐⭐⭐ exec()
- [ ] ➕⭐⭐⭐ wait()
- [ ] ➕⭐⭐ waitpid()

### Linux Process Concepts

- [ ] ➕⭐⭐⭐ Zombie Process
- [ ] ➕⭐⭐⭐ Orphan Process
- [ ] ➕⭐⭐⭐ Copy-on-Write (COW)

### Scheduling Metrics

- [ ] ➕⭐⭐⭐ Turnaround Time
- [ ] ➕⭐⭐⭐ Waiting Time
- [ ] ➕⭐⭐⭐ Response Time
- [ ] ➕⭐⭐ Throughput
- [ ] ➕⭐⭐ CPU Utilization

---

# Phase 3 — Synchronization & Concurrency ⭐⭐⭐⭐⭐

## Basics

- [ ] ✅⭐⭐⭐ Synchronization
- [ ] ✅⭐⭐⭐ Critical Section Problem
- [ ] ✅⭐⭐⭐ Semaphores
- [ ] ✅⭐⭐⭐ Binary Semaphore
- [ ] ✅⭐⭐⭐ Counting Semaphore

---

## Problems

- [ ] ✅⭐⭐⭐ Producer Consumer
- [ ] ✅⭐⭐⭐ Deadlocks
- [ ] ✅⭐⭐⭐ Banker's Algorithm
- [ ] ✅⭐⭐ Starvation
- [ ] ✅⭐⭐ Aging

---

## ➕ Important Additions

### Locks

- [ ] ➕⭐⭐⭐ Mutex
- [ ] ➕⭐⭐⭐ Mutex vs Semaphore
- [ ] ➕⭐⭐ Spinlock
- [ ] ➕⭐⭐ Spinlock vs Mutex
- [ ] ➕⭐⭐ Condition Variables

### Classical Problems

- [ ] ➕⭐⭐⭐ Readers-Writers Problem
- [ ] ➕⭐⭐ Dining Philosophers
- [ ] ➕⭐ Sleeping Barber

### Advanced

- [ ] ➕⭐⭐ Race Conditions
- [ ] ➕⭐⭐ Atomic Operations

---

# Phase 4 — Memory Management ⭐⭐⭐⭐⭐

## Allocation

- [ ] ✅⭐⭐ First Fit
- [ ] ✅⭐⭐ Best Fit
- [ ] ✅⭐⭐ Worst Fit

---

## Memory Organization

- [ ] ✅⭐⭐⭐ Contiguous Allocation
- [ ] ✅⭐⭐⭐ Paging
- [ ] ✅⭐⭐⭐ Segmentation
- [ ] ✅⭐⭐⭐ Virtual Memory

---

## Page Replacement

- [ ] ✅⭐⭐⭐ FIFO
- [ ] ✅⭐⭐⭐ LRU
- [ ] ✅⭐⭐⭐ Optimal

---

## Concepts

- [ ] ✅⭐⭐⭐ Page Fault
- [ ] ✅⭐⭐ Belady's Anomaly
- [ ] ✅⭐⭐ Thrashing
- [ ] ✅⭐⭐ Dynamic Binding

---

## ➕ Important Additions

### Memory Layout

- [ ] ➕⭐⭐⭐ Text Segment
- [ ] ➕⭐⭐⭐ Data Segment
- [ ] ➕⭐⭐⭐ BSS Segment
- [ ] ➕⭐⭐⭐ Heap
- [ ] ➕⭐⭐⭐ Stack

### Virtual Memory

- [ ] ➕⭐⭐⭐ Demand Paging
- [ ] ➕⭐⭐⭐ TLB (Translation Lookaside Buffer)
- [ ] ➕⭐⭐ Multi-Level Page Tables
- [ ] ➕⭐ Huge Pages

### APIs

- [ ] ➕⭐⭐ mmap()
- [ ] ➕⭐⭐ Memory Mapped Files

---

# Phase 5 — File Systems ⭐⭐⭐

## File System Basics

- [ ] ✅⭐⭐⭐ File Systems
- [ ] ✅⭐⭐ Types of File Systems
- [ ] ✅⭐⭐ Allocation Techniques
- [ ] ✅⭐⭐ Fragmentation
- [ ] ✅⭐⭐ FCB
- [ ] ✅⭐⭐ ACL
- [ ] ✅⭐⭐ Authentication
- [ ] ✅⭐⭐ Encryption
- [ ] ✅⭐⭐ Journaling
- [ ] ✅⭐⭐ Backup
- [ ] ✅⭐⭐ Recovery

---

## ➕ Important Additions

- [ ] ➕⭐⭐⭐ Inodes
- [ ] ➕⭐⭐⭐ Hard Link vs Soft Link
- [ ] ➕⭐⭐ File Permissions
- [ ] ➕⭐ Symbolic Links

---

# Phase 6 — Disk Management ⭐⭐⭐

- [ ] ✅⭐⭐ Disk Scheduling
- [ ] ✅⭐⭐ FCFS Disk Scheduling
- [ ] ✅⭐⭐ SSTF
- [ ] ✅⭐⭐ SCAN
- [ ] ✅⭐⭐ C-SCAN
- [ ] ✅⭐⭐ LOOK
- [ ] ✅⭐⭐ C-LOOK
- [ ] ✅⭐⭐ RAID

---

## ➕ Additional

- [ ] ➕⭐⭐ SSD vs HDD
- [ ] ➕⭐ RAID Levels Comparison

---

# Phase 7 — Inter Process Communication ⭐⭐⭐⭐

- [ ] ✅⭐⭐⭐ Message Passing
- [ ] ✅⭐⭐⭐ Shared Memory
- [ ] ✅⭐⭐⭐ Signals

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Pipes
- [ ] ➕⭐⭐ Named Pipes (FIFO)
- [ ] ➕⭐⭐ Sockets
- [ ] ➕⭐⭐ Message Queues

---

# Phase 8 — System Calls & Interrupts ⭐⭐⭐⭐

## System Calls

- [ ] ✅⭐⭐⭐ System Calls
- [ ] ✅⭐⭐ Categories

---

## Interrupts

- [ ] ✅⭐⭐⭐ Hardware Interrupts
- [ ] ✅⭐⭐⭐ Software Interrupts

---

## System

- [ ] ✅⭐⭐ Boot Process
- [ ] ✅⭐⭐ Event Driven Programming
- [ ] ✅⭐⭐ Resource Management
- [ ] ✅⭐⭐ Priority Inversion
- [ ] ✅⭐⭐ Load Balancing
- [ ] ✅⭐⭐ Performance Tuning

---

## ➕ Important Additions

- [ ] ➕⭐⭐⭐ Polling vs Interrupts
- [ ] ➕⭐⭐ DMA (Direct Memory Access)
- [ ] ➕⭐⭐ System Call Flow

---

# Phase 9 — Cache ⭐⭐⭐

- [ ] ✅⭐⭐⭐ Direct Mapping
- [ ] ✅⭐⭐⭐ Associative Mapping

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Cache Locality
- [ ] ➕⭐⭐ Cache Coherency
- [ ] ➕⭐⭐ False Sharing

---

# Phase 10 — Virtualization ⭐⭐⭐

- [ ] ✅⭐⭐ Virtual Machines
- [ ] ✅⭐⭐ Hypervisors
- [ ] ✅⭐⭐ Spooling

---

## ➕ Important Additions

- [ ] ➕⭐⭐⭐ Type 1 Hypervisor
- [ ] ➕⭐⭐⭐ Type 2 Hypervisor
- [ ] ➕⭐⭐⭐ Containers
- [ ] ➕⭐⭐ Docker Basics
- [ ] ➕⭐⭐ Linux Namespaces
- [ ] ➕⭐⭐ cgroups

---

# Phase 11 — OS Security ⭐⭐

- [ ] ✅⭐⭐ Operating System Security
- [ ] ✅⭐⭐ Authentication
- [ ] ✅⭐⭐ Access Control

---

## ➕ Additional

- [ ] ➕⭐⭐ Privilege Escalation
- [ ] ➕⭐⭐ Sandboxing

---

# Phase 12 — Performance ⭐⭐⭐

- [ ] ✅⭐⭐ Resource Management
- [ ] ✅⭐⭐ Performance Measurement
- [ ] ✅⭐⭐ Load Balancing

---

## ➕ Additional

- [ ] ➕⭐⭐ Amdahl's Law
- [ ] ➕⭐⭐ CPU Bound vs IO Bound
- [ ] ➕⭐⭐ Context Switch Overhead

---

# Phase 13 — Linux Commands (Conceptual) ⭐⭐

- [ ] ➕⭐⭐ ps
- [ ] ➕⭐⭐ top
- [ ] ➕⭐⭐ htop
- [ ] ➕⭐⭐ kill
- [ ] ➕⭐⭐ killall
- [ ] ➕⭐⭐ nice
- [ ] ➕⭐⭐ renice
- [ ] ➕⭐⭐ free
- [ ] ➕⭐⭐ vmstat
- [ ] ➕⭐⭐ lsof
- [ ] ➕⭐⭐ df
- [ ] ➕⭐⭐ du

---

# Phase 14 — Signals ⭐⭐⭐

- [ ] ➕⭐⭐⭐ SIGINT
- [ ] ➕⭐⭐⭐ SIGTERM
- [ ] ➕⭐⭐⭐ SIGKILL
- [ ] ➕⭐⭐ SIGSTOP
- [ ] ➕⭐⭐ Signal Handling

---

# Phase 15 — Optional (Advanced)

- [ ] 🔹 Linux Scheduler (CFS)
- [ ] 🔹 NUMA
- [ ] 🔹 Slab Allocator
- [ ] 🔹 Buddy Allocator
- [ ] 🔹 RCU
- [ ] 🔹 Lock-Free Programming
- [ ] 🔹 Kernel Modules
- [ ] 🔹 Device Drivers
- [ ] 🔹 Kernel Memory Allocator

---

# Final Interview Revision Checklist ⭐⭐⭐⭐⭐

## Absolute Must Know

- [ ] Operating System Basics
- [ ] Process vs Program vs Thread
- [ ] PCB
- [ ] Context Switching
- [ ] User Mode vs Kernel Mode
- [ ] Scheduling Algorithms
- [ ] Scheduling Metrics
- [ ] fork()
- [ ] exec()
- [ ] wait()
- [ ] Zombie vs Orphan Process
- [ ] Copy-on-Write
- [ ] Threads
- [ ] Mutex vs Semaphore
- [ ] Producer Consumer
- [ ] Readers-Writers Problem
- [ ] Deadlocks
- [ ] Banker's Algorithm
- [ ] Paging
- [ ] Segmentation
- [ ] Virtual Memory
- [ ] Demand Paging
- [ ] TLB
- [ ] Page Replacement Algorithms
- [ ] Process Memory Layout
- [ ] mmap()
- [ ] File Systems
- [ ] Inodes
- [ ] Hard Link vs Soft Link
- [ ] Disk Scheduling
- [ ] RAID
- [ ] Shared Memory
- [ ] Pipes
- [ ] Signals
- [ ] System Calls
- [ ] Interrupts
- [ ] Polling vs Interrupts
- [ ] Cache
- [ ] Virtual Machines
- [ ] Containers
- [ ] Type 1 vs Type 2 Hypervisors
- [ ] Linux Commands (Conceptual)

---

# Completion Goal

- TUF+ Roadmap: **100%**
- Important Additions: **100%**
- Optional Topics: **As Needed (Backend/System Design Focus)**
