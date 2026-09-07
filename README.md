# VHDL Learning Journey — 100 Projects

A structured, hands-on journey to learn **VHDL and digital hardware design** by building 100 projects, starting with basic logic gates and progressing toward FPGA systems, communication protocols, memory subsystems, CPUs, and SoC prototypes.

The goal is simple:

> **Learn digital design by building, simulating, testing, and implementing hardware.**

This repository contains **100 projects organized into 10 progressive categories**, moving from fundamental digital logic to increasingly complete FPGA-based systems.

---

#  Main Goal

Build a strong practical foundation in:

* VHDL
* Digital logic
* Combinational circuits
* Sequential circuits
* Flip-flops
* Registers
* Counters
* Finite State Machines
* Memory systems
* Communication protocols
* Testbenches
* Simulation
* FPGA design
* Hardware interfaces
* CPU design
* SoC concepts

By the end of this journey, you should be comfortable designing, simulating, testing, and understanding digital hardware using VHDL.

---

#  Learning Path

| Category | Projects | Main Focus               |
| -------- | -------: | ------------------------ |
| 01       |     1–10 | Digital Basics           |
| 02       |    11–20 | Combinational Logic      |
| 03       |    21–30 | Sequential Logic         |
| 04       |    31–40 | Testbenches & Simulation |
| 05       |    41–50 | Finite State Machines    |
| 06       |    51–60 | Counters & Timers        |
| 07       |    61–70 | Memory & Registers       |
| 08       |    71–80 | Communication            |
| 09       |    81–90 | FPGA Projects            |
| 10       |   91–100 | Advanced Projects        |

---

#  Category 01 — Digital Basics

Start with fundamental digital logic and basic VHDL design.

### Projects

* [ ] **01 — Hello VHDL**
  Create a basic VHDL entity and architecture.

* [ ] **02 — AND Gate**
  Implement a two-input AND gate.

* [ ] **03 — OR Gate**
  Implement an OR gate.

* [ ] **04 — NOT Gate**
  Implement an inverter.

* [ ] **05 — XOR Gate**
  Implement an XOR gate.

* [ ] **06 — NAND Gate**
  Implement a NAND gate.

* [ ] **07 — NOR Gate**
  Implement a NOR gate.

* [ ] **08 — XNOR Gate**
  Implement an XNOR gate.

* [ ] **09 — Logic Gate Tester**
  Test multiple basic logic gates.

* [ ] **10 — Basic Logic Unit**
  Combine basic gates into a small logic unit.

### Main Concepts

* VHDL entity
* VHDL architecture
* Signals
* `std_logic`
* Concurrent assignments
* Boolean logic
* Logic operators
* Basic synthesis concepts

---

#  Category 02 — Combinational Logic

Build larger circuits from basic logic components.

### Projects

* [ ] **11 — Half Adder**
* [ ] **12 — Full Adder**
* [ ] **13 — Half Subtractor**
* [ ] **14 — Full Subtractor**
* [ ] **15 — 2-to-4 Decoder**
* [ ] **16 — 4-to-2 Encoder**
* [ ] **17 — 2-to-1 Multiplexer**
* [ ] **18 — 4-to-1 Multiplexer**
* [ ] **19 — 1-to-4 Demultiplexer**
* [ ] **20 — Four-Bit ALU**

### Main Concepts

* Combinational logic
* Adders
* Subtractors
* Decoders
* Encoders
* Multiplexers
* Demultiplexers
* Arithmetic operations
* `process`
* `case`
* `if`
* Component design

---

#  Category 03 — Sequential Logic

Learn how hardware stores state and responds to clock signals.

### Projects

* [ ] **21 — D Flip-Flop**
* [ ] **22 — T Flip-Flop**
* [ ] **23 — JK Flip-Flop**
* [ ] **24 — SR Flip-Flop**
* [ ] **25 — 4-Bit Register**
* [ ] **26 — Shift Register**
* [ ] **27 — Parallel Load Register**
* [ ] **28 — Serial-In Serial-Out**
* [ ] **29 — Serial-In Parallel-Out**
* [ ] **30 — Universal Shift Register**

### Main Concepts

* Sequential logic
* Clock signals
* Flip-flops
* Registers
* Reset
* Enable signals
* Synchronous design
* Serial data
* Parallel data
* Shift operations

---

# Category 04 — Testbenches & Simulation

Learn how to verify VHDL designs through simulation and automated testing.

### Projects

* [ ] **31 — Gate Testbench**
* [ ] **32 — Adder Testbench**
* [ ] **33 — MUX Testbench**
* [ ] **34 — Flip-Flop Testbench**
* [ ] **35 — Register Testbench**
* [ ] **36 — Counter Testbench**
* [ ] **37 — ALU Testbench**
* [ ] **38 — Random Stimulus Testbench**
* [ ] **39 — Assertion Testbench**
* [ ] **40 — Complete Simulation Project**

### Main Concepts

* Testbenches
* Simulation
* Stimulus generation
* Clock generation
* Waveforms
* Assertions
* Random testing
* Functional verification
* Expected vs. actual results
* Debugging hardware designs

---

#  Category 05 — Finite State Machines

Learn how to design systems that operate through defined states and transitions.

### Projects

* [ ] **41 — Simple FSM**
* [ ] **42 — Traffic Light FSM**
* [ ] **43 — Pedestrian Crossing FSM**
* [ ] **44 — Vending Machine FSM**
* [ ] **45 — Door Controller FSM**
* [ ] **46 — Elevator FSM**
* [ ] **47 — Washing Machine FSM**
* [ ] **48 — Sequence Detector**
* [ ] **49 — Parking Gate FSM**
* [ ] **50 — FSM Controller Project**

### Main Concepts

* Finite State Machines
* States
* Transitions
* State registers
* Moore machines
* Mealy machines
* State diagrams
* Control logic
* Sequential processes
* FSM verification

---

#  Category 06 — Counters & Timers

Build timing-related digital systems using clocks, counters, and dividers.

### Projects

* [ ] **51 — Up Counter**
* [ ] **52 — Down Counter**
* [ ] **53 — Up/Down Counter**
* [ ] **54 — Ring Counter**
* [ ] **55 — Johnson Counter**
* [ ] **56 — Decade Counter**
* [ ] **57 — Frequency Divider**
* [ ] **58 — Digital Timer**
* [ ] **59 — Stopwatch**
* [ ] **60 — Digital Clock**

### Main Concepts

* Counters
* Clock division
* Frequency
* Timing
* Clock enables
* Modulo counters
* Timing logic
* Multi-digit counting
* Time-based state machines

---

#  Category 07 — Memory & Registers

Learn how digital systems store, retrieve, and manage data.

### Projects

* [ ] **61 — ROM**
* [ ] **62 — RAM**
* [ ] **63 — Single-Port RAM**
* [ ] **64 — Dual-Port RAM**
* [ ] **65 — FIFO**
* [ ] **66 — LIFO**
* [ ] **67 — Register File**
* [ ] **68 — Cache Simulator**
* [ ] **69 — Memory Controller**
* [ ] **70 — Memory Subsystem**

### Main Concepts

* ROM
* RAM
* Memory addresses
* Read/write operations
* Registers
* FIFO
* LIFO
* Register files
* Memory controllers
* Cache concepts
* Data storage

---

#  Category 08 — Communication

Learn how digital systems communicate with external devices and other hardware.

### Projects

* [ ] **71 — UART Transmitter**
* [ ] **72 — UART Receiver**
* [ ] **73 — UART Loopback**
* [ ] **74 — SPI Controller**
* [ ] **75 — SPI Receiver**
* [ ] **76 — I2C Master**
* [ ] **77 — I2C Slave**
* [ ] **78 — Serial Command Processor**
* [ ] **79 — Communication Bridge**
* [ ] **80 — Multi-Protocol Controller**

### Main Concepts

* UART
* SPI
* I2C
* Serial communication
* Baud rate
* Clocked communication
* Transmitters
* Receivers
* Protocol state machines
* Command processing
* Hardware interfaces

---

#  Category 09 — FPGA Projects

Move from simulated hardware toward practical FPGA-oriented designs.

### Projects

* [ ] **81 — LED Controller**
* [ ] **82 — Button Debouncer**
* [ ] **83 — LED Chaser**
* [ ] **84 — Seven-Segment Display**
* [ ] **85 — Multiplexed Display**
* [ ] **86 — Keypad Interface**
* [ ] **87 — PWM Generator**
* [ ] **88 — Digital Thermometer Interface**
* [ ] **89 — VGA Controller**
* [ ] **90 — FPGA Control Panel**

### Main Concepts

* FPGA I/O
* LEDs
* Buttons
* Switches
* Debouncing
* Seven-segment displays
* Display multiplexing
* Keypads
* PWM
* VGA
* Hardware interfaces

---

#  Category 10 — Advanced Projects

Combine the concepts from the entire journey into larger digital systems.

### Projects

* [ ] **91 — Digital Stopwatch FPGA**
* [ ] **92 — Digital Clock FPGA**
* [ ] **93 — Calculator FPGA**
* [ ] **94 — Frequency Counter**
* [ ] **95 — Logic Analyzer**
* [ ] **96 — Simple CPU**
* [ ] **97 — Simple Assembler Interface**
* [ ] **98 — SoC Prototype**
* [ ] **99 — FPGA Data Logger**
* [ ] **100 — Mini Computer System**

### Main Concepts

* System-level design
* Hardware architecture
* CPU concepts
* Instruction processing
* Data paths
* Control units
* Embedded systems
* FPGA-based systems
* Hardware/software interfaces
* SoC concepts

---

#  Skills Developed

By completing the 100 projects, you will practice:

## VHDL

* Entities
* Architectures
* Signals
* Ports
* Processes
* Concurrent assignments
* Sequential statements
* `if`
* `case`
* Generics
* Components
* Packages

## Digital Logic

* Logic gates
* Boolean logic
* Combinational circuits
* Sequential circuits
* Arithmetic circuits
* Multiplexers
* Decoders
* Encoders
* Registers
* Counters

## Sequential Design

* Flip-flops
* Clocked processes
* Reset logic
* Enable signals
* State machines
* Timing logic

## Verification

* Testbenches
* Simulation
* Waveform analysis
* Assertions
* Random stimulus
* Functional verification

## FPGA Development

* FPGA I/O
* LED control
* Button interfaces
* Displays
* Keypads
* PWM
* VGA
* Hardware peripherals

## System Design

* Memory systems
* Communication protocols
* CPUs
* Data paths
* Control units
* SoC architecture
* Hardware interfaces

---

#  Learning Progress

Track your progress through the complete journey.

## Category 01 — Digital Basics

* [ ] 01 Hello VHDL
* [ ] 02 AND Gate
* [ ] 03 OR Gate
* [ ] 04 NOT Gate
* [ ] 05 XOR Gate
* [ ] 06 NAND Gate
* [ ] 07 NOR Gate
* [ ] 08 XNOR Gate
* [ ] 09 Logic Gate Tester
* [ ] 10 Basic Logic Unit

## Category 02 — Combinational Logic

* [ ] 11 Half Adder
* [ ] 12 Full Adder
* [ ] 13 Half Subtractor
* [ ] 14 Full Subtractor
* [ ] 15 Decoder 2-to-4
* [ ] 16 Encoder 4-to-2
* [ ] 17 Multiplexer 2-to-1
* [ ] 18 Multiplexer 4-to-1
* [ ] 19 Demultiplexer 1-to-4
* [ ] 20 Four-Bit ALU

## Category 03 — Sequential Logic

* [ ] 21 D Flip-Flop
* [ ] 22 T Flip-Flop
* [ ] 23 JK Flip-Flop
* [ ] 24 SR Flip-Flop
* [ ] 25 4-Bit Register
* [ ] 26 Shift Register
* [ ] 27 Parallel Load Register
* [ ] 28 Serial-In Serial-Out
* [ ] 29 Serial-In Parallel-Out
* [ ] 30 Universal Shift Register

## Category 04 — Testbenches & Simulation

* [ ] 31 Gate Testbench
* [ ] 32 Adder Testbench
* [ ] 33 MUX Testbench
* [ ] 34 Flip-Flop Testbench
* [ ] 35 Register Testbench
* [ ] 36 Counter Testbench
* [ ] 37 ALU Testbench
* [ ] 38 Random Stimulus Testbench
* [ ] 39 Assertion Testbench
* [ ] 40 Complete Simulation Project

## Category 05 — FSM

* [ ] 41 Simple FSM
* [ ] 42 Traffic Light FSM
* [ ] 43 Pedestrian Crossing FSM
* [ ] 44 Vending Machine FSM
* [ ] 45 Door Controller FSM
* [ ] 46 Elevator FSM
* [ ] 47 Washing Machine FSM
* [ ] 48 Sequence Detector
* [ ] 49 Parking Gate FSM
* [ ] 50 FSM Controller Project

## Category 06 — Counters & Timers

* [ ] 51 Up Counter
* [ ] 52 Down Counter
* [ ] 53 Up/Down Counter
* [ ] 54 Ring Counter
* [ ] 55 Johnson Counter
* [ ] 56 Decade Counter
* [ ] 57 Frequency Divider
* [ ] 58 Digital Timer
* [ ] 59 Stopwatch
* [ ] 60 Digital Clock

## Category 07 — Memory & Registers

* [ ] 61 ROM
* [ ] 62 RAM
* [ ] 63 Single-Port RAM
* [ ] 64 Dual-Port RAM
* [ ] 65 FIFO
* [ ] 66 LIFO
* [ ] 67 Register File
* [ ] 68 Cache Simulator
* [ ] 69 Memory Controller
* [ ] 70 Memory Subsystem

## Category 08 — Communication

* [ ] 71 UART Transmitter
* [ ] 72 UART Receiver
* [ ] 73 UART Loopback
* [ ] 74 SPI Controller
* [ ] 75 SPI Receiver
* [ ] 76 I2C Master
* [ ] 77 I2C Slave
* [ ] 78 Serial Command Processor
* [ ] 79 Communication Bridge
* [ ] 80 Multi-Protocol Controller

## Category 09 — FPGA Projects

* [ ] 81 LED Controller
* [ ] 82 Button Debouncer
* [ ] 83 LED Chaser
* [ ] 84 Seven-Segment Display
* [ ] 85 Multiplexed Display
* [ ] 86 Keypad Interface
* [ ] 87 PWM Generator
* [ ] 88 Digital Thermometer Interface
* [ ] 89 VGA Controller
* [ ] 90 FPGA Control Panel

## Category 10 — Advanced Projects

* [ ] 91 Digital Stopwatch FPGA
* [ ] 92 Digital Clock FPGA
* [ ] 93 Calculator FPGA
* [ ] 94 Frequency Counter
* [ ] 95 Logic Analyzer
* [ ] 96 Simple CPU
* [ ] 97 Simple Assembler Interface
* [ ] 98 SoC Prototype
* [ ] 99 FPGA Data Logger
* [ ] 100 Mini Computer System

---

# Recommended Workflow

For each VHDL project, follow this workflow.

### 1. Understand

Read the project's `README.md` and understand the required hardware behavior.

### 2. Design

Before writing VHDL, think about:

* Inputs
* Outputs
* Internal signals
* Combinational logic
* Sequential logic
* Clock requirements
* Reset behavior
* State transitions

### 3. Implement

Write the VHDL entity and architecture.

### 4. Simulate

Create or use a testbench and verify the design with simulation.

### 5. Analyze

Inspect waveforms and verify that the circuit behaves as expected.

### 6. Refactor

Improve the design, naming, structure, and reusability.

### 7. Synthesize

When appropriate, synthesize the design and check for synthesis issues.

### 8. Implement on FPGA

For FPGA-oriented projects, connect the design to actual hardware when available.

### 9. Document

Record the design, behavior, simulation results, and lessons learned.

### 10. Commit

Save your progress with Git.

```bash
git status
git add .
git commit -m "feat: complete VHDL project"
git push
```

---

#  Simulation-First Philosophy

Hardware development should be approached carefully.

A useful development cycle is:

```text
Specification
     ↓
Design
     ↓
VHDL Implementation
     ↓
Testbench
     ↓
Simulation
     ↓
Waveform Analysis
     ↓
Fix / Refactor
     ↓
Synthesis
     ↓
FPGA Implementation
     ↓
Hardware Testing
```

Simulation is an important part of the journey because it allows you to verify behavior before moving to physical hardware.

---

#  Repository Structure

```text
vhdl-learning-journey/
│
├── category-01-digital-basics/
│   ├── 01-HelloVHDL/
│   ├── 02-ANDGate/
│   ├── ...
│   └── 10-BasicLogicUnit/
│
├── category-02-combinational-logic/
│   ├── 11-HalfAdder/
│   ├── ...
│   └── 20-FourBitALU/
│
├── category-03-sequential-logic/
│
├── category-04-testbenches-simulation/
│
├── category-05-fsm/
│
├── category-06-counters-timers/
│
├── category-07-memory-registers/
│
├── category-08-communication/
│
├── category-09-fpga-projects/
│
├── category-10-advanced-projects/
│
└── README.md
```

---

#  Hardware Design Progression

The journey gradually moves from individual gates to complete digital systems:

```text
Logic Gates
     ↓
Combinational Circuits
     ↓
Flip-Flops & Registers
     ↓
Testbenches & Simulation
     ↓
Finite State Machines
     ↓
Counters & Timers
     ↓
Memory Systems
     ↓
Communication Protocols
     ↓
FPGA Peripherals
     ↓
CPU / SoC / Computer Systems
```

Each stage builds on the hardware concepts introduced earlier.

---

#  Project Philosophy

The purpose of this repository is not simply to write 100 VHDL files.

The goal is to develop the ability to **think in hardware**.

For every project, focus on:

* What are the inputs?
* What are the outputs?
* Does the circuit need memory?
* Is the logic combinational or sequential?
* What happens on each clock edge?
* What happens during reset?
* What are the possible states?
* How can the design be tested?
* Does the simulation match the specification?
* Can the design be synthesized?

The projects gradually move from:

```text
Understanding Gates
        ↓
Designing Circuits
        ↓
Managing State
        ↓
Building Controllers
        ↓
Storing Data
        ↓
Communicating
        ↓
Controlling FPGA Hardware
        ↓
Designing Computer Systems
```

---

#  Final Goal

After completing all 100 projects, you should have practical experience with:

* VHDL syntax and structure
* Digital logic design
* Combinational circuits
* Sequential circuits
* Flip-flops
* Registers
* Counters
* FSMs
* Testbenches
* Simulation
* Assertions
* Memory systems
* UART
* SPI
* I2C
* FPGA peripherals
* Display controllers
* PWM
* VGA
* CPU fundamentals
* SoC concepts
* Hardware system design

Most importantly, you should be able to take a digital-system specification, break it into smaller hardware components, implement those components in VHDL, verify them through simulation, and progressively integrate them into larger systems.

---

#  100 Projects. One Hardware Journey.

**Start with logic gates.
Build circuits.
Learn sequential logic.
Master FSMs.
Design memory and communication systems.
Work with FPGAs.
Build a CPU.
Build a computer system.**

> **Don't just learn VHDL. Learn to think, design, and build in hardware. ⚡**
