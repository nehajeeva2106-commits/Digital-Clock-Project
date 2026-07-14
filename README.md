# ⏰ Digital Clock Project

## Project Description

The **Digital Clock Project** is a 24-hour digital clock built using discrete digital IC components. A **NE555 Timer IC** generates a 1 Hz clock pulse, which drives **CD4026 decade counters** to count seconds, minutes, and hours. The output is displayed using **7-segment displays**.

The project was designed using **KiCad** for schematic design and implemented on a **breadboard** to demonstrate digital electronics concepts such as timing, counting, and display interfacing.

---

## Features

* 24-hour time format
* 1 Hz clock generation using NE555 Timer
* Displays Hours, Minutes, and Seconds
* Built using discrete digital ICs
* KiCad schematic design
* Breadboard implementation

---

## Components Used

* NE555 Timer IC
* CD4026 Decade Counter
* 7-Segment Displays
* Logic Gates (AND)
* Resistors
* Capacitors
* Breadboard
* Jumper Wires
* 5V Power Supply

---

## Working Principle

The NE555 Timer is configured in astable mode to generate a continuous **1 Hz pulse**, where each pulse represents one second. These pulses are fed into the **CD4026 decade counters**, which sequentially count the seconds, minutes, and hours. Logic gates are used wherever required to reset or control the counters at their respective maximum counts. The outputs of the counters directly drive the 7-segment displays, resulting in a real-time 24-hour digital clock.

---

## Repository Structure

```text
Digital-Clock-Project
│
├── Circuit/
│   ├── CircuitDiagram.png
│   └── Schematic.pdf
│
├── Datasheet/
│   ├── NE555.pdf
│   ├── CD4026.pdf
│   └── SevenSegment.pdf
│
├── Documentation/
│   └── ChronoBit26_Report.pdf
│
├── Images/
│   ├── BlockDiagram.png
│   └── CircuitPhoto.jpg
│
└── README.md
```

---

## Documentation

The complete project documentation is available in a single PDF file, which includes:

* Project Description
* Components Used
* Block Diagram
* Circuit Diagram
* KiCad Schematic
* Working Principle
* Breadboard Implementation
* Results
* Conclusion

---

## Challenges Faced

* Generating an accurate and stable 1 Hz clock signal.
* Properly resetting the counters at their maximum count.
* Managing wiring connections between multiple ICs on the breadboard.

---

## Future Improvements

* Alarm functionality
* Day and Date display
* PCB implementation for a compact and reliable design

---

## Contributors

* Neha https://github.com/nehajeeva2106-commits/Digital-Clock-Project.git
* Sakthivelv 
* Dhanyaask https://github.com/Dhanyaask

