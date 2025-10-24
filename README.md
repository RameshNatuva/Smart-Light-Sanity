🏠 Smart Light Sanity – FPGA-Based Home Automation System

Smart Light Sanity is a Verilog-based home automation project implemented on the Edge Artix-7 FPGA board.
This system dynamically controls lighting, automatic sanitization, and door operation using IR and Ultrasonic sensors, aiming to save energy and promote contactless hygiene through real-time hardware control.

🔍 Features

💡 Smart Lighting: Automatically turns lights ON/OFF based on human presence using an IR sensor.

🧴 Contactless Sanitization: Activates a servo motor to dispense sanitizer when hands are detected.

🚪 Automatic Door System: Opens or closes the door using an ultrasonic sensor based on distance detection.

⚙️ Efficient Hardware Design: Fully implemented in Verilog HDL with modular structure for sensors, servos, and control logic.

⚙️ Hardware Components

Edge Artix-7 FPGA Board

Ultrasonic Sensor

IR Sensor

Servo Motor

LEDs

Breadboard & Jumper Wires

💡 Objective

To design a low-power, contactless smart home automation system that enhances safety and energy efficiency using real-time FPGA control.

📂 Repository Information

This repository contains:

Verilog source codes for all modules (IR, Ultrasonic, Servo, LED)

Top-level integration module

Constraint files

Simulation results and schematics

🧠 Learning Outcomes

Sensor interfacing and real-time control using FPGA

Verilog HDL coding and modular hardware design

PWM generation and timing management for servo operation

Hardware testing and system integration on Artix-7
