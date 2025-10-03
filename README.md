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
## 👥 Team Roles


| Role | Description |
|------|-------------|
| **Project Lead / Research Coordinator** | Oversees project progress, ensures deadlines are met, coordinates between sub-teams, and integrates all work. Also contributes to benchmarking when needed. |
| **Classical Algorithms Lead** | Focuses on RSA/ECC benchmarks, writes scripts for key generation, encryption/decryption, signing/verification, and prepares data for analysis. |
| **Post-Quantum Algorithms Lead** | Handles Kyber, Dilithium, Falcon benchmarks, ensures proper setup of liboqs, runs experiments, and collects results. |
| **New/Experimental PQC Researcher** | Investigates and benchmarks newer PQC algorithms not widely studied, documents results, and compares them with established algorithms. |
| **Data & Visualization Specialist** | Cleans raw benchmark data, performs statistical analysis, generates graphs/charts, and prepares visual summaries for reports and presentations. |
| **Documentation & Paper Lead** | Maintains project documentation, writes research reports, keeps references, drafts the final paper, and ensures reproducibility of experiments. |

---

## 📅 Timeline (5 Weeks)
- **Week 1:** Setup, environment, replicate existing benchmarks  
- **Weeks 2–3:** Benchmark classical and PQC algorithms, collect data  
- **Weeks 4–5:** Add new algorithms, analyze trends, produce figures and paper draft
