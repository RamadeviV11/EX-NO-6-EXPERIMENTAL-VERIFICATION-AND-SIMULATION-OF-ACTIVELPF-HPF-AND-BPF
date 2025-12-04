# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![20251204_005723](https://github.com/user-attachments/assets/ce34d081-2c7f-4a08-b0d6-1de6af16ae69)

## SIMULATION CIRCUIT DIAGRAM
![20251204_005748](https://github.com/user-attachments/assets/a7219f76-7533-4e88-8170-7b0f995a057b)

## MODEL GRAPH
![20251204_005907](https://github.com/user-attachments/assets/b4aa65c7-7476-4b68-8837-44efc5e250f5)

---

## DESIGN
![WhatsApp Image 2025-12-04 at 15 43 38_5a79b824](https://github.com/user-attachments/assets/46f4cbd8-33b9-449a-b1e3-a337fd1dfcbc)

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![20251204_005929](https://github.com/user-attachments/assets/57c81e3d-89aa-4b2f-a078-b47fd6e88c0d)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![20251204_005841](https://github.com/user-attachments/assets/61ac999b-ca94-4677-aec6-204d3ff8132f)
![20251204_005821](https://github.com/user-attachments/assets/1dc179af-e645-47f7-9ac9-f6805b86e36d)
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/ba7cec7c-0429-46b5-80a9-22eb26eb6f9d" />

---

 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM
![20251204_010034](https://github.com/user-attachments/assets/01b18799-e69d-4f7c-b4bb-7387e61e4e38)

## SIMULATION CIRCUIT DIAGRAM
![20251204_010052](https://github.com/user-attachments/assets/f072a03a-0e20-48f1-bf67-39f8c5533830)

## MODEL GRAPH
![20251204_010209](https://github.com/user-attachments/assets/b951be27-0cd8-422e-ad87-83bb7c81dffd)

---

## DESIGN
![20251204_010256](https://github.com/user-attachments/assets/739ebc18-d7fe-4763-bb13-075004f1c310)

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![WhatsApp Image 2025-12-04 at 15 55 42_03eb83b1](https://github.com/user-attachments/assets/06fcf66a-776a-401c-b1f7-38f0d3127d9d)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![20251204_010130](https://github.com/user-attachments/assets/3cea2ce2-0ec5-457b-8cf6-3b6163cd78d7)
![20251204_010103](https://github.com/user-attachments/assets/1c202ffe-61a6-49c3-a04b-5a2622ebfd17)
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/e9a5da2e-04d4-4327-ac34-b8a705512c1c" />

---

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM
![20251204_010401](https://github.com/user-attachments/assets/2f4df266-ca44-464c-9eae-acb9c82dd339)

## SIMULATION CIRCUIT DIAGRAM
![20251204_010415](https://github.com/user-attachments/assets/c259b058-5b21-4ed7-85cd-e805bb1299d0)

## MODEL GRAPH
![20251204_010506](https://github.com/user-attachments/assets/4abf2f54-07bd-4fd9-bca3-e55d20aad7c0)

---

## DESIGN
![20251204_010623](https://github.com/user-attachments/assets/70ad5e02-7db6-4dee-8ee9-e4afb0e79af1)

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-12-04 at 15 55 42_a3f455d5](https://github.com/user-attachments/assets/b5157102-f301-4fbe-944a-8a9a6470e6f5)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![20251204_010439](https://github.com/user-attachments/assets/e28fe75d-021b-4a43-b7ed-2649409566d2)
![20251204_010423](https://github.com/user-attachments/assets/87b7e64e-2427-4593-b636-9032a55afe85)
<img width="784" height="339" alt="image" src="https://github.com/user-attachments/assets/d3e37bd6-ecf8-49c1-b2a0-22accfd9b04f" />

---
##RESULT:

![20251204_010538](https://github.com/user-attachments/assets/62304938-fce4-4357-9a22-c75bfd9fc416)
![20251204_010430](https://github.com/user-attachments/assets/db249e90-5794-48f1-8399-83c5c7650f01)

	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
