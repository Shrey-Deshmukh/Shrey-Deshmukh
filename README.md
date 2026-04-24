<div align="center">

# Shrey Deshmukh

**Graduate Computer Science Student @ UC Irvine** &nbsp;|&nbsp; **Ex-Hewlett Packard Enterprise** &nbsp;|&nbsp; **Irvine, CA**

*Currently seeking Summer 2026 internships in Software Engineering, AI Engineering, Cloud Engineering and related fields*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrey-deshmukh)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=netlify&logoColor=white)](https://shrey-deshmukh.netlify.app)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sdeshmu2@uci.edu)

</div>

---

## About Me

I'm a graduate CS student at UCI with **2+ years of professional experience** building production-grade backend systems and distributed infrastructure at Hewlett Packard Enterprise. I've shipped features used by Fortune 500 clients, led root cause analysis across production escalations, and built everything from Kubernetes storage controllers to AI-powered automation pipelines.

I care about systems that are correct, fast, and reliable - and I enjoy working on problems where those properties actually matter.

---

## Technical Skills

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Infrastructure & DevOps**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google_Cloud_Platform-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-277A9F?style=for-the-badge&logo=helm&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**AI & ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF8F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white)

**Software Methodologies**

![Agile](https://img.shields.io/badge/Agile-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Scrum](https://img.shields.io/badge/Scrum-009FDA?style=for-the-badge&logoColor=white)
![SDLC](https://img.shields.io/badge/SDLC-6A0DAD?style=for-the-badge&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white)

---

## Projects

Here are a few selected projects.

### [Recovery Adapter](https://github.com/shrey-deshmukh/recovery-adapter)
`Go · REST APIs · CLI · Linux`

A Golang-based CLI tool built at HPE to automate disaster recovery operations on storage arrays. The tool abstracts complex HPE array CLI commands into a simple menu-driven interface supporting the full failover lifecycle: connect to primary and secondary sites via REST, check array and Remote Copy Group (RCG) status, execute planned failover and failback, reprotect arrays, and fetch task logs for debugging. Implements pre-failover safety checks, robust error handling for 14+ edge cases (invalid RCG states, expired sessions, incorrect credentials), and was designed to reduce Recovery Time Objective (RTO) for support teams, sales engineers, and R&D. **Ranked Top 5** at HPE Storage Creative Days Hackathon 2023.

---

### [SurveyOps+](https://github.com/Shrey-Deshmukh/survey_ops_plus_poc)
`Python · LLMs · Multimodal AI · API Integration · LangChain · LangGraph · Prompt Engineering`

An AI-powered inspection workflow automation system that replaces manual marine container reporting with an end-to-end intelligent pipeline. Uses multimodal LLMs to process raw visual and textual inspection inputs, applies structured output schemas and prompt engineering to generate standardized reports, and incorporates human-in-the-loop validation gates to ensure accuracy before finalization. Designed with async processing for throughput and modular pipeline stages for extensibility - directly applicable to any domain requiring automated document generation from unstructured inputs.

---

### [Real Time Face Mask Detection](https://github.com/Shrey-Deshmukh/real-time-face-mask-detection.git)
`Python · TensorFlow · Keras · OpenCV · MobileNetV2`

An end-to-end computer vision pipeline for real-time face mask detection. Fine-tuned a MobileNetV2 transfer learning model with data augmentation on 2,200+ labeled images, achieving **95.77% classification accuracy** across two datasets. Built a complete inference pipeline from data preprocessing and CNN training through to real-time video detection using OpenCV - capable of processing live camera feeds and classifying mask/no-mask per detected face at video frame rate.

---

### [Autonomous Intersection Navigation RL](https://github.com/Shrey-Deshmukh/autonomous-intersection-navigation-drl.git)
`Python · PyTorch · Deep Q-Network · Curriculum Learning`

A reinforcement learning agent trained to navigate unsignalized four-way intersections without traffic signals. Uses Deep Q-Network (DQN) with curriculum learning - progressively increasing traffic density from low to high congestion across 35,000 training episodes - achieving **85% success rate** in high-congestion 16-car scenarios. Engineered a hybrid safety architecture combining DQN-based long-term planning with a rule-based collision shield that overrides unsafe actions, and applied transfer learning to improve generalization across unseen traffic densities.

---

### [Transaction Processing Engine](https://github.com/shrey-deshmukh/transaction-processing-engine)
`C++ · RocksDB · Multithreading · Concurrency Control`

A multithreaded transaction processing engine built from scratch in C++ on top of RocksDB. Implements two full concurrency control protocols: **Optimistic Concurrency Control (OCC)** with a read-validate-write phase model and exponential backoff on abort, and **Conservative Two-Phase Locking (2PL)** with all-or-nothing lock acquisition, deadlock avoidance via consistent key ordering, and livelock prevention through timestamp-based priority escalation. Features a configurable hotset-based contention model and full benchmarking pipeline measuring throughput (txns/sec) and p50/p95/p99 latency across thread counts and contention levels. Benchmark results included in the repository.

---

### [Live Web Code Sandbox](https://github.com/shrey-deshmukh/live-web-code-sandbox)
`HTML · CSS · JavaScript · jQuery`

A browser-based live coding environment that dynamically injects and executes HTML, CSS, and JavaScript in real time without page reloads. Features resizable and toggleable editor panels built with jQuery UI, isolated output rendering to prevent style and script conflicts between the editor and preview environments, and immediate visual feedback on every keystroke — similar in concept to tools like CodePen.

---

### [Android Fitness Metrics Calculator](https://github.com/Shrey-Deshmukh/android-fitness-metrics-calculator)
`Java · Android SDK`

A native Android application for computing real-time fitness pacing metrics from user inputs including distance, time, and target goals. Implements event-driven input callbacks with full validation, constraint-based responsive layouts that adapt across screen sizes, and a modular Activity-based architecture with cleanly separated presentation, computation, and resource layers.


---

## Experience

### Hewlett Packard Enterprise - Software / Cloud Development Engineer
`August 2023 – August 2025` &nbsp;|&nbsp; Bengaluru, India

**Kubernetes (K8s) CSI Storage Integration**
- Drove cross-team collaboration in HPE’s Innovation Connect program, supporting 4 engineering teams in delivering winning TechCons submissions, hackathon prototypes, and patent initiatives.
- Engineered scalable, high availability backend microservices in Go within HPE's Container Storage Provider to orchestrate dynamic resource provisioning and multi-cluster replication across distributed Kubernetes deployments
- Designed and implemented Active Peer Persistence using Kubernetes CRDs to track array changes, reducing downtime risk
- Engineered and released an end-to-end Disable Host Deletion safeguard preventing destructive operations on arrays during active replication, reducing accidental deletion-related escalations to near zero post-release
- Troubleshot and led root cause analysis for 12 production escalations across Fortune 500 enterprise CSI deployments; increased unit test coverage from 0% to ~80% in high-risk modules, significantly improving CSI 3.0 release stability

**VMware vSphere Backend Plugin Development**
- Developed core backend components for Storage Integration Pack (SIPVC) 13.x, integrating HPE storage systems with VMware REST APIs, enabling lifecycle management, snapshots, and persistence workflows within vCenter
- Implemented Quick Restore Snapshot for VMFS datastores using array-level fast-copy primitives - benchmarked recovery time reduction from hours to near instant - directly contributing to a $1.1M Disaster Event Recovery engagement
- Collapsed a 5-step manual provisioning workflow into a single automated operation via dynamic datastore expansion, reducing administrative steps by 80%

---

### Hewlett Packard Enterprise - Software / Cloud Development Engineering Intern
`January 2023 – July 2023` &nbsp;|&nbsp; Bengaluru, India

**Disaster Recovery Automation**
- Developed a Python and Go-based SRM integration plugin to automate failover, failback, and migration workflows across distributed systems, eliminating manual sequencing and improving recovery consistency
- Implemented multithreaded execution for DR validation and state reconciliation workflows within the SRM plugin, reducing sequential bottlenecks and improving failover readiness by 60% as measured by call logs
- Built and documented unit test code for Prepare Reverse Replication (PRR) workflows with comprehensive error handling, covering edge cases including invalid RCG states, expired session keys, and inconsistent array states
- Contributed to code analysis and debugging of SRA integration functions for VMware Site Recovery Manager (SRM), working across the full failover-to-reverse-replication lifecycle

---

### Tata Starbucks - Information Technology Intern
`June 2022 – August 2022` &nbsp;|&nbsp; Mumbai, India

**Mobile App Development & Quality Assurance**
- Executed Quality Assurance and User Acceptance Testing across multiple builds of the Starbucks India mobile app, logging 150+ bugs with structured reproduction steps across devices, OS versions, and network configurations
- Conducted API testing using Postman, validating REST endpoints (GET, POST, PUT, DELETE) for the Starbucks NewApp backend covering store, menu, cart, and order management services
- Worked with OrderServ (Cognizant's kitchen order management system) to categorize and configure 500+ menu items across categories, subcategories, and modifier groups
- Built product filter and search tags for item subcategories, and uploaded classified SVG product images across multiple resolutions to the OrderServ dashboard

---

## Education

### University of California, Irvine
**Master of Computer Science** &nbsp;|&nbsp; *Expected December 2026*

| | |
|---|---|
| Artificial Intelligence | Machine Learning |
| Advanced Data Structure | Parallel Computing |
| Distributed Systems | Algorithms |
| Advanced Programming | Transaction Processing |

---

### Manipal Institute of Technology
**B.Tech, Computer and Communication Engineering** &nbsp;|&nbsp; *July 2019 – July 2023*

| | |
|---|---|
| Data Structures & Algorithms | Object-Oriented Programming |
| Database Systems | Operating Systems |
| Cloud Computing | Big Data Management |
| Software Design | Computer Networks |
| Mobile Application Development | Data Mining and Predictive Analysis |

---

## GitHub Stats

<div align="center">

<!-- ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shrey-deshmukh&show_icons=true&theme=dark&hide_border=true&count_private=true&v=1) -->
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shrey-deshmukh&layout=compact&theme=dark&hide_border=true&v=1)

</div>
