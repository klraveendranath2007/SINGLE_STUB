# SINGLE_STUB
# Therapeutic Resonance: How Single Stubs Power RF Ablation and Hyperthermia Systems in Modern Healthcare

### Introduction
In modern hospitals, RF Ablation and Microwave Hyperthermia are frontline tools against tumors.
These systems deliver controlled electromagnetic energy to heat and destroy abnormal tissues — without surgery.

When RF or microwave signals travel through cables and electrodes into the human body, the patient’s tissue doesn’t behave like a fixed resistor.
It changes its electrical properties as temperature rises.

This creates impedance mismatch and reflected power, leading to:

* Unstable heating zones

* Reduced treatment efficiency

* RF amplifier stress

**Solution:** A Single Stub Matching Network—a simple yet powerful transmission-line-based circuit—tunes the system in real-time to maintain perfect energy delivery.

### Theory of Single Stub Matching
A transmission line of characteristic impedance Z<sub> 0 </sub> feeds a load Z<sub> L </sub>.

If z<sub> L </sub> ≠ Z<sub> 0 </sub>, part of the signal is reflected.

<img width="121" height="58" alt="image" src="https://github.com/user-attachments/assets/837b7cb4-7c1b-430d-94e5-a4d8f9a17bcc" />

The power delivered to the load is:
<img width="130" height="41" alt="image" src="https://github.com/user-attachments/assets/b3c09129-b050-4597-916e-8c37c4ad1431" />

For maximum power transfer,<img width="133" height="32" alt="image" src="https://github.com/user-attachments/assets/082b9f4f-6e66-4f6d-94ab-b792a2f9d50d" />


### Single Stub
<img width="385" height="173" alt="image" src="https://github.com/user-attachments/assets/52615da9-e0e3-4f6b-be4e-f34805ef14d9" />

A stub is a short section of transmission line (either short- or open-circuited) connected in parallel (shunt) at a certain distance from the load.

It introduces a susceptance 𝑗𝐵 which cancels out the reactive part of the transformed load admittance.

<img width="139" height="35" alt="image" src="https://github.com/user-attachments/assets/13a1e909-cc35-4983-b0ed-97e9602d0d62" />

Thus achieving impedance matching.

Two design parameters:

* Distance of stub from load (𝑑)
* Length of stub (𝑙)

#### Analytical Derivation
For a load Z<sub> L </sub>, after a length d:
<img width="158" height="61" alt="image" src="https://github.com/user-attachments/assets/d147eb05-dd23-4bf0-ba5d-c2eecb7ad196" />

Convert to admittance <img width="119" height="38" alt="image" src="https://github.com/user-attachments/assets/33a59599-bc79-4798-9100-710ec1dc9bfa" />

Add stub susceptance 𝑗𝐵𝑠𝑡𝑢𝑏 such that: <img width="150" height="39" alt="image" src="https://github.com/user-attachments/assets/1e41ab06-bfc4-4d2e-b992-5b12b901529b" />

If the stub is short-circuited,
<img width="126" height="60" alt="image" src="https://github.com/user-attachments/assets/4da1f456-c8cc-4940-969a-5c5483e7d639" />

where 𝑙 is the stub length.

Design involves solving for 𝑑 and 𝑙 using Smith Chart or analytical equations.









	​
