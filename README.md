# Post-Quantum Cryptography Performance Analysis

## 📌 Overview  
This project benchmarks classical cryptographic algorithms (RSA, ECC) against standardized and emerging Post-Quantum Cryptography (PQC) algorithms like Kyber, Dilithium, and Falcon.  
It’s divided into three phases:
1. **Replicate** existing benchmarks to learn the process.  
2. **Benchmark** new or less-explored PQC algorithms.  
3. **Analyze trends** and visualize how performance and security characteristics are changing over time.

---

## 🧠 Project Structure
```
.
├── benchmarks
│   ├── classical       # RSA, ECC benchmarking scripts
│   ├── pqc             # Kyber, Dilithium, Falcon benchmarking scripts
│   └── new             # New/experimental PQC algorithms
├── data
│   ├── raw             # Unprocessed benchmark data
│   └── processed       # Cleaned and analyzed data
├── visualizations      # Graphs, charts, and performance comparisons
├── docs                # Project notes, references, guides
├── paper               # Research paper drafts, bibliography
├── README.md
├── .gitignore
└── requirements.txt
```

---

## 🧰 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/pqc-benchmarking.git
cd pqc-benchmarking
```

### 2. Install Requirements
```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Install liboqs (Open Quantum Safe)
Follow [liboqs installation guide](https://github.com/open-quantum-safe/liboqs).  
Once installed, ensure the Python bindings are set up:
```bash
pip install oqs
```

---

## 🧪 Example Benchmark Command

Run a sample benchmark to compare RSA vs Kyber:
```bash
python benchmarks/classical/rsa_benchmark.py
python benchmarks/pqc/kyber_benchmark.py
```

Process and visualize results:
```bash
python visualizations/plot_results.py
```

---

## 📚 Useful Resources

- **Research Papers (Free)**
  - NIST PQC Standardization: [https://csrc.nist.gov/projects/post-quantum-cryptography](https://csrc.nist.gov/projects/post-quantum-cryptography)
  - Kyber, Dilithium, Falcon Papers: [https://pq-crystals.org](https://pq-crystals.org)
- **Video Tutorials**
  - Open Quantum Safe Overview: [https://www.youtube.com/watch?v=3mA7l8_NwAw](https://www.youtube.com/watch?v=3mA7l8_NwAw)
  - PQC Benchmarking Example: [https://www.youtube.com/watch?v=rbObU6Rzx8E](https://www.youtube.com/watch?v=rbObU6Rzx8E)
- **Code Examples**
  - liboqs GitHub: [https://github.com/open-quantum-safe/liboqs](https://github.com/open-quantum-safe/liboqs)
  - Qiskit for Shor's Algorithm: [https://qiskit.org/documentation/tutorials/algorithms/05_shor.html](https://qiskit.org/documentation/tutorials/algorithms/05_shor.html)

---

## 👥 Team Roles
- **Project Lead** – Oversees timeline, ensures integration between tasks  
- **Benchmarking Leads (Classical/PQC)** – Run and document algorithm tests  
- **Data & Visualization** – Clean data, plot trends, summarize results  
- **Documentation & Writing** – Manage references, draft research paper  
- **Exploration** – Investigate new PQC algorithms and integrate benchmarks

---

## 📅 Timeline (5 Weeks)
- **Week 1:** Setup, environment, replicate existing benchmarks  
- **Weeks 2–3:** Benchmark classical and PQC algorithms, collect data  
- **Weeks 4–5:** Add new algorithms, analyze trends, produce figures and paper draft
