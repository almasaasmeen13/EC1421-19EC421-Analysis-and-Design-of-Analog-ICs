# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## RC PHASE SHIFT AND WIEN BRIDGE OSCILLATOR

## AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-amp.

## APPARATUS REQUIRED:
<img width="933" height="270" alt="image" src="https://github.com/user-attachments/assets/4f7bc183-2ed0-4591-b9aa-846127704eee" />

## THEORY:
### RC PHASE SHIFT OSCILLATOR:
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
### WIEN BRIDGE:
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC

## CIRCUIT DIAGRAM:
### RC PHASE SHIFT OSCILLATOR:
![WhatsApp Image 2025-11-23 at 14 37 24_524d551e](https://github.com/user-attachments/assets/671e71be-e0e2-460c-86e7-d58e57f05eee)

### WEIN BRIDGE:
![WhatsApp Image 2025-11-23 at 14 37 46_c1b6d8b4](https://github.com/user-attachments/assets/889c3cae-780c-4c19-afd6-3a4cc9c4cf17)

## MODEL GRAPH:
### RC PHASE SHIFT OSCILLATOR AND WEIN BRIDGE :
![WhatsApp Image 2025-11-23 at 14 38 10_81025bbd](https://github.com/user-attachments/assets/7deb20aa-02b4-4f9d-a4d9-36364ce1a750)

## PROCEDURE:
1. Connect the circuit as shown in fig. With the design values.
2. Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3. Measure the output wave frequency and amplitude.
   
## DESIGN:
<img width="645" height="758" alt="image" src="https://github.com/user-attachments/assets/d2e7cd3f-8c88-44aa-8ac3-807b92beabba" />

## TABULATION:

![WhatsApp Image 2025-11-23 at 14 38 30_bbcff61d](https://github.com/user-attachments/assets/0738aa1d-87dd-4d21-b2df-9b06dd80eb05)

## GRAPH:
![WhatsApp Image 2025-11-23 at 14 38 53_13b04772](https://github.com/user-attachments/assets/6f69f1a9-00f8-4c84-bdeb-d850e3743874)

## RESULT:
Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.

