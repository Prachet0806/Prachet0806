# Hi, I'm Prachet 👋

### Backend Engineer · Systems & Infrastructure

I build software that reasons about **state, constraints, resources, and failure** — from optimization-driven applications and transactional backend systems to network analysis and distributed workload orchestration.

I'm interested in the engineering behind reliable software: how systems coordinate work, preserve correctness, use resources efficiently, and behave under failure.

[Portfolio](https://prachet-portfolio-nine.vercel.app/projects) · [LinkedIn](https://www.linkedin.com/in/prachet-sensarma-3a08a92b2/) · [GitHub](https://github.com/Prachet0806)

---

## Featured Projects

### 01 · EcoRace — Constraint-Based Calendar Optimization

**Backend Engineering · Optimization · Full-Stack Development**

A deployed decision-support application that constructs and optimizes an F1 calendar across real-world venues, balancing travel distance against scheduling, circuit uniqueness, and weather-feasibility constraints.

- Built a standalone optimization core with a FastAPI application layer and Next.js frontend.
- Uses a CP-SAT and heuristic solver portfolio to generate candidate schedules.
- Validates solutions independently and distinguishes feasible timeout results from proven optimal solutions.
- Includes route visualization, scheduling diagnostics, and baseline comparisons.

**Stack:** `Python` · `FastAPI` · `OR-Tools` · `Next.js` · `TypeScript` · `MapLibre`

[Live Demo](https://eco-race-two.vercel.app/) · [Source Code](https://github.com/Prachet0806/EcoRace)

### 02 · WizDesk — Transactional Team Workflow Platform

**Backend Engineering · API Design · Data Integrity**

A team task-management platform built around controlled membership, task assignments, progress tracking, and safe concurrent updates.

- Enforces role and team-membership rules across API operations.
- Applies task edits atomically and uses revision checks to detect stale updates.
- Models assignment transfers, archival behavior, and task progress transitions.
- Includes backend, browser-workflow, and PostgreSQL concurrency testing.

**Stack:** `Python` · `Django` · `Django REST Framework` · `PostgreSQL` · `JavaScript` · `Playwright`

[Source Code](https://github.com/Prachet0806/WizDesk)

### 03 · Packet Sniffer & Protocol Analyzer

**Systems Programming · Networking · Concurrency**

A multithreaded packet-capture and protocol-analysis tool written in C, designed to explore network traffic from link-layer frames through selected application protocols.

- Separates packet capture and analysis using a threaded architecture and synchronized buffering.
- Implements protocol parsing across Ethernet, IPv4/IPv6, TCP/UDP, ICMP, DNS, HTTP, TLS metadata, and DHCP.
- Supports persistent statistics, JSON export, and containerized workflows.

**Stack:** `C` · `libpcap` · `POSIX Threads` · `CMake` · `PostgreSQL` · `Docker`

[Source Code](https://github.com/Prachet0806/Packet_Sniffer)

### 04 · AWS Waste Hunter — Read-Only Cloud FinOps

**Cloud Infrastructure · Serverless Architecture · Cost Analysis**

A serverless pipeline that discovers potentially wasteful AWS resources and generates evidence-backed reports without automatically modifying or deleting infrastructure.

- Uses AWS Step Functions to coordinate isolated scanner Lambdas.
- Organizes run state and scan artifacts using DynamoDB and S3.
- Produces auditable findings and notifications through SNS.
- Treats uncertain pricing and incomplete cost data explicitly rather than presenting estimates as realized savings.

**Stack:** `Python` · `AWS Lambda` · `Step Functions` · `EventBridge` · `DynamoDB` · `S3` · `SNS`

[Source Code](https://github.com/Prachet0806/aws_waste_hunter)

### 05 · Distributed Spot Workload Orchestrator

**Distributed Systems · Workload Scheduling · Fault Recovery**

A workload-orchestration project exploring cost-aware execution on AWS EC2 Spot capacity, with checkpointing and recovery as central design concerns.

- Explores scheduling workloads against variable-cost compute resources.
- Integrates AWS infrastructure components for workload state and artifact management.
- Investigates checkpoint-and-restore workflows using CRIU.
- Focuses on the trade-offs between execution cost, interruption risk, recovery, and coordination.

**Stack:** `Python` · `AWS EC2 Spot` · `DynamoDB` · `S3` · `Terraform` · `CRIU`

[Source Code](https://github.com/Prachet0806/Distributed_Spot_Orchestrator)

### 06 · LegacyLock — Digital Legacy Vault

**Backend Engineering · Security Architecture · Cryptography**

A security-focused proof of concept for storing encrypted messages and releasing them to designated beneficiaries under configurable inactivity and recovery rules.

- Implements browser-side message encryption and key-wrapping workflows.
- Explores Shamir Secret Sharing for recovery, beneficiary access, and controlled release.
- Models heartbeat, grace-period, and triggered states with guarded transitions.
- Includes authentication, recovery flows, audit-related functionality, and backend tests.

**Stack:** `TypeScript` · `Next.js` · `FastAPI` · `PostgreSQL` · `Web Crypto API` · `Pytest`

[Source Code](https://github.com/Prachet0806/legacylock)

---

## Technical Toolkit

**Languages**

`Python` · `C++` · `C` · `TypeScript` · `JavaScript`

**Backend & Data**

`FastAPI` · `Django` · `REST APIs` · `PostgreSQL` · `SQLite` · `SQLAlchemy`

**Cloud & Infrastructure**

`AWS` · `Lambda` · `EC2` · `S3` · `DynamoDB` · `CloudWatch` · `EventBridge` · `Step Functions` · `Terraform` · `Docker`

**Systems & Engineering**

`Linux` · `Networking` · `Concurrency` · `CMake` · `Cryptography` · `OR-Tools` · `Pytest` · `Playwright` · `CI/CD`

---

## Engineering Interests

- **Backend systems:** API contracts, transactions, concurrency, and data integrity
- **Distributed systems:** scheduling, coordination, fault tolerance, and recovery
- **Cloud infrastructure:** orchestration, resource efficiency, and cost-aware execution
- **Systems programming:** networking, computer architecture, and performance
- **Reliability and observability:** telemetry pipelines, diagnostics, and operational insights
- **Security engineering:** identity, authorization, cryptographic boundaries, and secure state transitions

## Currently Exploring

- Kubernetes and cloud-native infrastructure
- Distributed tracing and observability
- Rust and Go open-source ecosystems
- Distributed coordination, scheduling, and failure recovery
- Systems and infrastructure for AI workloads

---

*I value systems that are not only functional, but explainable, testable, and honest about their limitations.*
