# Qiskit Global Summer School 2025
### *The Past, Present and Future of Quantum Computing*

Completed labs from IBM's **Qiskit Global Summer School 2025** — a two-week intensive programme led by IBM Quantum experts including John Preskill (Caltech), David DiVincenzo (IBM Quantum), Barbara Terhal (RWTH Aachen), and Jerry M. Chow (IBM Quantum). The programme covered the full arc of quantum computing, from foundational theory to state-of-the-art error correction techniques, with hands-on execution on real IBM quantum hardware.

> **Certificate of completion awarded.** All core labs and the final challenge completed.

---

## Labs

| Lab | Topic |
|-----|-------|
| `lab0.ipynb` | **Hello Quantum World** — IBM Quantum platform setup, Qiskit 2.0 introduction, running first quantum circuits on real hardware |
| `lab1.ipynb` | **Quantum Foundations** — Quantum mechanics history, qubit representation, quantum gates, and foundational quantum algorithms |
| `lab2.ipynb` | **Quantum Algorithms** — Core algorithms including interference, entanglement, and algorithm design patterns in Qiskit |
| `lab3.ipynb` | **Noise & Error Mitigation** — Characterising noise in NISQ devices, error mitigation strategies, and techniques for improving circuit fidelity |
| `lab4.ipynb` | **Quantum Error Correction** — Classical vs quantum error correcting codes, Steane code implementation, syndrome decoding on real hardware |

---

## Final Challenge

Sample-Based Quantum Diagonalization (SQD) — approximating ground state energy of a quantum chemistry Hamiltonian using a hybrid quantum-classical approach. Implementation of the qLDPC Gross code for fault-tolerant quantum error correction.

---

## Key Concepts Covered

- Qiskit 2.0 and IBM Quantum Platform
- Quantum circuit design and transpilation
- Noise characterisation and error mitigation (ZNE, PEC)
- Quantum error correcting codes — Steane [[7,1,3]] code
- Syndrome measurement and decoding
- Sample-Based Quantum Diagonalization (SQD)
- qLDPC codes and fault-tolerant quantum computing

---

## Setup

```bash
pip install qiskit qiskit-ibm-runtime qiskit-aer qiskit-addon-sqd
```

An IBM Quantum account is required to run circuits on real hardware. Set up credentials:

```python
from qiskit_ibm_runtime import QiskitRuntimeService
QiskitRuntimeService.save_account(channel="ibm_quantum_platform", token="YOUR_API_KEY")
```

---

## About QGSS 2025

- **Dates:** July 7–22, 2025
- **Format:** Fully virtual, 18 lectures + 17 lab sessions
- **Theme:** International Year of Quantum Science and Technology
- **Platform:** qBraid Lab + IBM Quantum hardware
- **Registrants:** 8,100+ from 100+ countries
