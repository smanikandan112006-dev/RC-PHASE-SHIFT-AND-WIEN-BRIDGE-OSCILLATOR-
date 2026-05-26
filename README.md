# RC PHASE SHIFT AND WIEN BRIDGE OSCILLATOR
## AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-amp.

## APPARATUS REQUIRED:
| S.No | Name of the Apparatus            | Range           | Quantity |
|-----|----------------------------------|-----------------|----------|
| 1   | Function Generator               | 3 MHz           | 1        |
| 2   | DSO                              | 30 MHz          | 1        |
| 3   | Dual RPS                         | (0 – 30) V      | 1        |
| 4   | Op-amp                           | µA741           | 1        |
| 5   | Bread Board                      | -               | 1        |
| 6   | Resistors                        | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
| 7   | Capacitor                        | 0.1 µF          | 3        |
| 8   | Connecting wires and probes      | As required     | -        |

## THEORY:
## RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .

## WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC

## CIRCUIT DIAGRAM:
## WIEN BRIDGE

<img width="570" height="480" alt="image" src="https://github.com/user-attachments/assets/4a8aa73e-4d61-4c11-b62f-b503a95bca39" />

## RC PHASE SHIFT
<img width="931" height="467" alt="image" src="https://github.com/user-attachments/assets/2e4612c3-0558-41a9-98b8-eee02391e262" />

## MODEL GRAPH:
## WEIN BRIDGE
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/4a12ff9e-1c4f-4c2d-96e9-6486a4034426" />

## RC PHASE SHIFT
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/9415e086-a465-454d-8812-01a0708beb25" />

## TABULATION
## WEIN BRIDGE:

| S.NO | Amplitude (Volts) | Time Period (ms) | Frequency (Hz) |
|------|-------------------|------------------|----------------|
| 1    |         2.32          |         20.1         |      49.98          |

##

## RC PHASE SHIFT

| S.NO | Amplitude (Volts) | Time Period (ms) | Frequency (Hz) |
|------|-------------------|------------------|----------------|
| 1    |        9.60           |       634           |  1.58              |

## DESIGN:
## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ

## PROCEDURE
PROCEDURE:
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude

## OUTPUT

RC PHASE SHIFT:
##

<img width="1489" height="1144" alt="WhatsApp Image 2026-05-25 at 11 45 32 PM" src="https://github.com/user-attachments/assets/1c062463-ef84-4008-abd0-91c76ac84bca" />

##

WEIN BRIDGE OSCILLATOR:
##

<img width="1495" height="1137" alt="WhatsApp Image 2026-05-25 at 11 39 36 PM" src="https://github.com/user-attachments/assets/7312c52b-e78e-4480-9a81-cba28f4706b2" />

##

## RESULT
Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.



