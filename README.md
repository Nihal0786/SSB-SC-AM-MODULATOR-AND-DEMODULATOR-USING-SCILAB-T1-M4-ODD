# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# SSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM
<img width="960" height="1280" alt="82e500f4-ec18-48ed-aa35-43492ceadf41" src="https://github.com/user-attachments/assets/627a9f69-0170-45a2-90a7-2278ef463781" />
<img width="960" height="1280" alt="f34cb31d-8c93-4b37-986d-9c686cb04e65" src="https://github.com/user-attachments/assets/3b1692d5-8287-40be-afef-5b5a198ae977" />
<img width="960" height="1280" alt="2c19058e-d446-45ca-84e5-a8985eb9b355" src="https://github.com/user-attachments/assets/2324e0da-bb1d-41cd-a47e-62d260f1d002" />
<img width="960" height="1280" alt="33a35d98-e44c-4cae-b900-ae65614fa96f" src="https://github.com/user-attachments/assets/e65d8bb9-09ed-413f-a2a5-2c6d6ff718f7" />
<img width="960" height="1280" alt="d1a89d75-18cd-41fc-aa46-deab926a1ba9" src="https://github.com/user-attachments/assets/55353e17-4943-4c13-9e4b-81b90e4f0952" />


### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION

| Sl. No. | SIGNAL                 | AMPLITUDE (V) | FREQUENCY (Hz) |
| ------- | ---------------------- | ------------- | -------------- |
| **1**   | **Message Signal**     | **Theory:**   | **Practical:** |
|         |                        |               | **Theory:**    |
|         |                        |               | **Practical:** |
| **2**   | **Carrier Signal**     | **Theory:**   | **Practical:** |
|         |                        |               | **Theory:**    |
|         |                        |               | **Practical:** |
| **3**   | **Modulated Signal**   | **Practical** |                |
|         |                        | **Emax =**    |                |
|         |                        | **Emin =**    |                |
| **4**   | **Demodulated Signal** | **Practical** |                |

---

## MODEL GRAPH

<img width="960" height="1280" alt="c9e67a88-5121-48fc-9a08-00c9c4fce2ce" src="https://github.com/user-attachments/assets/2123adbd-117c-4a34-8fd8-59cc7713eb69" />

