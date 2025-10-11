# Quantum Error Correction with Qiskit

This project delves into the theory of **quantum error correction codes (QEC)** and implements famous error correcting codes using **Qiskit**. The goal is to demonstrate how quantum information can be protected from noise through encoding, syndrome extraction, error correction, and decoding. This project is intended for educational purposes only. All references to articles and documentation are cited in the notebook.

## Implemented Codes
- **2- and 3-qubit codes**: bit-flip and phase-flip (introductory examples)
- **Shor code (9 qubits)**: protects against any single-qubit error
- **5-qubit code**: the smallest perfect QEC code.

## Workflow
Each code follows the same pipeline:
1. **Initialization**
2. **Encoding** of the logical qubit
3. **Error injection** (bit-flip, phase-flip, or both)
4. **Syndrome extraction**
5. **Error correction** (unitary)
6. **Decoding**
7. **Fidelity evaluation** (for Shor and 5-qubit codes).

## Results
This notebook demonstrates that, under ideal conditions, these codes successfully protect one qubit from an arbitrary error.

## References

Core references:

- Roffe, J. *Quantum Error Correction: An Introductory Guide*. Contemporary Physics, 2019.
- Laflamme, R., Miquel, C., Paz, J.P., and Zurek, W.H. *Perfect Quantum Error Correction Code*. Physical Review Letters, 1996.
- Qiskit Textbook (IBM).
- IBM Quantum Learning, *Foundations of Quantum Error Correction*.

For hardware context:

- Wang, X.L., Chen, L.K., Li, W., et al. *Experimental Ten-Photon Entanglement*. Physical Review Letters, 2016.
- Qiang, X., Zhou, X., Wang, J., et al. *Large-Scale Silicon Quantum Photonics Implementing Arbitrary Two-Qubit Processing*. Nature Photonics, 2018.
- Randall, J., Weidt, S., Standing, E.D., et al. *Efficient Preparation and Detection of Microwave Dressed-State Qubits and Qutrits with Trapped Ions*. Physical Review A, 2015.
- Ballance, C., Harty, T., Linke, N., et al. *High-Fidelity Quantum Logic Gates Using Trapped-Ion Hyperfine Qubits*. Physical Review Letters, 2016.
- Brandl, M.F., van Mourik, M.W., Postler, L., et al. *Cryogenic Setup for Trapped Ion Quantum Computing*. Review of Scientific Instruments, 2016.
- Debnath, S., Linke, N.M., Figgatt, C., et al. *Demonstration of a Small Programmable Quantum Computer with Atomic Qubits*. Nature, 2016.

Further readings:

- Wootters, W.K., and Zurek, W.H. *A Single Quantum Cannot Be Cloned*. Nature, 1982.
- Knill, E., and Laflamme, R. *Theory of Quantum Error-Correcting Codes*. Physical Review A, 1997.
