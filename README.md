#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM

![WhatsApp Image 2025-11-28 at 08 27 17_f0c86fd5](https://github.com/user-attachments/assets/6a46b4f7-1f8d-4b6f-9ba7-13e25d5baf56)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-28 at 08 27 17_8d0f13d5](https://github.com/user-attachments/assets/125e9c1b-2f73-41e0-9402-ef59f10c61ca)

MODEL GRAPH 
![WhatsApp Image 2025-11-28 at 08 27 18_fdfe2c98](https://github.com/user-attachments/assets/521c81aa-4672-4460-bb14-26b579c674f8)


DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 10kΩ, Rf=100kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![WhatsApp Image 2025-11-23 at 15 44 58_04571f3a](https://github.com/user-attachments/assets/894bc96d-f439-4ee9-9a4d-dd61a3d484d0)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-20 at 18 30 33_e24709ee](https://github.com/user-attachments/assets/e0e7c300-922b-4b30-bde5-1c0b6be9fbc0)

![WhatsApp Image 2025-11-20 at 18 58 01_3cdac38e](https://github.com/user-attachments/assets/3a900dda-9e9c-42b8-82b9-aed3f6960f38)





---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1



## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 08 29 56_bece1176](https://github.com/user-attachments/assets/030ecd11-f88a-446f-a1ac-16c66c21f7a6)



## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 08 30 26_9e307d7a](https://github.com/user-attachments/assets/afd78cc9-f0b4-4441-92cc-3f3dea674e57)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![WhatsApp Image 2025-11-23 at 15 45 22_b6588647](https://github.com/user-attachments/assets/2ee68025-ad80-40a4-af5a-3551ddbbd80f)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-20 at 18 55 56_1c024ca0](https://github.com/user-attachments/assets/7011014b-7aaa-4e0f-8f2d-ffd97ca414c6)


![WhatsApp Image 2025-11-20 at 18 39 57_e8b16bc2](https://github.com/user-attachments/assets/858aa124-daf7-426b-83f3-153f6e94f4ac)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 08 32 53_8eb17415](https://github.com/user-attachments/assets/84f1124f-5521-4276-9ca5-cefbe673542b)


## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 08 33 14_98c35268](https://github.com/user-attachments/assets/1b068fd0-0250-405b-b5c9-696954d54dab)


## DESIGN
vo=(-Rf/R1)(v1-v2)volts
v1=0.5
v2=1
Rf=100
Ri=100

### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)
![WhatsApp Image 2025-11-23 at 15 45 48_8789c1ac](https://github.com/user-attachments/assets/6ba43ffa-3c19-4509-96bb-cd3231b0c978)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-20 at 18 47 39_76a82f13](https://github.com/user-attachments/assets/da39aec0-1ed3-43ff-89f4-45b27fb83904)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-11-28 at 08 34 45_e54710b9](https://github.com/user-attachments/assets/7abe970a-9f59-4f2f-8e9d-7c5459126240)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-11-23 at 15 46 19_2dfa29d8](https://github.com/user-attachments/assets/91361bab-31e6-49a2-9526-775fb3667b69)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-20 at 18 51 59_08b080cc](https://github.com/user-attachments/assets/0542f237-b257-4901-8884-1509e6ae6ddd)

---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
