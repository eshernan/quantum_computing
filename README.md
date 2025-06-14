# Guide to install all requirements necessary to this workshop

1. Create a virtual environtment called qcve using <br>
    ``bash python -m venv qcve``
2. Activate the virtual env using <br>
    ``source ./qcve/bin/activate``
3.  If you are using Windows, please follow this [video guide](https://www.youtube.com/watch?v=qwQX-S42rys)
4. Install the following libs <br>
    ```bash pip install qiskit quiskit[visualization] qiskit-ibm-runtime qiskit-aer jupyter ipykernel numpy matplotlib   ```
5. Install the jupyter plugin for vscode
6. Open the ipynb file and select the correct kernel based on ve
7. Review lib by lib and execute cell by cell 

## Books List recommended categorized by area of focus


---

### 1. **General Quantum Computing**

**Books that offer a comprehensive introduction to the principles, algorithms, and architecture of quantum computers.**

**1.1.** *Quantum Computation and Quantum Information* – **Michael A. Nielsen & Isaac L. Chuang**

* Widely considered the “bible” of quantum computing.
* Covers algorithms, qubits, error correction, entanglement, and gate models in a formal and didactic way.
* Best for someone who wants a deep yet broad overview.

**1.2.** *Quantum Computing: An Applied Approach* – **Jack D. Hidary**

* More recent and practical, with a strong focus on implementation using platforms like Qiskit and Cirq.
* Includes circuit models, oracles, variational circuits, and hybrid methods.
* Good for engineers and applied researchers.

---

### 2. **Mathematical Background of Quantum Computing**

**Books focused on the mathematical foundations: Hilbert spaces, linear algebra, operators, Dirac notation, etc.**

**2.1.** *Mathematics of Quantum Computation and Quantum Technology* – **Gedik, Leung, Sanders, and Zhang (Eds.)**

* In-depth and formal. Topics include tensor products, quantum complexity theory, and algebraic structures.
* Recommended for advanced readers with a strong math background.

**2.2.** *Quantum Computing for Mathematicians* – **N. David Mermin**

* Written by a physicist for mathematicians, with rigorous development of qubit systems, gates, and measurements.
* Bridges the gap between formal mathematics and physical computation models.

---

### 3. **Quantum Machine Learning / AI for Quantum Computing**

**Books that explore how quantum algorithms can be applied to AI, and how hybrid classical-quantum systems operate.**

**3.1.** *Quantum Machine Learning: What Quantum Computing Means to Data Mining* – **Peter Wittek**

* First academic work focused solely on QML. Covers support vector machines, clustering, PCA, and more.
* Leverages mathematical foundations, suitable for research and implementation.

**3.2.** *Quantum Machine Learning: An Applied Approach* – **Santanu Ganguly**

* Practical and Qiskit-based, shows how variational circuits and quantum kernel methods apply to real-world ML problems.
* Ideal for ML practitioners looking to transition into quantum-enhanced models.

---

### 4. **Quantum Computing for Chemistry**

**Books exploring how QC solves quantum chemistry problems like electronic structure, energy states, and reaction simulation.**

**4.1.** *Quantum Chemistry and Computing for the Curious* – **Seth Lloyd, William Huggins, Jarrod McClean et al.**

* Designed for chemists and physicists. Explains how variational quantum eigensolvers (VQE) and quantum phase estimation (QPE) solve molecular Hamiltonians.
* Uses Qiskit Chemistry and actual case studies.

**4.2.** *Quantum Chemistry and Dynamics of Excited States* – **Bernd Engels**

* While more rooted in chemistry, includes sections on how quantum computing can model excited states and reaction paths.
* Valuable bridge for chemical physicists exploring computational quantum chemistry.

---

### 5. **Quantum Mechanics and Physical Foundations of QC**

**Books that link the physical basis (quantum mechanics, decoherence, measurement) with quantum computing models.**

**5.1.** *Quantum Mechanics and Path Integrals* – **Richard P. Feynman & Albert Hibbs**

* Classical text that, while not about QC directly, is essential to understanding the underlying mechanics of superposition and interference—the core of quantum computing.
* Highly recommended for a deep physical intuition.

**5.2.** *Quantum Physics for Computer Scientists* – **Noson S. Yanofsky & Mirco A. Mannucci**

* Merges the formalism of quantum physics with computer science concepts. Includes measurement theory, entanglement, and decoherence explained from an information perspective.
* Designed for CS audiences entering quantum information.
