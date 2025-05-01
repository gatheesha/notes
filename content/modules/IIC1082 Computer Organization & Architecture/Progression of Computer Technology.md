---
topic: Progression of Computer Technology
code: IIC1082
week: 0
lecturer: Dr. Chamara Liyanage
date: 2025-04-21T20:00:00
draft: false
cascade:
  type: docs
tags:
  - lecture
  - coa
---
## Summary
Brief summary of the main points and key takeaways from this lecture (2-3 sentences).

---

## Key Concepts
- Concept One: Brief definition
- Concept Two: Brief definition
- Concept Three: Brief definition

---

## Detailed Notes

### 🧠 Computer Science and Computing-Related Fields

#### Computer Science
Computer science is the study of the theory, design, implementation, and performance of computer software and computer systems, including the study of computability and computation itself.

#### Computer Engineering
Computer engineering is concerned with the design of computer hardware and of  
computer-based devices. To the extent CE involves software, it is software interacting tightly with hardware for embedded systems and computer-based devices.

#### Information System
Information systems as a field has to do with applying today’s information technology to solve today’s problems, typically in the area of businesses and other enterprises.

> Source: [University of Maine](https://umaine.edu/cs/what-is-cs/)

---

### 🧱 Computer Organization and Architecture
#### Introduction
Computer Organization and Architecture is a fundamental field of  
study in computer science and engineering that explores the design and  
operation of computer systems.

It forms the backbone of how modern computers are structured, how  
they function, and how they execute instructions to perform tasks.

#### Computer Organization
Computer Organization refers to the way hardware components are arranged  
and interconnected to form a computer system.

It involves understanding the various building blocks that constitute a  
computer, such as the central processing unit (CPU), memory, input/output  
devices, and storage units. The focus is on how these components work  
together to process data and execute programs efficiently.

#### Computer Architecture
Computer Architecture, on the other hand, deals with the design principles and  
concepts that govern the structure and behavior of a computer system.

It encompasses the instruction set architecture (ISA), which defines the set of  
instructions that a CPU can execute, as well as the organization of the CPU and  
its interaction with other system components.

Computer Architecture aims to optimize the performance, power efficiency, and  
cost-effectiveness of the computer system.

> Sources:  
> [TutorialsSpace](http://www.tutorialsspace.com/Computer-Architecture-And-Organization)  
> [GeeksforGeeks](https://www.geeksforgeeks.org/)
### Difference between Computer Architecture and Computer Organization

![](computer_organization_and_computer_architecture.png)

| Computer Architecture                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Computer Organization                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Architecture describes **what the computer does.**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | The Organization describes **how it does it.**                                                                                                                                                                                                                                                                                                                                                                                                              |
| Computer Architecture deals with the functional behavior of computer systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Computer Organization deals with a structural relationship.                                                                                                                                                                                                                                                                                                                                                                                                 |
| In the above figure, it’s clear that it deals with high-level design issues.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | In the above figure, it’s also clear that it deals with low-level design issues.                                                                                                                                                                                                                                                                                                                                                                            |
| Architecture indicates its hardware.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Whereas Organization indicates its performance.                                                                                                                                                                                                                                                                                                                                                                                                             |
| As a programmer, you can view architecture as a series of instructions, addressing modes, and registers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | The implementation of the architecture is called organization.                                                                                                                                                                                                                                                                                                                                                                                              |
| For designing a computer, its architecture is fixed first.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | For designing a computer, an organization is decided after its architecture.                                                                                                                                                                                                                                                                                                                                                                                |
| Computer Architecture is also called **Instruction Set Architecture (ISA).**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Computer Organization is frequently called **microarchitecture**.                                                                                                                                                                                                                                                                                                                                                                                           |
| Computer Architecture comprises logical functions such as instruction sets, registers, data types, and [addressing modes](https://www.geeksforgeeks.org/addressing-modes/).                                                                                                                                                                                                                                                                                                                                                                                                                              | Computer Organization consists of physical units like circuit designs, peripherals, and adders.                                                                                                                                                                                                                                                                                                                                                             |
| The different architectural categories found in our computer systems are as follows:<br><br>- [Von-Neumann Architecture](https://www.geeksforgeeks.org/computer-organization-von-neumann-architecture/)<br>- [Harvard Architecture](https://www.geeksforgeeks.org/harvard-architecture/)<br>- [Instruction Set Architecture](https://www.geeksforgeeks.org/microarchitecture-and-instruction-set-architecture/)<br>- [Micro-architecture](https://www.geeksforgeeks.org/microarchitecture-and-instruction-set-architecture/)<br>- [System Design](https://www.geeksforgeeks.org/system-design-tutorial/) | [CPU](https://www.geeksforgeeks.org/what-are-the-functions-of-a-cpu/) organization is classified into three categories based on the number of address fields:<br><br>- Organization of a single[Accumulator](https://www.geeksforgeeks.org/introduction-of-single-accumulator-based-cpu-organization/).<br>- Organization of general registers<br>- [Stack organization](https://www.geeksforgeeks.org/memory-stack-organization-in-computer-architecture/) |
| It makes the computer’s hardware visible.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | It offers details on how well the computer performs.                                                                                                                                                                                                                                                                                                                                                                                                        |
| Architecture coordinates the hardware and software of the system.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Computer Organization handles the segments of the network in a system.                                                                                                                                                                                                                                                                                                                                                                                      |
| The software developer is aware of it.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | It escapes the software programmer’s detection.                                                                                                                                                                                                                                                                                                                                                                                                             |
| Examples- Intel and AMD created the x86 processor. Sun Microsystems and others created the SPARC processor. Apple, IBM, and Motorola created the PowerPC.                                                                                                                                                                                                                                                                                                                                                                                                                                                | Organizational qualities include hardware elements that are invisible to the programmer, such as interfacing of computer and peripherals, memory technologies, and control signals.                                                                                                                                                                                                                                                                         |
### Key Topics Covered

- **Instruction Set Architecture (ISA):**  
  The interface between software and hardware, defines the set of instructions that a CPU can execute.

- **Processor Organization:**  
  How the central processing unit is designed, including its components like arithmetic logic unit (ALU), control unit, registers, and data paths.

- **Memory Hierarchy:**  
  The organization of memory subsystems, including cache memory, main memory (RAM), and secondary storage (hard disks, SSDs), to manage data storage and access efficiently.

- **Input/Output (I/O) Systems:**  
  How input and output devices are integrated into the computer system, enabling communication with external devices.

- **Parallel Processing and Pipelining:**  
  Techniques to enhance performance by executing multiple instructions concurrently or dividing the instruction execution into stages.

- **System Buses and Interconnects:**  
  The pathways that enable communication between different components of the computer system.

- **Multiprocessor and Multicore Systems:**  
  Configurations involving multiple processors or cores, allowing for increased processing power and parallel execution of tasks.

---

### 🖥️ Categories of Computer Types

#### Microcomputers
- Microcomputers are smaller computers that run on microprocessors in their central processing units.  
- Used on a professional or non-professional basis, often as personal computers at home (but not exclusively).  
- Much cheaper than supercomputers, mainframes, and even minicomputers.  
- Examples: Desktop computers, video game consoles.

Desktop computers can be specialized for things like gaming, equipped with high-end graphics cards and more RAM.

#### Personal Computer
A computer designed for use by an individual, usually incorporating a graphics display, a keyboard, and a mouse.

#### Workstations
A workstation is a powerful, high-end microcomputer. They contain one or more microprocessor CPUs.  
Mostly used for professional applications that require more power than a typical PC.

They may also be used as server computers that supply files to client computers over a network or the Internet.
#### Servers
- Built from similar technology as desktops but with greater computing, storage, and I/O capacity.  
- Range widely in cost and capability — from basic systems to supercomputers.  
- At the high end, servers can consist of tens of thousands of processors and terabytes of memory.

#### Warehouse-Scale Computers (WSCs)
- Massive datacenters used in cloud computing.  
- Companies like Amazon and Google build WSCs with over 100,000 servers.  
- These WSCs deliver software services to personal mobile devices (PMDs) without requiring local servers.

> Source: [UNM](https://www.unm.edu/~tbeach/terms/types.html)

#### Mobile Computers / Personal Mobile Devices (PMDs)
- Extremely portable, battery-powered devices with wireless connectivity.  
- Rely on downloadable apps for functionality.

**Examples include:**
- Laptops
- Netbooks
- Handheld game consoles (e.g., Game Boy, PSP)
- Calculators
- Small robots, AI devices, drones
- Portable media players (e.g., MP3 players, iPods)
- Smartwatches
- Smartphones
- Tablets (flat touchscreen devices, sometimes with keyboard attachments)

> Source: [Udemy Blog](https://www.udemy.com/blog/categories-of-computer/)

---

### 🔌 Embedded Computers

#### Overview
- A computer inside another device, used to run a specific application or suite.  
- Often have strict limitations on power and cost.  
- Prioritize reliability and performance within limited environments.

Embedded applications often:
- Require minimal performance
- Are low-cost and power-efficient
- Must interact with the external environment

#### Capabilities
- Communicate with sensors and monitor:
  - Speed of motion
  - Measurement precision
  - Time duration
- Can manage multiple simultaneous activities

**Examples:**
- Digital home appliances
- Home security systems
- Car control functions
- Embedded processors in TVs and washing machines
---
### 🧾 Terminals

#### Definition
A terminal is a computer, usually with limited processing power, that enables users to send data to and/or receive information from a server or host computer.
#### Thin Clients
- Resemble desktop computers but have limited capabilities.
- Depend heavily on network-connected servers for processing and storage.

#### Examples
- **POS Terminals:** Used in retail to record purchases and manage inventory.
- **ATMs:** Automated teller machines that perform banking services through host connections.

---

### Practical Examples
- Example 1: Description and outcome
- Example 2: Description and outcome
- Sample problem worked through in class