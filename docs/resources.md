# Resources

## Core Implementation & Setup (Must-Have)

### 1. Open Quantum Safe (OQS) - Primary Library
- **URL**: https://github.com/open-quantum-safe/liboqs-python
- **Why Essential**: Complete Python wrapper for all NIST algorithms (Kyber, Dilithium, Falcon, SPHINCS+)
- **Beginner Value**: Auto-installs everything, simple pip install, extensive examples
- **Project Use**: Your main implementation library for Phase 1 & 2

### 2. OQS Getting Started Guide
- **URL**: https://openquantumsafe.org/liboqs/getting-started.html
- **Why Essential**: Official step-by-step setup tutorial
- **Beginner Value**: Covers installation, first benchmark, troubleshooting
- **Project Use**: Day 1 setup for entire team

### 3. PQClean Reference Implementations
- **URL**: https://github.com/PQClean/PQClean
- **Why Essential**: Clean C code for understanding algorithm internals
- **Beginner Value**: Well-documented, easy to read implementations
- **Project Use**: Phase 2 new algorithm integration

## Practical Benchmarking Frameworks

### 4. PQC-LEO Comprehensive Benchmarking Tool ⭐
- **URL**: https://github.com/crt26/pqc-evaluation-tools
- **Why Essential**: **Automated benchmarking framework** with Python scripts
- **Beginner Value**: Pre-built scripts for x86/ARM, automatic data collection
- **Project Use**: Your main benchmarking engine for Phases 1-3
- **Key Features**: CPU/memory profiling, TLS testing, result parsing

### 5. pqm4 - ARM Cortex-M4 Benchmarking
- **URL**: https://github.com/mupq/pqm4
- **Why Essential**: Industry-standard embedded benchmarking
- **Beginner Value**: Ready-to-run scripts, detailed documentation
- **Project Use**: IoT performance comparisons, alternative platform testing

## Data Analysis & Visualization

### 6. PQ-Plot Specialized Visualization ⭐
- **URL**: https://github.com/tobhe/pq-plot
- **Why Essential**: **Built specifically for PQC benchmark plotting**
- **Beginner Value**: Simple command-line tool, generates publication-ready graphs
- **Project Use**: Phase 3 visualization, creates all your performance charts

### 7. Kaggle PQC Benchmark Dataset
- **URL**: https://www.kaggle.com/datasets/ranatariq09/pqc-algorithms-benchmark-data
- **Why Essential**: **37,004+ real benchmark results** for comparison
- **Beginner Value**: Pre-processed data, validates your results
- **Project Use**: Phase 3 trend analysis, baseline for your measurements

## Quantum Attack Demonstration

### 8. IBM Qiskit Shor's Algorithm Tutorial ⭐
- **URL**: https://quantum.cloud.ibm.com/docs/en/tutorials/shors-algorithm
- **Why Essential**: **Official step-by-step RSA attack demo**
- **Beginner Value**: Copy-paste code, runs on free IBM Quantum
- **Project Use**: Phase 1 RSA vulnerability demonstration

### 9. Programming Shor's Algorithm Guide
- **URL**: https://www.qcsp.ph/programming-shors-algorithm/
- **Why Essential**: Complete implementation with RSA factorization
- **Beginner Value**: Explains every line of code, multiple examples
- **Project Use**: Team training, understanding quantum threat

## 📚 Algorithm Implementation Examples

### 10. NIST PQC Benchmarking Methodology ⭐
- **URL**: https://csrc.nist.gov/csrc/media/Presentations/2022/benchmarking-and-analysing-nist-pqc-lattice-based/images-media/session4-howe-benchmarking-analysing-pqc2022.pdf
- **Why Essential**: **Official NIST benchmarking standards**
- **Beginner Value**: Tells you exactly what to measure and how
- **Project Use**: Ensures your methodology matches academic standards

### 11. Performance Analysis Research Paper
- **URL**: https://arxiv.org/html/2503.12952v1
- **Why Essential**: **Recent 2025 study** with actual performance numbers
- **Beginner Value**: Shows expected results, validates your findings
- **Project Use**: Phase 1 baseline replication, Phase 3 comparison data

### 12. Classical Crypto Implementation Examples
- **URL**: https://mojoauth.com/encryption-decryption/ecc-192-encryption--python/
- **Why Essential**: Working RSA/ECC Python code for baseline
- **Beginner Value**: Copy-paste implementations, clear explanations
- **Project Use**: Phase 1 classical algorithm benchmarking

## Quick Start Implementation Order

### Week 1 Priority:
1. Install liboqs-python [#1] following getting started guide [#2]
2. Run Shor's algorithm demo [#8] for project motivation
3. Set up PQC-LEO benchmarking framework [#4]

### Week 2-3 Priority:
4. Use PQC-LEO [#4] to benchmark all NIST algorithms
5. Implement classical baselines using ECC guide [#12]
6. Validate results against Kaggle dataset [#7]

### Week 4-5 Priority:
7. Generate all plots using PQ-Plot [#6]
8. Follow NIST methodology [#10] for proper analysis
9. Compare findings with research paper [#11]

---
