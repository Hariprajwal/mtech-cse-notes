<div align="center">

# 🎓 M.Tech Computer Science & Engineering — Course Vault

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Hariprajwal/mtech-cse-notes/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Hariprajwal/mtech-cse-notes)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Hariprajwal/mtech-cse-notes)

**A curated, comprehensive academic repository containing lecture slides, reference textbooks, lab sheets, handwritten & compiled notes, and exam question banks for M.Tech CSE coursework.**

---

[Explore Subjects](#-curriculum--subject-breakdown) • [Directory Tree](#-repository-structure) • [Lab Work](#-hands-on-labs--practicals) • [Contributing](#-contributing) • [License](#-license)

---

</div>

## 📌 Repository Overview

This repository acts as an all-in-one academic companion for postgraduate coursework in Computer Science and Engineering. It consolidates theoretical foundations, advanced systems engineering, high-performance computing, mathematical optimization, and quantum algorithms into a clean, searchable vault.

---

## 📚 Curriculum & Subject Breakdown

| Code | Subject | Key Focus Areas | Reference Material |
| :--- | :--- | :--- | :--- |
| **CSS 5101** | **[ADSA](#1-advanced-data-structures--algorithms-adsa)** | B-Trees, Bipartite Matching, Multithreading, Amortized Analysis | Cormen (CLRS), Lab Manuals |
| **CSS 5102** | **[ASS](#2-advanced-systems-software-ass)** | Linux Kernel Internals, VFS, Memory Management, Device Drivers, Concurrency | Robert Love, O'Reilly ULK, LDD |
| **MAT 5128** | **[CSMP](#3-computational-methods--stochastic-processes-csmp)** | Gram-Schmidt, Linear Programming, Graph Theory, Optimization | Problem Sets, Handouts |
| **CSS 5103** | **[HPCS](#4-high-performance-computing-systems-hpcs)** | Parallel Computing, OpenMP, MPI, NVIDIA CUDA Architecture | CUDA Slides, Lab Manuals |
| **CSS 5104** | **[Quantum Computing](#5-quantum-computing-quntam-computer)** | Qubits, Quantum Gates, Quantum Algorithms, Circuit Synthesis | Question Banks, Midsem Papers |

---

### 1. Advanced Data Structures & Algorithms (ADSA)
* **Directory:** [`/adsa`](./adsa)
* **Course Code:** `CSS 5101`
* **Core Topics:**
  - **Module 1 & Intro:** Advanced algorithmic analysis, asymptotic growth, recurrence relations.
  - **Module 2:** Multiway Search Trees, B-Trees (operations, splitting, merging - CLRS Ch. 18).
  - **Module 3 & 4:** Advanced graph algorithms and dynamic programming paradigms.
  - **Module 5:** Maximum Bipartite Matching, Ford-Fulkerson augmentation, Multithreaded Algorithms (work, span, scheduling).
  - **Amortized Analysis:** Aggregate analysis, Accounting method, Potential method.
* **Key Inclusions:** CLRS textbook reference, 2025 Lab Manual, detailed syllabus, and comprehensive merged revision notes.

---

### 2. Advanced Systems Software (ASS)
* **Directory:** [`/ASS`](./ASS)
* **Course Code:** `CSS 5102` / `CSS 5132`
* **Core Topics:**
  - **Kernel Architecture:** Process lifecycle, context switching, Process Scheduling (`2.1`), and Kernel Synchronization (`1.4`).
  - **Memory Subsystems:** Memory addressing, page tables, slab allocators (`kmalloc`, `vmalloc`).
  - **Virtual File System (VFS):** Inodes, dentry cache, file operations (`8 VFS`).
  - **Driver Development:** Character/block drivers, module building, system calls interface, debugging techniques.
  - **Concurrency & IPC:** Race conditions, mutexes, spinlocks, shared variable vs. message passing models.
  - **Functional Paradigms:** Introduction to Haskell concepts for systems.
* **Textbook Classics Included:**
  - *Linux Kernel Development (3rd Ed)* by Robert Love
  - *Understanding the Linux Kernel* by Daniel P. Bovet & Marco Cesati (O'Reilly)
  - *Linux Device Drivers (LDD)* by Jonathan Corbet, Alessandro Rubini, and Greg Kroah-Hartman
* **Labs:** Complete solutions for Labsheets 1 to 4 and weekly lab manuals (Weeks 2–6).

---

### 3. Computational Methods & Stochastic Processes (CSMP)
* **Directory:** [`/csmp`](./csmp)
* **Course Code:** `MAT 5128`
* **Core Topics:**
  - **Linear Algebra:** Gram-Schmidt Orthogonalization Process, vector spaces, inner products, projections.
  - **Optimization:** Linear Programming Problems (LPP), Simplex method, duality, and sensitivity analysis.
  - **Graph Theory:** Applied graph theory, trees, connectivity, and network flows.
  - **Stochastic Modeling:** Probability distributions, Markov chains, random walks, and transition probabilities.
* **Key Inclusions:** Optimization problem sets, course handout, and consolidated zero-to-exam midterm preparation notes.

---

### 4. High Performance Computing Systems (HPCS)
* **Directory:** [`/HPCS`](./HPCS)
* **Course Code:** `CSS 5103` / `CSS 5132`
* **Core Topics:**
  - **Parallel Architectures:** Flynn's taxonomy, memory hierarchies, SMP vs. NUMA, cache coherence.
  - **Shared Memory Programming (OpenMP):** Compiler pragmas, loop parallelization, synchronization constructs, false sharing.
  - **Distributed Memory Programming (MPI):** Point-to-point communication, collective operations (`MPI_Bcast`, `MPI_Reduce`, `MPI_Scatter`/`Gather`).
  - **GPU Computing (NVIDIA CUDA):**
    - CUDA programming model (Grids, Blocks, Threads, Warps).
    - Memory hierarchy: Global, Shared, Constant, and Registers.
    - Kernel execution, coalesced access patterns, and bank conflict avoidance.
* **Key Inclusions:** Multi-part CUDA slide decks, complete syllabus lesson plans, and HPCS lab manual.

---

### 5. Quantum Computing
* **Directory:** [`/quntam computer`](./quntam%20computer)
* **Course Code:** `CSS 5104` / `CSE 5025`
* **Core Topics:**
  - **Quantum Foundations:** Superposition, entanglement, Dirac notation ($|\psi\rangle$), Hilbert spaces, measurement postulate.
  - **Quantum Gates & Circuits:** Pauli-X, Y, Z, Hadamard ($H$), Phase ($S, T$), CNOT, Toffoli, and unitary matrices.
  - **Quantum Algorithms:** Deutsch-Jozsa, Grover's search, Quantum Fourier Transform (QFT), and Shor's factoring foundation.
  - **Error & Decoherence:** Quantum noise models and introductory quantum error correction.
* **Key Inclusions:** Mid-Sem examination papers (Sept 2026), Question Bank 1, Practice problem sets, and consolidated master course notes.

---

## 📂 Repository Structure

```text
mtech-cse-notes/
├── .gitignore
├── LICENSE
├── README.md
│
├── adsa/                               # Advanced Data Structures & Algorithms
│   ├── ADS Lab Manual-2025.docx
│   ├── Cormen Introduction to Algorithms.pdf
│   ├── detailed syllabus.pdf
│   └── modules/                        # B-Trees, Multithreading, Bipartite Matching
│
├── ASS/                                # Advanced Systems Software
│   ├── Course_Plan_CSS_5102_ASS.pdf
│   ├── Linux Kernel Development, 3rd Edition.pdf
│   ├── Understanding The Linux Kernel (O'Reilly).pdf
│   ├── linux_device_driver.pdf
│   ├── Flipped class slides/           # kmalloc/vmalloc, Parallel models
│   ├── Lab (1)/Lab/                    # Labsheets 1-4 & Weekly manuals
│   └── Theory/                         # Kernel Sync, Memory, VFS, System Calls
│
├── csmp/                               # Computational Methods & Stochastic Processes
│   └── Computation methods.../
│       ├── Applied Graph Theory.pdf
│       ├── Gram-Schmidt Process.pdf
│       ├── Linear Programming Problems.pdf
│       └── MAT_5128 Midterm Notes.pdf
│
├── HPCS/                               # High Performance Computing Systems
│   ├── HPCS LAB Manual.pdf
│   ├── Theory & Planning Syllabi.pdf
│   └── slides/
│       ├── OpenMP & MPI guides.pdf
│       └── CUDA/                       # CUDA Part 1, Part 2, and Architecture
│
└── quntam computer/                    # Quantum Computing
    ├── CSS_5104 Complete Combined Materials.pdf
    ├── Mid Sem Exam Question Papers.pdf
    ├── Question Banks & Practice Sets.pdf
    └── OneDrive_2026-09-27/Class Material/
```

---

## 🛠️ Hands-On Labs & Practicals

This repository contains reproducible practical resources:
* **Linux Systems Programming:** Kernel module initialization/cleanup routines, device registration (`/dev`), memory allocation tests.
* **Parallel Computing Benchmarks:** Matrix multiplication, reduction, and stencil computations implemented with OpenMP, MPI, and CUDA kernels.
* **Algorithms Implementation:** Tree balancing, max-flow implementations, and algorithmic profiling.

---

## 🤝 Contributing

Contributions to improve notes, add solution walkthroughs, or fix errata are warmly welcomed!

1. **Fork** this repository.
2. Create your feature branch (`git checkout -b feature/AddTopicNotes`).
3. Commit your changes (`git commit -m 'Add notes on Topic XYZ'`).
4. Push to your branch (`git push origin feature/AddTopicNotes`).
5. Open a **Pull Request**.

---

## 📄 License

This repository is distributed under the **[MIT License](./LICENSE)**. You are free to read, study, modify, and share these resources with proper attribution.

---

<div align="center">
  <sub>Maintained with ❤️ by <a href="https://github.com/Hariprajwal">K R Hari Prajwal</a></sub>
</div>
