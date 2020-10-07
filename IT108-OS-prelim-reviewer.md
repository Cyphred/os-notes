# IT108 Prelim Reviewer

## Boot Process
- The **bootstrap program** is loaded at power-up or reboot
- Initializes all aspects of the system
- Loads the operating system kernel and starts execution
- Kernel starts **system daemons** (services provided outside of the kernel)
- Kernel is **interrupt driven** (hardware and software). These interrupts consist of:
  - Hardware interrupt by one of the devices
  - Software interrupt (excepiton or trap)
    - Software error (e.g. division by zero)
    - Request for operating system service - **system call**
    - Other process problems like infinite loop, or processes modifying each other or the operating system.

### Powering up
This is where the computer will run a POST - a Power-On Self-Test. This is performed by firmware immediately after a computer is powered on. 
![POST Screen](https://upload.wikimedia.org/wikipedia/commons/9/92/POST_P5KPL.jpg)

If the self-test completes successfully, the **BIOS** will run, applying the parameters that are stored in the **CMOS**.

## Interrupts

## Traps
- A software-generated interrupt caused by an error or a user request.
- Also known as an **exception** or a **fault**
- Is caused by an exceptional condition like:
  - A breakpoint
  - Division by zero
  - Invalid memory access
- Usually results to a switch to kernel mode.
- Traps in a kernel process is more serious than a trap in a user process, and is fatal in some systems.


## Exceptions

## Shell

## GUI/CLI

## Kernel

## Interfaces

## API

## OS Layers

## System Calls

## Processes

## IPC

## States

## Threads/Threading
