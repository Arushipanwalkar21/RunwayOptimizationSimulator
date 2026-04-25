# Runway Optimization Simulator

A Java Swing–based aviation simulation that recommends the optimal landing runway 
for 5 Indian airports based on wind direction and rule-based wind alignment logic.

## Airports Covered
Delhi (IGI) · Mumbai (CSIA) · Chennai (MAA) · Vizag (VTZ) · Port Blair (IXZ)

## How It Works
The user selects an airport, enters wind direction in degrees and arrival time. 
The system applies rule-based headwind alignment logic to recommend the most 
suitable runway — the same principle used in real ATC operations.

## Tech Stack
Java · Swing · AWT · OOP · Timer-based Animation · paintComponent() rendering

## Features
- Multi-screen GUI: welcome screen → input → animated simulation → result
- Custom aircraft movement animation over runway with centreline markings
- Rule-based decision logic per airport runway configuration
