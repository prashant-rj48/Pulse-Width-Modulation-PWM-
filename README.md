# PWM-Based Power Control System Using IC 555 & KiCad PCB Design
Pulse Width Modulation (PWM)-based power control system using IC 555 timer, transistor switching, and duty-cycle modulation techniques.
The project demonstrates how PWM can efficiently control output power in real-world applications such as electric vehicle motor control, DC fan regulation, industrial actuators, and power electronics systems.

An LED load was used as a visual hardware indicator to demonstrate real-time PWM operation and switching behavior.

***

# Features
PWM signal generation using IC 555 timer.

Duty-cycle-based power control technique.

Potentiometer-controlled pulse width adjustment.

Efficient power regulation without varying supply voltage.

Complete schematic and PCB design using KiCad.

Hardware implementation on General Purpose PCB board.

Real-time PWM output visualization using LED load.

***

# PWM Concept
## IC 555
The IC 555 generates high-frequency ON/OFF pulses by charging and discharging a capacitor through diodes and a potentiometer.

Higher ON time → higher average output power
Lower ON time → lower average output power

The load receives varying average power depending on duty cycle.

##
## Duty Cycle

<img width="400" height="92" alt="image" src="https://github.com/user-attachments/assets/fae4869e-de31-471b-9319-af4b6ff3a6ff" />


<img width="650" height="446" alt="image" src="https://github.com/user-attachments/assets/4355207e-4f17-4a05-a17a-5ae331aa54c0" />

## Role of Potentiometer
The potentiometer changes the charging and discharging timing of the capacitor connected to the 555 timer.

This directly controls:- Pulse width, Duty cycle, Average output power

***

## Working Principle

    Power Supply
           │
           ▼
    555 Timer IC ───► PWM Signal Generation
           │
           ▼
    Potentiometer ───► Duty Cycle Control
           │
           ▼
     Transistor Switching Stage
           │
           ▼
      Output Load (LED Demonstration)


***

# PCB Design

## Components 
IC 555 timer

Timing capacitor

Resistors

Potentiometer

NPN transistor

Output load stage

Power supply section



## Schematic 
<img width="931" height="652" alt="image" src="https://github.com/user-attachments/assets/a978efbf-2856-4f7e-852e-6b83bc183cfb" />

## PCB layout

<img width="682" height="665" alt="image" src="https://github.com/user-attachments/assets/f474819e-5c39-48d9-b75c-6b0cd23c6301" />

## 3-D View
<img width="392" height="382" alt="image" src="https://github.com/user-attachments/assets/660efed5-343a-4c27-8d67-9b62c1cb0bdd" />

<img width="621" height="482" alt="image" src="https://github.com/user-attachments/assets/f3202721-ea01-4e73-8731-ff843dec27da" />







