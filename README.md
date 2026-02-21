# Embedded-Project-Omni-Wheel 🏆🏆🏆🏆🏆🏆

# Project Description🚀🚀
This project involves designing and building a modular mobile manipulator robot for the MCT333/MCT344 Mechatronic Systems Design course at Ain Shams University. The robot will feature an omni-wheel base for versatile movement and a robotic arm for manipulation tasks. It's part of the Spring 2026 Mechatronics Omni-Challenge competition, focusing on developing a fully integrated mechatronic system where mechanical, electrical, control, and software subsystems operate as one cohesive and synchronized unit.

# Key Functionality and Tasks🚀🚀
The robot needs to perform the following:

Manual Teleoperation: The robot should be controllable wirelessly for initial maneuvering through a marked lane.
Autonomous Pick-and-Place: It must autonomously pick up QR-code-encoded colored cubes from constrained pickup stations.
Sorting: Sort the picked-up cubes into dedicated on-board bins (Red, Blue, Green) based on their QR code, which encodes the target box color.
Delivery: Deliver the sorted cubes to specific matching colored ground drop-off zones.
Obstacle Detection: The robot must be capable of obstacle detection.
Repeatable Task Execution: The system should demonstrate repeatable task execution.

# Modularity Requirements🚀🚀
The design emphasizes modularity, ensuring components are easily interchangeable and separable.

Two Main Modules: Mobile Base Module and Manipulator Module. Each module must have its own controller and power distribution.
Standardized Mechanical Interface: For fast attachment/detachment (mounting pattern + alignment features).
Standardized Electrical Interface: For plug-and-play integration (power connector + communication connector).
Defined Communication Protocol: Between modules (e.g., CAN/UART/Ethernet/RS-485) including heartbeat and safety states.
Constraints
Total weight: Less than 10kg (including motors, mechanics, electronics, and battery. Lighter is better).
Max dimensions (arm folded): 50 cm (W) x 50 cm (L) x 70cm (H). The robot must start with the arm folded in this configuration.
Boxes sizes: 5cm x 5cm x 5cm. Each box will have a QR code for the color configuration.
Materials: 3D printing and/or laser cutting, or any other relevant materials (other methods require instructor approval).
Power source: Battery operated, including fuse, main switch, and safe charging approach.
Safety: Mandatory safety inspection (must pass Phase 1 to enter competition).

# Design Methodology🚀🚀
The project follows the VDI 2206 methodology for system design, which includes phases from problem definition to system integration and validation. Additionally, each team must perform a functional analysis (functional decomposition, function structure, and functional block diagrams) and apply TRIZ to generate innovative concepts and resolve key design contradictions.

# Competition Aspects🚀🚀
Team Roles: Teams will consist of 7-8 students, with each student owning a well-defined set of tasks and deliverables. Recommended roles include Project Manager & Systems Engineer, Mechanical Lead, Actuation & Power Lead, Electronics Lead, Embedded/Real-Time Lead, Software/Perception Lead, Controls & Estimation Lead, and Documentation & QA Lead.
Competition Procedures: Each team receives a 5-minute time slot for an official run. It includes a pre-competition safety check, a manual teleoperation phase for initial maneuvering, and a fully autonomous handling operation phase for picking, identifying, and delivering boxes.
Scoring:
Safety inspection passed: Mandatory gate (no points).
Manual phase: reach and stop at transition line: 10 points.
Autonomous pick the box: 5 points per box.
Correct on-board color sorting: +2 bonus per box (only if correct bin).
Correct maneuvering to the drop-off zone: 10 points per box.
Correct delivery to matching drop-off zone: 10 points per box (box must end fully inside the target square).
Penalties: Lane boundary crossing: -3 each; collision: -5; manual intervention after transition: -10 (repeat may invalidate run).
Tie-breaker: highest score, then fastest valid time, then lightest robot.

# Deliverables and Deadlines🚀🚀
The document outlines a detailed schedule with expected submissions and demos throughout the semester, culminating in a final submission package. Key submissions include:

Weekly: Updated responsibility sheet, engineering notebook/decision log, subsystem test evidence (videos and logs).
Mid-semester: Requirements document, competition interpretation, initial risk assessment, functional decomposition/functional block diagrams, TRIZ ideation worksheet, system concept review, modeling & simulation demo, subsystem prototype check, autonomy demo, full integration dry-run.
Final Submission Package (after the competition):
Final technical report (PDF) with full VDI 2206 documentation.
System datasheet and specifications sheet (1-2 pages).
CAD package (assembly + drawings) and manufacturing files (STL/DXF as applicable).
Electrical schematics + PCB files + wiring diagram and harness plan.
Source code repository with README, build instructions, and license declarations.
Short videos: (1) system walkthrough, (2) autonomy demo, (3) competition run highlight.
Test report including repeatability results and failure analysis.

# Assessment Criteria🚀🚀
The project grade is based on both team outcomes (50%) and individual contribution (50%). Team assessment criteria include:

Professional system documentation + system datasheet and specifications (15%).
Professional system design and correct application of VDI 2206 (20%).
Modeling and simulation activities (15%).
Professional design of control panel, wiring, HMI, etc. (10%).
Professional implementation of hardware components and system integration (20%).
Professional system integration in a functional way (10%).
System overall performance, accuracy, and repeatability (including competition performance) (10%).
