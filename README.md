# exp_2_mode_characteristics_of_reflex_klystron_oscillator

# Experiment 2 — Mode Characteristics of Reflex Klystron
---
## Aim

To study the mode characteristics of a reflex klystron and hence determine the mode number, transit time, electronic tuning range (ETR) and electronic tuning sensitivity (ETS).

## Equipment and Components

1. Klystron power supply MTI KP 503
2. Klystron tube / 2K25
3. Isolator MTI/NVIS-204
4. Frequency meter MTI/NVIS-205A
5. Variable attenuator MTI/NVIS-206
6. Detector mount MTI/NVIS-209
7. Waveguide stands MTI/NVIS
8. VSWR meter MTI VS 501/NVIS
9. Cathode ray oscilloscope Scientech-801C

## Experimental Setup

<img width="870" height="295" alt="image" src="https://github.com/user-attachments/assets/9a3dedfa-312f-4f45-ab30-f3a8f4bd1639" />

<img width="701" height="292" alt="image" src="https://github.com/user-attachments/assets/7d3952ea-2bb0-43d7-b35c-2a6ffff002c7" />

---

## Theory

The reflex klystron is a microwave tube used as the microwave source in the lab. It uses **velocity modulation** to convert a continuous electron beam into microwave power; its oscillation frequency can be varied over a wide band and it can be pulse- and frequency-modulated.

Electrons emitted from the cathode are accelerated through the positive resonator grid towards the reflector. The reflector is negative with respect to the cathode, so it retards and finally reflects the electrons, which turn back through the resonator grids. When the klystron oscillates a high field exists between the resonator grids: an electron crossing the gap is either accelerated or retarded as the gap voltage changes in amplitude. Accelerated electrons leave at increased velocity, retarded electrons at reduced velocity, so the electrons need different times to return — different transit times — and the returning electrons group together in **bunches**. This variation of electron velocity is velocity modulation.

As the bunches pass back through the resonator grids they interact with the gap voltage. If they arrive when the grid voltage slows them down, energy is delivered to the resonator and the klystron oscillates. The strongest oscillation occurs when the transit time in the reflector region equals **n + ¾** cycles of the resonator frequency, where *n* is an integer including zero. If the bunches arrive when the field accelerates them, energy is removed from the resonator and no oscillation occurs.

<img width="551" height="376" alt="image" src="https://github.com/user-attachments/assets/f46fd238-b33e-4b3e-a345-7f672af0752e" />

### Mechanical and Electronic Tuning

* **Mechanical tuning** changes the width of the cavity, i.e. its effective capacitance, and hence the resonant frequency. The output power stays essentially the same.
* **Electronic tuning** changes the repeller voltage, which changes the output frequency — but the output power also changes. It is quantified by the **electronic tuning sensitivity (ETS)**, obtained as the slope of the frequency characteristic of the mode.

---

## Procedure

1. Connect the components and equipment as shown in Fig. (A).
2. Keep the control knobs of the klystron power supply as follows:

   | Control | Setting |
   |---|---|
   | Mode switch | AM |
   | Beam voltage knob | Fully anti-clockwise |
   | Repeller voltage knob | Fully clockwise |
   | Meter switch | Beam current |

3. Rotate the frequency meter to one side (**rotate the frequency meter very slowly**).
4. Switch on the klystron power supply, the VSWR meter/CRO and the cooling fan for the klystron tube. Wait 1–2 minutes for the klystron to respond.
5. With the cathode voltage knob at minimum the beam voltage is about 235–300 V. Observe the beam current by switching the meter to the beam-current position. **The beam current must not exceed 30 mA** — try to set it to about 20 mA by adjusting the beam voltage knob.
6. Change the meter switch to the repeller/reflector voltage position.
7. Decreasing the reflector/repeller voltage, record the output power and the frequency.
8. To measure frequency, set the mode switch to AM and observe the output on the CRO. Use the AM amplitude and frequency controls and the oscilloscope front-panel controls to get a clear display. Rotate the frequency meter and watch for a dip in the output; note the corresponding frequency.
9. Switch on the beam voltage and rotate the beam voltage knob clockwise slowly while watching the VSWR meter; set it for maximum deflection.
10. Change the repeller voltage slowly and set it for maximum deflection on the VSWR meter.
11. Rotate the frequency meter knob slowly and stop where the output on the VSWR meter is lowest.
12. Read the frequency directly on the frequency meter, between the two horizontal fine marks.
13. Change the repeller voltage and read the power and frequency for each repeller voltage.

## Observation

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/fe98d61b-85e3-4e9c-8e04-6263a953dfdd" />


## Graph

*(Include your own graph relevant to the experiment.)*

## Precautions

1. Check the connections before switching on the kit.
2. Keep all knobs at their minimum positions before switching on the VSWR meter / klystron power supply.
3. On the klystron power supply the **HT must be OFF** before switching on the mains supply.
4. The beam knob must be fully anti-clockwise and the repeller voltage knob fully clockwise.
5. Switch on the mains and allow some warm-up time for accurate readings.
6. Make all connections properly.
7. Do not look directly into the waveguide.
8. After the experiment, switch off the mains and return all knobs to their minimum positions before leaving the bench.
9. If the mains supply fails mid-experiment, return to the initial condition — all knobs at minimum — and switch off the main switches.
10. Do not increase the repeller voltage beyond −70 V; it should stay between −70 V and 270 V.

## Conclusion

The mode characteristics of the Reflex Klystron were studied successfully. The variation of output power with repeller voltage was observed, and the different modes of oscillation were identified. The experiment verified the principle of velocity modulation and electron bunching used for microwave generation.
