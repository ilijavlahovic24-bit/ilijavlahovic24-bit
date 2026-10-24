<pre>
.___.__  .__     __         ____   ____.__         .__                .__        
|   |  | |__|   |__|____    \   \ /   /|  | _____  |  |__   _______  _|__| ____  
|   |  | |  |   |  \__  \    \   Y   / |  | \__  \ |  |  \ /  _ \  \/ /  |/ ___\ 
|   |  |_|  |   |  |/ __ \_   \     /  |  |__/ __ \|   Y  (  <_> )   /|  \  \___ 
|___|____/__/\__|  (____  /    \___/   |____(____  /___|  /\____/ \_/ |__|\___  >
            \______|    \/                       \/     \/                    \/ 
</pre>

```
ilija@etf-belgrade
-------------------
name      : Ilija Vlahović
role      : CS student, Faculty of Electrical Engineering, Belgrade
year      : 4th year, Software Engineering
open to   : internships · systems / infrastructure engineering roles
contact   : ilija.vlahovic24@gmail.com
linkedin  : https://www.linkedin.com/in/ilija-vlahovic-ba9946201
```

---

### About

4th-year Software Engineering student at the **Faculty of Electrical Engineering, University of Belgrade**. I build the layers that software runs on, from scratch: an OS kernel, a Raft-replicated filesystem, a key-value store, a query engine, compilers. I take the same approach to machine learning, where I write the frameworks myself, such as a physics-informed ML framework and a vector search index, instead of treating them as black boxes.


Currently:
- Developing **AIPlasma**, a physics-informed ML framework for plasma/fusion problems
- Making a full functional drone from scratch with STM32 microcontroller
- Making a shader language compiler in C++ that translates my custom made language into GLSL

---

### Projects
|Statuses| meaning |
|---|---|
|Completed | All core functionalities are completed, the project is documented and measured, and no further development is expected.|
| Maintained | All core functionalities are completed, the project is documented and measured, but development continues to improve results or add/improve functionalities.|
|Core Completed | All core functionalities are completed, but documentation and/or measurement is not done.|
|In Progress | Not all core functionalities are completed, but they are in development.|
|Planned| Core idea for the project is defined or structured, but development has not started.|
| Abandoned | Not all functionalities are completed, and there will be no further development in the foreseeable future.|

#### Distributed Systems
| Project | Description | Stack | Status | Also in |
|---|---|---|---|---|
| [Fault-Tolerant Distributed File System](https://github.com/ilijavlahovic24-bit/ffs) | Distributed FS with FUSE mount, WAL for crash recovery, Raft consensus, RPC, VFS, Chaos Testing | Rust, FUSE, Tokio | Completed | Systems Software |
| [Distributed Key-Value Store (DKVS)](https://github.com/ilijavlahovic24-bit/dkvs) | Sharded KV store with consistent hashing (FNV-64) and inter-shard replication | Go, BoltDB | Completed | - |
| [Distributed Tuple-Space System (Linda)](https://github.com/ilijavlahovic24-bit/javalinda) | Distributed Linda-style tuple space with worker heartbeat/failover | Java | Completed | - |
| [GraphStream](https://github.com/ilijavlahovic24-bit/graphstream) | Temporal graph query engine with a custom query language (TQL) - EBNF grammar, parser, execution engine | Rust, Apache Kafka, Kubernetes | Maintained | Compilers & Query Languages|
| [GFCS-R](https://github.com/ilijavlahovic24-bit/gfcr) | Discrete-event simulator for GPU interconnect fabric with congestion-aware routing | Rust | In progress | - |

#### Systems Software

| Project | Description | Stack | Status | Also in |
|---|---|---|---|---|
| [Fault-Tolerant Distributed File System](https://github.com/ilijavlahovic24-bit/ffs) | Distributed FS with FUSE mount, WAL for crash recovery, Raft consensus, RPC, VFS, Chaos Testing | Rust, FUSE, Tokio | Completed | Distributed Systems |
| [RISC-V OS Kernel](https://github.com/ilijavlahovic24-bit/OS1) | OS kernel from scratch: preemptive multitasking, memory allocator, trap-based syscalls | C++, RISC-V ASM | Completed | - |

#### Compilers & Query Languages

| Project | Description | Stack | Status | Also in |
|---|---|---|---|---|
| [MicroJava Compiler](https://github.com/ilijavlahovic24-bit/microjavacompiler) | Full compiler for MicroJava (Level C) - lexer, parser, semantic analysis, codegen for a custom VM | Java, JFlex, CUP | Completed | - |
| [GraphStream](https://github.com/ilijavlahovic24-bit/graphstream) | Temporal graph query engine with a custom query language (TQL) - EBNF grammar, parser, execution engine | Rust, Apache Kafka, Kubernetes | Maintained | Distributed Systems |
| [SLC](https://github.com/ilijavlahovic24-bit/slc) | Custom shader language to GLSL compiler (diploma thesis) | C++ | In Progress | - |

#### Machine Learning & Physics Simulations

| Project | Description | Stack | Status |
|---|---|---|---|
| [AIPlasma](https://github.com/ilijavlahovic24-bit/aiplasma) | Physics-informed ML framework (PINNs, Bayesian NNs) for plasma/fusion problems | Python, PyTorch | Maintained |
| [Particle Physics Engine](https://github.com/ilijavlahovic24-bit/Cuda-Particle-Solver) | 2D particle simulation, CUDA-accelerated from ~500 to 12,000+ particles at 60+ FPS | C++, CUDA, OpenGL, SFML | Completed |
| [Mini-RAG](https://github.com/ilijavlahovic24-bit/rag-search) | Search engine with a custom HNSW vector index and hybrid retrieval | Python, FastAPI | Completed |
| [DistillBench](https://github.com/ilijavlahovic24-bit/distilbench) | Model Compression Trilogy - Distillation, quantization, and pruning benchmark suite | Python | Completed |

#### Applications & Platforms

| Project | Description | Stack | Status |
|---|---|---|---|
| [Pennant](https://github.com/ilijavlahovic24-bit/pennant) | B2B feature flag management system - RBAC, multi-tenancy, deterministic bucketing | Go, React, PostgreSQL, Redis | Completed |
| [AzureBank](https://github.com/ilijavlahovic24-bit/azurebank) | Retail banking API with CI/CD pipeline and cloud deployment | Go, PostgreSQL, Azure, Terraform | Completed |
| [Hallify](https://github.com/ilijavlahovic24-bit) | Event hall rental platform (university group project) | Python, Django | Completed |
| [Retail-ELT](https://github.com/ilijavlahovic24-bit/elt) | Complete ELT pipeline that ingests raw sales data, loads it into a warehouse, transforms it into a star schema with dbt, orchestrates the entire flow with Airflow, and enforces data quality at every stage. The output is a queryable analytics table and a simple dashboard. | Python, Docker, Airflow, dbt | Completed |

#### Embedded Systems & Robotics

| Project | Description | Stack | Status |
|---|---|---|---|
| [Drone](https://github.com/ilijavlahovic24-bit/drone) | Bare-metal quadcopter flight controller from scratch - IMU fusion, PID control, PWM/ESC driving, 6-DOF dynamics simulation  | C, STM32F103 (Cortex-M3), Proteus | In Progress |

---

### Tech Stack

```
Languages     : C/C++ · Rust · Go · Python · Java · RISC-V Assembly
Technologies  : CUDA · Docker · Git · Linux · MySQL · PostgreSQL · Azure
Areas         : Systems Programming · Distributed Systems · GPU Computing · Machine Learning
```

---

### Certifications & Achievements

- Cisco Cybersecurity Certificate
- Google Production ML Systems Certificate
- Petnica Science Center - competitive science program for Serbia's most talented students
- ABB Robotics Hackathon · JetBrains Hackathon (logistics team) · Google Developer Group Cloud Workshop
- Member, EESTEC - European Association of Electrical Engineering Students
- Member, Google Developer Group on Campus

---

### GitHub Stats



<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ilijavlahovic24-bit&theme=dark&hide_border=true" height="165"/>
</p>

---

<p align="center">
  <em>Reach out: ilija.vlahovic24@gmail.com</em>
</p>
