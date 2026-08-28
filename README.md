<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25,30&height=200&section=header&text=B.%20Santhana%20Krishna&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineering%20%7C%20AI%20Security%20%7C%20Cloud%20%26%20Distributed%20Systems&descAlignY=56&descSize=18" width="100%" />



<br/>





<br/>

📍 Chennai, India

<br/><br/>


 

 


<br/>



</div>

👋 About Me

I'm a final-year B.Tech Electronics & Communication Engineering student specialising in Cyber-Physical Systems at SASTRA Deemed University.

I'm interested in building and securing AI systems, with hands-on work across LLM applications, RAG, AI agents, AI security, cloud infrastructure, and distributed systems.

I enjoy understanding systems from first principles and turning that understanding into working, testable implementations — from AI guardrails and prompt-injection defense to consistent hashing and distributed caching.

My current direction is toward building AI systems that are reliable, secure, observable, and resilient, with security and evaluation considered throughout the engineering process.

🧠 What I'm Working With

<div align="center">

AI Engineering






LLM Applications · RAG · AI Agents · LangChain · LangGraph · Prompt Engineering · LLM Evaluation

AI Security



Prompt Injection · Jailbreak Detection · AI Guardrails · RAG Security · Agent Security · AI Red Teaming · OWASP Top 10 for LLM Applications

Cloud & AI Infrastructure

AWS · IAM · EC2 · S3 · VPC · CloudTrail · CloudWatch · GuardDuty · Amazon Bedrock · AWS CDK

NVIDIA NeMo Guardrails · AWS Bedrock Guardrails · Guardrails AI · Portkey AI Gateway · LangSmith · Pydantic Logfire

Security & Systems



Network Security · Anomaly Detection · Sysmon · Nmap · Wireshark · Tcpdump · Network Traffic Classification · Distributed Systems · Consistent Hashing · SQL

</div>

🚀 Featured Projects

🛡️ GuardrailOps — AWS Bedrock Guardrails-as-Code

Treating AI safety policies as version-controlled infrastructure.

Stack: Python · AWS CDK · Amazon Bedrock Guardrails

Built a Guardrails-as-Code pipeline for LLM applications using AWS CDK (Python).

Provisioned AI safety controls as reproducible infrastructure instead of relying on manual console configuration.

Implemented reusable policies for denied topics, content filtering, and grounding / hallucination detection.

Structured the infrastructure into modular components with standalone policy evaluation.

Explored the relationship between AI governance, runtime protection, policy enforcement, and application security.

🔐 PromptWarden — LLM Prompt Injection & Jailbreak Detection Middleware

A security middleware layer for detecting adversarial inputs before they reach downstream LLM components.

Stack: Python · PyRIT · OWASP Top 10 for LLM Applications

Developing a real-time detection layer positioned between users and an LLM application.

Focused on detecting prompt injection and jailbreak attempts designed to override instructions or bypass application policies.

Using PyRIT to construct an adversarial test corpus covering:

Direct prompt injection

Encoding and obfuscation

Multi-turn attacks

Persuasion-based jailbreak techniques

Designing a detection-and-decision layer that can allow, flag, or block suspicious requests.

Using the OWASP Top 10 for LLM Applications as a security reference for threat modelling.

⚙️ Distributed Cache Router — Consistent Hashing & Distributed Caching

A from-scratch Python implementation exploring the routing algorithms behind distributed caching systems.

Stack: Python · SHA-256 · Consistent Hashing · Binary Search · Unit Testing · Benchmarking

Implemented SHA-256 based consistent hashing and a consistent hash ring from scratch.

Added virtual nodes to improve key distribution and reduce redistribution when cluster membership changes.

Implemented binary-search based routing across the hash ring.

Added configurable replication with clockwise replica selection.

Built unit tests and performance benchmarks to study:

Key distribution

Virtual-node behaviour

Replica distribution

Routing characteristics

Scalability trade-offs

Documented the evolution from modulo hashing → consistent hashing → virtual nodes → replication.

🏭 Securing Water Infrastructure — ICS / OT Security

A cyber-physical security monitoring system for a lab-scale water treatment control environment.

Stack: Python · Raspberry Pi 5 · ESP32 · ESP-NOW · Flask · ARX Modelling

Built an ARX-based digital-twin anomaly detection engine for live sensor streams.

Implemented an automated detect → alert → persist → safe-state response workflow.

Used a persistence filter to confirm anomalous behaviour before response execution.

Built a Flask-based monitoring interface for anomaly visualisation and alert status.

Explored sensor spoofing detection and physical safe-state activation in an ICS/OT environment.

🤖 ML Network Threat Detection Pipeline

A machine-learning pipeline for network attack classification using the UNSW-NB15 dataset.

Stack: Python · scikit-learn · Pandas · NumPy · SMTP · UNSW-NB15

Built an end-to-end network threat classification pipeline.

Performed EDA, encoding, normalisation, and feature selection.

Reduced 47 raw features to 15 high-signal indicators through correlation analysis.

Trained Random Forest models for binary and multi-class attack classification.

Evaluated attack categories including DoS, Exploits, Reconnaissance, and Backdoor.

Added SMTP-based alert escalation to simulate security monitoring workflows.

🔍 Areas of Interest

<div align="center">

Area

Focus

🤖 AI Engineering

LLM applications, RAG, AI agents, evaluation

🔐 AI Security

Prompt injection, jailbreaks, guardrails, red teaming

☁️ Cloud Security

AWS security services, IAM, monitoring, Bedrock

🧩 Distributed Systems

Consistent hashing, caching, replication, fault tolerance

🛡️ Security Engineering

Network security, anomaly detection, detection pipelines

🏭 ICS / OT Security

Cyber-physical systems, SCADA, anomaly detection

</div>

🎓 Education

Institution

Degree

Period

Score

SASTRA Deemed University, Thanjavur

B.Tech — ECE, Cyber-Physical Systems Specialisation

2022 – 2026

CGPA: 8.00

Kendriya Vidyalaya Ashok Nagar, Chennai

Class XII — CBSE

2022

88.8%

Kendriya Vidyalaya Ashok Nagar, Chennai

Class X — CBSE

2020

96.6%

📜 Certifications & Programs

🔷 Google Cybersecurity Professional Certificate

Focus: Incident Response · SIEM Fundamentals · Network Security · Threat Detection · Linux Security

Credential ID: AOOV02KBIFCI

🔷 Deloitte Australia — Cyber Job Simulation

Focus: Threat Triage · Alert Analysis · Incident Classification · Security Recommendations

Credential ID: Daqp5gbLuK4PCHwGt

🔷 Mastercard — Cybersecurity Job Simulation

Focus: Phishing Email Analysis · Attack Pattern Recognition · Security Awareness

Credential ID: g2kRx3qEQkufZGsT5

🧪 Currently Learning & Building

current_focus:
  learning:
    - LLM security and prompt injection defense
    - RAG architecture and RAG security
    - AI agent architectures and agent security
    - LLM evaluation and observability
    - AWS security and cloud infrastructure
    - Distributed systems and system design

  building:
    - PromptWarden:
        - Prompt injection detection
        - Jailbreak detection
        - Adversarial testing with PyRIT
    - GuardrailOps:
        - AWS Bedrock Guardrails
        - AWS CDK
        - Guardrails-as-Code
    - RAG systems:
        - Retrieval pipelines
        - Embeddings
        - Vector search
        - Evaluation
    - Distributed systems:
        - Consistent hashing
        - Distributed caching
        - Replication

  exploring:
    - AI red teaming
    - OWASP Top 10 for LLM Applications
    - Secure AI agents
    - Cloud-native security
    - Detection engineering

💻 Coding & Problem Solving

<div align="center">


 

 

 


</div>

📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Santa-Cruz1654&show_icons=true&theme=tokyonight&hide_border=true&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD&bg_color=0D0B1E&count_private=true&include_all_commits=true" height="180" />
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Santa-Cruz1654&theme=tokyonight&hide_border=true&ring=A78BFA&fire=7C3AED&currStreakLabel=C4B5FD&background=0D0B1E&stroke=4F46E5&sideLabels=C4B5FD&currStreakNum=A78BFA&sideNums=A78BFA&dates=6D28D9" height="180" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Santa-Cruz1654&layout=donut&theme=tokyonight&hide_border=true&title_color=A78BFA&text_color=C4B5FD&bg_color=0D0B1E&langs_count=8" height="220" />

</div>

🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Santa-Cruz1654/Santa-Cruz1654/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Santa-Cruz1654/Santa-Cruz1654/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Santa-Cruz1654/Santa-Cruz1654/output/github-contribution-grid-snake.svg" />
</picture>

</div>

🤝 Let's Connect

<div align="center">

I'm interested in connecting with people working on AI engineering, AI security, cloud security, distributed systems, and cybersecurity.

<br/>


 

 


<br/><br/>

"Build it from first principles. Secure it by design. Test what you trust."

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25,30&height=120&section=footer&animation=fadeIn" width="100%" />

</div>
