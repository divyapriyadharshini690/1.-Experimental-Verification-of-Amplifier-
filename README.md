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
		
 



### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM

![WhatsApp Image 2025-12-03 at 22 31 08_9cb6e9f8](https://github.com/user-attachments/assets/7f22d346-179b-4740-90e8-2fc2a074cf18)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-12-03 at 22 31 34_07ea1361](https://github.com/user-attachments/assets/c717600b-3908-4aaf-8a08-61a1af66e0f2)



MODEL GRAPH 
![WhatsApp Image 2025-12-03 at 22 32 58_03545151](https://github.com/user-attachments/assets/56fe448b-ab83-4adb-91aa-1ca7d7275110)


DESIGN:
![WhatsApp Image 2025-12-03 at 22 34 58_bfcc4e60](https://github.com/user-attachments/assets/f328a8a7-f455-45d9-9fe3-b9fa32d4c251)


![WhatsApp Image 2025-12-03 at 22 42 53_8e10f3a4](https://github.com/user-attachments/assets/9a292291-bec6-4d9a-b594-5c7dae965f68)

Inverting amplifier:



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
![WhatsApp Image 2025-12-03 at 22 35 35_6359290a](https://github.com/user-attachments/assets/bdb7f097-cb8a-4eae-b7d4-12b21fe24ba0)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-03 at 22 36 17_34c481a5](https://github.com/user-attachments/assets/30499831-6ec6-466b-b984-d57064c88974)

![WhatsApp Image 2025-12-03 at 22 36 49_dcf35515](https://github.com/user-attachments/assets/7765a7d4-556f-4298-aa97-40dc0c24ccff)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1



## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-03 at 22 46 11_a1952106](https://github.com/user-attachments/assets/c084a994-fa3b-4171-9266-db8f0ef2bbc7)
![WhatsApp Image 2025-12-03 at 22 54 39_1afcaed6](https://github.com/user-attachments/assets/aa381db3-d927-432d-a8c7-44fadac85b6c)



## MODEL GRAPH
![WhatsApp Image 2025-12-03 at 22 52 10_6dedc4d5](https://github.com/user-attachments/assets/b7810a51-16da-4181-be23-dc1213eba2a1)

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
![WhatsApp Image 2025-12-03 at 22 44 39_8eaf5e48](https://github.com/user-attachments/assets/8f3025b9-a88a-49db-ac41-7f875e043156)

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-03 at 22 53 00_5db76836](https://github.com/user-attachments/assets/568411fc-c900-4764-9ee4-3079d883702b)
![WhatsApp Image 2025-12-03 at 22 49 08_97273947](https://github.com/user-attachments/assets/6f3c353e-7b3c-4796-b239-eb9e32a5e9c5)



## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-03 at 23 00 23_b372f61a](https://github.com/user-attachments/assets/a8f8908e-95f6-4f8e-a325-ba1317591707)

## MODEL GRAPH
![WhatsApp Image 2025-12-03 at 23 01 27_9304ca0e](https://github.com/user-attachments/assets/0730ce0d-4976-4702-b0b9-44dc7d73e318)

## DESIGN
![WhatsApp Image 2025-12-03 at 22 57 55_05e41e17](https://github.com/user-attachments/assets/c85400c1-2c2a-4159-818e-42f3f1077f72)
![WhatsApp Image 2025-12-03 at 23 02 40_f68611fa](https://github.com/user-attachments/assets/7cb497b8-1250-4af8-bc79-eafe66093b3f)

### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 10kOhm, Rf = 100kOhm

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
![WhatsApp Image 2025-12-03 at 22 57 27_2ef9be60](https://github.com/user-attachments/assets/54aa0c6c-f352-4c72-84f3-33e128189af3)

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-03 at 22 59 13_3b456292](https://github.com/user-attachments/assets/7b11ba51-65b5-4010-91cc-500e98c4134c)

## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-12-03 at 23 04 01_c7fcea49](https://github.com/user-attachments/assets/402f2e16-5abb-4370-a782-f48c7a574d11)
![WhatsApp Image 2025-12-03 at 23 09 49_cdd8917c](https://github.com/user-attachments/assets/49cf8567-f54f-41df-a579-36ce0dedc9c7)


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
![WhatsApp Image 2025-12-03 at 23 04 17_0b77e639](https://github.com/user-attachments/assets/e7b2ba88-eecc-4d6a-96df-cad3f249eaa0)

![WhatsApp Image 2025-12-03 at 23 06 08_a74fc3fe](https://github.com/user-attachments/assets/bddae12c-939f-4487-a4ce-362e80d478da)


## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-03 at 23 05 08_ef176f02](https://github.com/user-attachments/assets/6384ef1f-7794-4f6c-9d22-b2df1201529a)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
