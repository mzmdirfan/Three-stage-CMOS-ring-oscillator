# THREE-STAGE-CMOS-RING-OSCILLATOR

- [IMPLEMENTATION-OF-THREE-STAGE-CMOS-RING-OSCILLATOR](#)
- [Abstract](#abstract)
- [CMOS RING OSCILLATOR](#cmos-ring-oscillator)
- [Block Diagram](#block-diagram)
- [Reference Circuit Diagram](#reference-circuit-diagram)
- [Proposed Methodology](#proposed-methodology)
- [EDA Tools Used](#eda-tools-used)
- [Circuit Details](#circuit-details)
- [Output Waveforms](#output-waveforms)

# Abstract
The design and simulation of a three-stage CMOS ring oscillator using the SkyWater PDK. The oscillator, consisting of three interconnected inverters, demonstrates stable oscillation characteristics, including tunable frequency and appropriate duty cycle. Simulation results highlight the impact of transistor sizing and load capacitance on performance. This work emphasizes the significance of ring oscillators in integrated circuit applications

# CMOS RING OSCILLATOR

The ring oscillator is “an odd number of inverters are connected in a series form with positive feedback & output oscillates between two voltage levels either 1 or zero to measure the speed of the process.
Ring oscillator uses an odd number of inverters to achieve more gain than a single inverting amplifier. The inverter gives a delay to the input signal and if the numbers of inverters are increases then oscillator frequency will be decreased. So the desired oscillator frequency depends on the number of inverter stages of the oscillator.”


The s frequency of oscillation formula for this oscillator is

                                  f = 1 / (2*N*T)

T = time delay for single inverter
n = number of inverters in the oscillator

# Block Diagram
![image](https://github.com/user-attachments/assets/5eac58fd-8dfa-4da6-9782-94072845393a)

# Reference Circuit Diagram
![image](https://github.com/user-attachments/assets/ab1ffb53-875f-48b0-9172-50aa33974369)

# Proposed Methodology
• Step 1 : Installation of ubuntu in hyper-v

• Step 2 : Install Xschem,Ngspice and Skywater pdk

• Step 3 : Schematics creation

• Step 4 : Creating Netlist

• Step 5: Simulation & Verification of results

# EDA Tools Used

Xschem

It is an Schematic capture and netlisting EDA tool.For more details refer:

https://xschem.sourceforge.io/stefan/index.html

NgSpice

It is an Open Source Software for Spice Simulations. For more details refer:

http://ngspice.sourceforge.net/docs.html

Skywater 130nm pdk

The SkyWater Open Source PDK is a collaboration between Google and SkyWater Technology Foundry to provide a fully open source Process Design Kit and related resources, which can be used to create manufacturable designs at SkyWater’s facility.

https://github.com/google/skywater-pdk

# Circuit Details
![Ring_osc_circuit](https://github.com/user-attachments/assets/8bd769f1-74d1-429e-8c24-02f11ceb617a)

# Output Waveforms

![Ring_osc_Out3](https://github.com/user-attachments/assets/e79710bb-e4f7-469d-a9cc-1d48615362a8)

![Ring_osc_Allout](https://github.com/user-attachments/assets/de96e623-65b7-451d-a264-3ebac3c1d112)




