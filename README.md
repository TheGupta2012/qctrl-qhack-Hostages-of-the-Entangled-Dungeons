<img src = "https://github.com/TheGupta2012/qctrl-qhack-Hostages-of-the-Entangled-Dungeons/blob/master/logo.png" width = 300 height = 180 >

# QCHack 2021 Entry

## Hostages of the Entangled Dungeons 

Q-CTRL QCHack Challenge "Hostages of the Entangled Dungeons" entry
- This repository contains the submission for the Quantum Coalition Hack 2021.
- The objective of this challenge was to make **Robust Pulses** and realize **X** and the **H** gate for qubits in the actual, noisy environments.

### Approach

- We utilised the functionalities of *Boulder Opal* and made *Robust Pulses* that accounted for **dephasing noises** and **amplitude correction**.
- These pulses were simulated on classical devices by creating artifical noise and sent out to the qubit in the cloud for testing

### Limitations

- The *Rabi rate* calculations were the major roadblock in our entry and we weren't able to calibrate the pulses fully to work on the qubit in the cloud
- The total Hamiltonian for the **H** gate was harder to figure out and that was also one of the limitations in our code.
