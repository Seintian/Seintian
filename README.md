# Hi, I'm Christian Santarelli 👋

## Computer Scientist & Systems Software Engineer

I'm a computer scientist specializing in low-level systems programming, high-performance telemetry, and distributed architectures. I'm currently completing my B.Sc. in Computer Science at the **University of Turin**, with academic research on Linux kernel observability (HPC4AI) and teaching experience in algorithms and data structures.

---

## 🔭 What I'm Working On

- **YATAL** — a high-performance, Linux-native telemetry daemon in Rust for the HPC4AI datacenter cluster (my bachelor's thesis research)
- Low-level systems libraries: lock-free IPC, NUMA-aware memory management
- Compilers, operating systems, and system libraries

## 🛠️ Tech Stack

**Languages** — C · Rust · Java · Python · JavaScript / TypeScript · C# · PHP

**Frontend** — React · Next.js · Tailwind CSS · Bulma CSS · Bootstrap · jQuery

**Backend & Cloud** — Spring Boot · Docker · PostgreSQL · FastAPI · Flask · Kubernetes

**Core CS** — Linux Systems & io_uring · Algorithms & Data Structures · Operating Systems · Compilers · NUMA Architectures · Data Analysis

**DevOps & Tools** — Git · Make · CMake · InfluxDB · Grafana · Prometheus

---

## 🚀 Featured Projects

### [YATAL: Linux Telemetry Daemon for HPC & AI](https://github.com/alpha-unito/yatal)

High-performance, Linux-native telemetry daemon engineered in Rust for the HPC4AI datacenter cluster. Bridges synchronous hardware scraping with asynchronous network pipelines, featuring zero-allocation hot paths, Linux kernel `io_uring`, and temporal drift sentinels.

`Rust` `Linux Systems` `io_uring` `Tokio` `jemalloc` `InfluxDB`

### [librbipc: Lock-Free Shared-Memory Ring Buffer IPC](https://github.com/Seintian/librbipc)

High-throughput, sub-microsecond MPMC shared-memory ring buffer IPC library in ISO C23 for Linux. Features 4-tier hybrid synchronization, 0.13% idle CPU via `futex2`, race-free crash resilience with `pidfd_open`, and 50M+ msgs/s vector batching.

`C23` `Linux Systems` `Shared Memory` `Lock-Free` `Futex` `AVX2 / SIMD`

### [libnumakit](https://github.com/Seintian/libnumakit)

Advanced system library written in C (built with CMake) for memory management on NUMA architectures. Includes low-level task pooling, scheduling, and memory migration logic.

`C` `CMake` `NUMA` `IPC`

### [Formal Languages & Compilers](https://github.com/Seintian/unito-formal-languages-and-compilers-25-26)

Compiler developed from scratch in Java: lexical analyzer (Lexer), top-down LL(1) parser, semantic analysis via SDT, and JVM bytecode generation.

`Java` `Compilers` `JVM` `Parsers`

### [POSIX Operating Systems Simulation](https://github.com/Seintian/unito-operative-systems-24-25)

Complex multi-process simulation in C for POSIX environments, leveraging advanced IPC primitives (Message Queues, Shared Memory, Semaphores) for secure concurrency management and node synchronization.

`C` `POSIX` `IPC` `Multithreading` `Makefile`

### [WinHUD](https://github.com/Seintian/WinHUD)

Desktop application for Windows in C# (.NET/WPF) implementing a customizable overlay for real-time monitoring of hardware data and system performance.

`C#` `.NET 10` `WPF`

### [GreenHabits (Web Technologies)](https://github.com/Seintian/unito-web-technologies-25-26)

Full-stack web platform with enterprise architecture: Java Spring Boot backend, React/Vite (TS) frontend, PostgreSQL, fully containerized with Docker, and advanced monitoring with Grafana and Prometheus.

`Java` `Spring Boot` `React` `Docker` `PostgreSQL`

### [School Outreach Portal (HCI)](https://github.com/Seintian/unito-human-computer-interaction-25-26)

High-fidelity, accessible web portal for the Department of Computer Science (UniTo) aggregating outreach activities for schools.

`React` `TypeScript` `Vite` `Bootstrap` `UX/UI Design`

### [HCI Anime Data Storytelling](https://github.com/Seintian/unito-hci-data-analysis-25-26)

Data processing and analysis pipeline in Python (Pandas, Jupyter) based on a massive dataset (+130M data points) from the anime industry, including ETL, anomaly treatment, feature engineering, and EDA.

`Python` `Pandas` `PyArrow` `Jupyter` `Data Analysis`

### [Gym Management System (Freelance)](https://github.com/Seintian/gym-management-system)

Bespoke management platform for a local fitness center with a dual-interface architecture: public website and secure staff dashboard. Built with Vanilla PHP, jQuery, and Bulma CSS.

`Vanilla PHP` `MySQL` `jQuery` `Bulma CSS` `Session API`

---

## 🎓 Education & Research

- **BSc in Computer Science (180 ECTS)** — University of Turin (2023–2026)
  - *Bachelor's Thesis:* Comprehensive Datacenter Usage and Sensor Monitoring (YATAL) — real-time Linux telemetry daemon for the HPC4AI supercomputing infrastructure
- **High School Diploma in Scientific Studies** — Liceo Scientifico Maria Curie, Pinerolo (2018–2023)

---

## 💼 Experience

- **Academic Tutor & Algorithmic Assessment Designer** — University of Turin (Apr 2026 – Sep 2026)
  - Designed automated grading exercises on Moodle (CodeRunner), including a 4–5 stage guided composite exercise on an advanced Rabin-Karp variant with rigorous test suites and anti-brute-force validation.
- **Laboratory Teaching Assistant / Academic Tutor** — University of Turin (Oct 2025 – Dec 2025)
  - Tutored ~100 students in Algorithms & Data Structures; supervised programming sessions, code reviews, Valgrind debugging, and complexity analysis.
- **Full-Stack Software Developer** — Powerline 2.0, Freelance (Aug 2023 – May 2024)
  - End-to-end design and development of a dynamic web platform for a fitness center (PHP, MySQL, JavaScript, Bulma CSS), including GDPR-compliant data handling.

---

## 📫 Get in Touch

- **Email:** [seintian@altervista.org](mailto:seintian@altervista.org)
- **LinkedIn:** [Christian Santarelli](https://linkedin.com/in/christian-santarelli-4290ab19a/)
- **Portfolio:** [seintian.altervista.org](https://seintian.altervista.org)
