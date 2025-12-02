# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
---

## AIM
            
## DATE: 27.09.2025  
         
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
<img width="836" height="455" alt="image" src="https://github.com/user-attachments/assets/e5181151-836f-4f80-8f56-53b23ff05c74" />

## SIMULATION CIRCUIT DIAGRAM
<img width="1174" height="841" alt="image" src="https://github.com/user-attachments/assets/4f161465-e278-416b-bc52-b1a7633b9ae1" />


## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---

## DESIGN

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

![WhatsApp Image 2025-11-16 at 22 30 59_eef1730c](https://github.com/user-attachments/assets/e74ac699-87db-4ea9-b467-911b9cff143e)
---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-16 at 22 31 04_3d4e1343](https://github.com/user-attachments/assets/1d50d4ea-2a09-4ae3-9b9d-7844db5e718f)

---
## SIMULATION WAVEFORM
<img width="1177" height="296" alt="image" src="https://github.com/user-attachments/assets/542a2c6b-6a05-49dc-8761-97838f2f38c3" />


 ## 6 B HIGH PASS FILTER
 ## DATE : 04.10.2025

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

<img width="660" height="343" alt="image" src="https://github.com/user-attachments/assets/f3d7466c-244d-49a8-a017-746e467feec7" />

## SIMULATION CIRCUIT DIAGRAM
<img width="1222" height="759" alt="image" src="https://github.com/user-attachments/assets/b41530dd-f7ed-40dd-8906-342266dbe128" />


## MODEL GRAPH

<img width="1250" height="558" alt="image" src="https://github.com/user-attachments/assets/54944820-2d8b-492a-bc24-3b7987b23ec0" />

---

## DESIGN

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

![WhatsApp Image 2025-11-16 at 22 31 05_3bfb6ca4](https://github.com/user-attachments/assets/a254044a-bcf1-489a-a7bc-7b97b2c76ca7)


## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-16 at 22 31 05_e24dc4a5](https://github.com/user-attachments/assets/890f00b8-1d1e-4332-958b-f58a17c0f1b6)

---

## SIMULATION WAVEFORM
<img width="1234" height="290" alt="image" src="https://github.com/user-attachments/assets/f4ae5734-fa9b-4d09-af8a-3fd5b9e63c7e" />


 ## 6C Band Pass Filter
 ## DATE : 11.10.2025

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

<img width="1068" height="446" alt="image" src="https://github.com/user-attachments/assets/ee37b95a-05ea-448c-9102-111e071e41e8" />

## SIMULATION CIRCUIT DIAGRAM
<img width="1165" height="684" alt="image" src="https://github.com/user-attachments/assets/daea5c57-8b44-4d9f-8c14-bfbb6cf16898" />


## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

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

![WhatsApp Image 2025-11-16 at 22 31 05_e3b3f274](https://github.com/user-attachments/assets/531d80ab-c7e7-4caa-973d-1b8f82e43111)
---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-16 at 22 31 06_f11bf9e4](https://github.com/user-attachments/assets/fd790afc-531d-4866-85ad-353e711662ac)

---

## SIMULATION WAVEFORM
<img width="1219" height="305" alt="image" src="https://github.com/user-attachments/assets/23ab22df-3cbb-4223-8c77-64bfb85342ed" />

##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
