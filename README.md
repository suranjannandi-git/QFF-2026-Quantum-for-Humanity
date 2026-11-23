# QFF 2026 - Quantum for Humanity

Jupyter notebooks with Qiskit examples for learning quantum computing concepts.

## Notebook summaries

| Notebook | Summary |
| --- | --- |
| [ex1.1-single-qubit.ipynb](ex1.1-single-qubit.ipynb) | Builds a one-qubit circuit, applies gates, and visualizes states and measurement outcomes. |
| [ex2.1-multi-qubit.ipynb](ex2.1-multi-qubit.ipynb) | Demonstrates multi-qubit circuits, gate operations, and state simulation. |
| [ex2.2-multi-qubit-toffoli.ipynb](ex2.2-multi-qubit-toffoli.ipynb) | Uses the three-qubit Toffoli gate and inspects the resulting unitary and statevector. |
| [ex3.1-bell-state-entanglement.ipynb](ex3.1-bell-state-entanglement.ipynb) | Creates Bell states, plus GHZ and W states, and compares their measurement results. |
| [ex4.1-circuit-optimization.ipynb](ex4.1-circuit-optimization.ipynb) | Explores gate ordering, equivalent circuits, depth, decomposition, and transpilation. |
| [ex5.1-circuit-execution.ipynb](ex5.1-circuit-execution.ipynb) | Runs an end-to-end 12-qubit circuit using Aer and visualizes correlations and probabilities. |
| [ex6.1-hello_ibm_quantum.ipynb](ex6.1-hello_ibm_quantum.ipynb) | Builds an n-qubit GHZ state and executes it through the IBM Quantum Runtime. |
| [ex6.2-execute-circuit-on-ibmq.ipynb](ex6.2-execute-circuit-on-ibmq.ipynb) | Demonstrates the end-to-end 12-qubit workflow, including transpilation and Aer execution. |

## Setup

The notebooks use Qiskit and Qiskit Aer. Run this in a notebook first:

```bash
%pip install qiskit qiskit_aer pylatexenc matplotlib
```

The IBM Quantum example also requires:

```bash
%pip install qiskit_ibm_runtime
```