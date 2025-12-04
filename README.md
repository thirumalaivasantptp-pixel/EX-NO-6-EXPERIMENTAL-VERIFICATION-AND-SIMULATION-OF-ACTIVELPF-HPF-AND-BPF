# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP  
         
---

## AIM
 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)

ii)	First order High Pass Filter (HPF)

iii)	Band pass filter

---

## 6 A :- LOW PASS FILTER



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
## DESIGN
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/3b5e3b35-a5a5-498f-abc0-7414af4471a9" />

## CIRCUIT DIAGRAM
<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/c3a5610c-bf77-43fd-a169-4070dbd46a6b" />
<img width="658" height="411" alt="image" src="https://github.com/user-attachments/assets/b7a67eb1-bfb2-4dd2-a90d-304093ac7e24" />




## MODEL GRAPH
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/f69d87e7-73b6-452a-b62d-c6f11df931a5" />


---




## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

| S.No | Frequency (Hz) | Output Voltage (V) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|--------------------|-----------------------------|
| 1    |     100           |   1.65                 |   4.349                          |
| 2    |    200            |  1.64                  |    4.296                         |
| 3    |    300            |  1.64                  |     4.296                        |
| 4    | 400              |   1.64                 |    4.296                         |
| 5    | 500              |   1.62                 |  4.190                           |
| 6    | 750              |   1.60                 |   4.082                          |
| 7    |   1000            |   1.54                 |   3.750                          |
| 8    |  1500             |  1.40                  |   2.992                          |
| 9    |  2000             |  1.08                  |   0.668                          |
| 10   |  2500              | 0.8                   |   -1.938                          |
| 11   |  2800              |   0.6                 |      -4.437                       |
| 12   |  3000              |  0.4                  | -7.535                            |
		

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/683a695c-a08d-49eb-9fcb-08b0da5a2893" />
<img width="658" height="411" alt="image" src="https://github.com/user-attachments/assets/64686278-9147-4e09-9036-607a217e296c" />

<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/5cd650f9-2e8a-414f-af66-52ff599f0876" />



---

 ## 6 B HIGH PASS FILTER

---

## THEORY
## HIGH PASS FILTER
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
<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/33ca5c57-8638-4df1-9acb-a33f8ffc4111" />
<img width="643" height="402" alt="image" src="https://github.com/user-attachments/assets/6a565159-9ec3-4ba6-bb98-7097d7fa64fb" />



## MODEL GRAPH
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/89b108e2-eae2-4556-b69c-1037fc3533e9" />


---



## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
| S.No | Frequency (Hz) | Output Voltage (V) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|--------------------|-----------------------------|
| 1    |   100             |   500           |     -6.020                        |
| 2    |   200             |      550              |-5.192                             |
| 3    | 300               |      640              | -3.876                            |
| 4    | 400               |      660              |  -3.609                           |
| 5    | 500               |     700               | -3.098                            |
| 6    | 750               |     740              | -2.615                            |
| 7    |1000                |      1150             | 1.214                            |
| 8    | 1500               |     1240               | 1.868                            |
| 9    |  2000              |   1350                 |  2.607                           |
| 10   | 2500               |  1450                  |  3.227                           |
| 11   | 3000               |  1540                  | 3.750                            |

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/f1321762-f8a8-454d-a4f9-113c4df6b863" />
<img width="658" height="411" alt="image" src="https://github.com/user-attachments/assets/c9b1e400-20d6-41f1-9dae-07c98e255d36" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/d5d1ecd9-451d-4eb4-b170-030c623b1fdf" />


---

 ## 6C Band Pass Filter

---

## THEORY
 ## Band Pass Filter
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

<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/21a6abb4-a3e0-4e7a-a2f9-dc452e729f51" />
<img width="659" height="412" alt="image" src="https://github.com/user-attachments/assets/23853d1d-aaff-4f7a-bae3-bf6f407a9835" />



## MODEL GRAPH

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/6425feb5-6515-4b0b-8815-eccd1b6e1b1b" />


---




## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
| S.No | Frequency (Hz) | Output Voltage (V) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|--------------------|-----------------------------|
| 1    | 50               | 0.5                   |     -6.021                        |
| 2    | 100               | 1                   |      0                       |
| 3    |200                | 1.34                   |    2.542                         |
| 4    |300                | 2.94                   |   9.367                          |
| 5    |400               |  3.12                  |    9.883                         |
| 6    |500                | 3.44                   |   10.731                          |
| 7    |750                |  3.44                  |  10.731                           |
| 8    |1000                | 3.44                   |   10.731                          |
| 9    |1300                |  3.20                  |  10.160                           |
| 10   |2000                |  2.84                  | 9.066                            |
| 11   |3000                | 2.28                   | 7.158                            |
| 12   |5000                |   1.56                 |  3.86                           |

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/3b66b6ae-ab99-493b-94b0-1bf97475afc1" />
<img width="651" height="407" alt="image" src="https://github.com/user-attachments/assets/767d77b9-97a1-4da2-b3d2-6dc1144269b1" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/1d54c33a-1bc3-4f59-8c80-dd5581af42be" />


## RESULT:

Thus an Active Low pass, High pass and Band Pass Filters are designed and tested using op-amp IC 741.
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/44d43ba0-6116-4c0e-b1e3-67128f055b41" />



   
