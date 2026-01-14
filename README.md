# Gabriel Valentin, Portfolio

Entry level Computer Engineering graduate focused on design adjacent and implementation oriented roles. Portfolio content is based on academic and project work with emphasis on structured problem definition, interface behavior, accessibility, validation, and clear technical communication.

**Location:** San Antonio, TX  
**Phone:** 602-541-0388  
**Email:** Gabriel.Valentin1959@gmail.com  
**LinkedIn:** linkedin.com/in/gabriel-valentin-ce  

---

## Portfolio Index

### Featured Projects
- **Web Based Calendar System**, React, Node.js, SQL  
- **Hardware Random Number Generator using RO PUFs**, Capstone  

### Engineering and Systems Projects
- **16 bit RISC Processor on FPGA**, Verilog and SystemVerilog  
- **MSP430 Assembly Programming**, interrupt driven embedded systems  
- **Self Adjusting Solar Panel Tracker**, Arduino based firmware  

### Supporting Technical Depth
- Automatic Controls, PID Temperature Regulation, MATLAB and Simulink  
- Photovoltaic Energy Systems, PV and Converter Modeling  
- Signals and Systems, MATLAB based modeling  
- Data Structures and Algorithms in C, unit tested implementations  
- PCB Assembly and Soldering, through hole and SMD  

---

## Featured Project 1, Web Based Calendar System

**Context:** Full stack academic project  
**Role:** UI structure, interaction logic, data persistence, implementation, validation  
**Focus:** Usability, accessibility, predictable behavior, correctness  

### Project Overview
Designed and implemented a web based calendar system supporting common scheduling workflows. The project emphasizes predictable interface behavior, accessible interaction patterns, and reliable data persistence. Validation focused on both user facing behavior and backend correctness.

### Case Study A, Accessibility Focused Interface

**User Problem**  
Users need a calendar interface that supports common scheduling tasks with clear navigation, consistent interaction behavior, and accessibility across devices and environments.

**Solution Summary**  
Designed the user interface using structured interaction flows and responsive layout. Implemented accessibility support using ARIA attributes and validated behavior across environments to ensure predictable interaction.

**Key Design Decisions**
- Defined clear navigation and interaction flows to reduce user error  
- Implemented ARIA attributes to support accessible interaction  
- Applied responsive layout principles for cross device usability  
- Validated cross browser behavior using Ubuntu virtual machines  

**Implementation and Validation**
- Implemented responsive UI behavior and accessibility attributes  
- Tested across browsers and environments using Ubuntu virtual machines  
- Iterated based on observed issues and functional validation  

### Case Study B, Database Backed Persistence and Workflow Correctness

**User Problem**  
Users require reliable create, modify, and retrieval workflows that remain consistent as calendar data changes.

**Solution Summary**  
Implemented SQL backed persistence to store, retrieve, and modify calendar data. Interface behavior was explicitly tied to data state to ensure correctness across workflows.

**Key Design Decisions**
- Defined explicit workflows for create, edit, and retrieval actions  
- Tied interface behavior directly to underlying data state  
- Validated correctness through repeatable test cases  

**Implementation and Validation**
- Implemented SQL queries supporting persistence and updates  
- Verified outputs against expected results for correctness  

**Tools and Technologies:** React, Node.js, JavaScript, HTML, CSS, SQL, Ubuntu virtual machines  
**Artifacts Available:** Text based case study only at this time  

---

## Featured Project 2, Hardware Random Number Generator using RO PUFs

**Context:** Capstone project, team of two  
**Role:** Research, experimentation, testing, documentation  
**Focus:** Validation, entropy analysis, defensible conclusions  

### Project Overview
Designed and tested a hardware random number generator using inverter based ring oscillator PUF structures. The project focused on entropy quality, repeatability, and realistic assessment of limitations for hardware bound randomness.

### Design and Validation Summary
Applied voltage tap points and decoder wiring strategies to improve entropy and reduce correlation. Captured output using Arduino Uno at approximately 8,000 bits per second. Validated output using NIST SP 800 22, meeting overall pass thresholds with documented limitations.

**Key Validation Decisions**
- Designed experiments to evaluate entropy and correlation behavior  
- Logged high rate output and analyzed results using standardized statistical tests  
- Documented limitations and realistic use cases rather than overstating results  

**Tools and Technologies:** Arduino Uno, breadboard prototyping, NIST SP 800 22  

---

## Engineering and Systems Projects

### 16 bit RISC Processor on FPGA, Digital Design Project

**Context:** Academic project  
**Role:** Design, implementation, simulation, debug, verification  
**Focus:** Structured logic, verification discipline  

**Summary**  
Designed and implemented a 16 bit pipelined CPU using Verilog and SystemVerilog. Implemented ALU, register file, control logic, and memory interface. Validated custom ISA behavior using C based tests and simulation driven testbenches. Performed synthesis in Quartus and simulation in Questa or ModelSim. Debugged state based logic across the full design lifecycle.

**Tools and Technologies:** Verilog, SystemVerilog, Quartus, Questa or ModelSim  

---

### MSP430 Assembly Programming, Embedded Systems Project

**Context:** Academic project  
**Role:** Low level firmware implementation and debug  
**Focus:** Interrupt driven behavior, deterministic control  

**Summary**  
Programmed TI MSP430 microcontroller in Assembly with interrupt driven routines for memory and I O control. Manually mapped registers and memory to perform arithmetic and logic operations. Controlled execution timing to observe high speed behavior. Implemented timing delays and damping logic to stabilize execution.

---

### Self Adjusting Solar Panel Tracker, Embedded Firmware Project

**Context:** Academic project  
**Role:** Firmware implementation, sensor integration, validation  
**Focus:** Continuous sampling, decision logic, stability  

**Summary**  
Developed an Arduino based solar panel tracking system using light sensors and motor actuators. Implemented continuous sensor sampling, decision logic, and calibration routines to ensure stable tracking behavior.

---

## Supporting Technical Depth

### Automatic Controls, PID Temperature Regulation

**Context:** Academic controls systems project  
**Focus:** System modeling, stability analysis, controller design, validation  

Applied classical control theory to model and regulate temperature systems. Derived system transfer functions using Laplace methods and block diagram manipulation. Designed and tuned PID controllers to meet stability and performance requirements, including steady state error and transient response constraints. Evaluated system behavior using root locus, Bode, and Nyquist analysis. Validated controller performance through MATLAB and Simulink simulation, adjusting gains to balance responsiveness and stability.

**Tools and Technologies:** MATLAB, Simulink, Control System Toolbox  

---

### Photovoltaic Energy Systems, PV and Converter Modeling

**Context:** Academic power and energy systems project  
**Focus:** System modeling, converter behavior, efficiency analysis  

Modeled photovoltaic array behavior under varying conditions and analyzed system performance through simulation. Designed and evaluated DC DC and DC AC converter topologies, including buck, boost, and inverter configurations. Analyzed switching behavior, transient response, and efficiency tradeoffs. Identified instability issues related to array interconnection and converter interaction. Used simulation results to assess performance limitations and realistic operating conditions.

**Tools and Technologies:** MATLAB, Simulink  

---

### Signals and Systems, MATLAB Based Modeling

**Context:** Academic signals and systems coursework  
**Focus:** Mathematical modeling, frequency domain analysis, validation  

Applied Fourier, Laplace, and Z transform techniques to analyze continuous and discrete time systems. Modeled sampling, reconstruction, aliasing, and frequency response behavior using MATLAB. Validated analytical results through simulation and comparison against expected theoretical outcomes. Emphasized understanding of system behavior across time and frequency domains rather than black box computation.

**Tools and Technologies:** MATLAB  

---

### Data Structures and Algorithms in C

**Context:** Academic programming project  
**Focus:** Correctness, efficiency, implementation discipline  

Implemented core data structures and algorithms in C, including lists, stacks, queues, trees, and sorting routines. Emphasized correctness, memory management, and predictable behavior. Developed unit tests to validate functionality and edge cases. Used Makefiles and gdb for structured build and debug workflows. Focused on clear implementation and verifiable outcomes rather than language abstractions.

**Tools and Technologies:** C, Make, GCC, gdb  

---

### PCB Assembly and Soldering

**Context:** Academic and hands on lab work  
**Focus:** Hardware assembly, verification, practical troubleshooting  

Performed through hole and surface mount PCB assembly using standard soldering techniques. Interpreted schematics and component layouts to ensure correct placement and orientation. Used multimeters to verify continuity and identify assembly faults. Developed familiarity with common hardware issues such as cold joints, bridging, and component misplacement. Emphasized careful workmanship and functional verification.

**Tools and Technologies:** Soldering tools, multimeter, schematics  
