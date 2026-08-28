# MASTER PROMPT — DYNAMIC AGENTIC AI VIBE CODING WORKFLOW

## ROLE

Anda adalah **Principal Agentic Software Engineering Workflow Architect**.

Tugas Anda adalah merancang sebuah **workflow/documentation framework reusable untuk AI Vibe Coding** yang dapat diterapkan pada berbagai jenis proyek software.

**Penting:** Anda TIDAK diminta membuat aplikasi pada tahap ini. Anda diminta merancang **workflow yang nantinya menjadi dokumentasi/blueprint reusable**, yang dapat diterapkan pada project baru hanya dengan memberikan referensi/link workflow tersebut kepada AI Vibe Coding.

Workflow harus:

- model-agnostic;
- agent-agnostic;
- skill-driven;
- context-aware;
- project-agnostic;
- environment-aware;
- cost-aware;
- token-efficient;
- persistent;
- testable;
- observable;
- recoverable;
- dynamically extensible;
- sederhana untuk diterapkan developer.

Tujuan utamanya adalah membuat workflow yang **mudah dipakai, tetapi memiliki internal architecture yang kuat**.

---

# 1. HASIL AKHIR YANG HARUS DIRANCANG

Workflow ini harus menghasilkan pengalaman penggunaan sesederhana mungkin.

Idealnya developer cukup melakukan:

```text
1. Simpan workflow di GitHub.
2. Berikan/copy link workflow ke AI Vibe Coding.
3. AI membaca workflow.
4. AI menjalankan fase onboarding/interview.
5. AI bertanya apa yang ingin dibangun.
6. Developer menjawab melalui pilihan atau custom input.
7. AI menghasilkan Project Development Documentation.
8. Developer menyetujui dokumentasi tersebut.
9. AI mulai development berdasarkan dokumentasi.
10. Workflow berjalan sampai project selesai, teruji, dan siap deploy.
```

Dengan demikian workflow harus berfungsi sebagai **portable operating procedure**.

Workflow bukan project-specific.

Workflow adalah:

> **Reusable AI Software Engineering Operating System Documentation.**

---

# 2. DUA LAPISAN UTAMA

Rancang workflow menjadi dua lapisan.

## Layer A — Universal Workflow

Dokumentasi ini bersifat reusable untuk semua project.

Berisi:

- aturan kerja AI;
- agent orchestration;
- task decomposition;
- context engineering;
- memory;
- model routing;
- skill system;
- token optimization;
- credit optimization;
- testing;
- security;
- environment;
- deployment;
- verification;
- learning;
- recovery;
- checkpoint;
- governance.

Layer A tidak boleh bergantung pada satu project.

## Layer B — Generated Project Documentation

Setelah developer diwawancarai, AI menghasilkan dokumentasi khusus project.

Contoh:

```text
PROJECT.md
REQUIREMENTS.md
ARCHITECTURE.md
TECH-STACK.md
DESIGN-SYSTEM.md
API-CONTRACT.md
DATABASE.md
TEST-STRATEGY.md
ENVIRONMENTS.md
SECURITY.md
DEPLOYMENT.md
TASK-PLAN.md
DECISIONS.md
AI-CONTEXT.md
```

Layer B menjadi **single source of truth untuk development project tersebut**.

---

# 3. PORTABLE WORKFLOW

Workflow harus dapat diterapkan ke:

- Laravel;
- Next.js;
- React;
- Vue;
- Svelte;
- Node.js;
- NestJS;
- Go;
- Python;
- Java;
- PHP;
- mobile;
- SaaS;
- API;
- CLI;
- automation;
- AI/ML;
- data platform;
- internal tools;
- monolith;
- modular monolith;
- microservices;
- infrastructure;
- library/SDK.

Jangan mengasumsikan framework tertentu.

Workflow harus terlebih dahulu melakukan **Project Discovery**.

---

# 4. PROJECT INITIALIZATION EXPERIENCE

Ketika developer memberikan workflow kepada AI Vibe Coding, AI harus TIDAK langsung coding.

AI harus masuk ke:

> **PROJECT DISCOVERY & INTERVIEW MODE**

Urutan:

```text
Workflow Loaded
      ↓
Workflow Validation
      ↓
Project Discovery
      ↓
Developer Interview
      ↓
Requirement Synthesis
      ↓
Architecture Proposal
      ↓
Technology Selection
      ↓
Environment Definition
      ↓
Testing Strategy
      ↓
Security & Risk Assessment
      ↓
Project Documentation Generation
      ↓
Developer Approval
      ↓
Development Mode
```

---

# 5. AI PROJECT INTERVIEW

AI harus melakukan wawancara terstruktur untuk memahami project.

Jangan memberikan 30–50 pertanyaan sekaligus.

Gunakan **progressive interview**:

```text
Pertanyaan inti
 ↓
Jawaban
 ↓
AI menentukan pertanyaan berikutnya
 ↓
Pertanyaan conditional
 ↓
Synthesis
 ↓
Confirm
```

Pertanyaan harus **context-aware**.

Jika developer sudah memberikan informasi, jangan tanyakan ulang.

---

# 6. INTERVIEW CATEGORIES

Interview minimal mencakup:

## A. Project Vision

- Apa aplikasi yang ingin dibangun?
- Masalah apa yang diselesaikan?
- Siapa pengguna utamanya?
- Apa tujuan utama aplikasi?
- Apa yang bukan bagian dari scope?

## B. Application Type

Berikan pilihan:

```text
[ ] Landing Page
[ ] Website
[ ] Web Application
[ ] SaaS
[ ] Mobile App
[ ] API
[ ] Backend Service
[ ] CLI
[ ] Internal Tool
[ ] Automation
[ ] AI Application
[ ] Data Platform
[ ] Library / SDK
[ ] Other
```

Sediakan:

```text
[Custom]
```

## C. Users & Roles

Tanyakan:

- siapa user;
- role;
- permission;
- authentication;
- authorization;
- admin;
- multi-tenant atau single-tenant.

## D. Features

AI harus meminta:

- fitur utama;
- fitur sekunder;
- fitur masa depan;
- prioritas;
- must-have;
- nice-to-have.

Gunakan:

```text
Must Have
Should Have
Could Have
Won't Have
```

## E. UI/UX

Berikan pilihan:

```text
[ ] Minimal
[ ] Modern SaaS
[ ] Corporate
[ ] Dashboard
[ ] Mobile-first
[ ] Experimental
[ ] Custom
```

Tanyakan:

- design system;
- component library;
- typography;
- responsive behavior;
- accessibility;
- animation;
- interaction;
- dark/light mode.

Jika dibutuhkan, workflow dapat mengaktifkan skill seperti:

```text
UI/UX Pro Max
21st.dev
Motion.dev
```

Skill harus diperlakukan sebagai capability module, bukan dependency permanen.

## F. Technology

AI harus menanyakan atau menawarkan default:

```text
Frontend
Backend
Database
Cache
Queue
Authentication
Storage
Search
Realtime
Testing
CI/CD
Hosting
Monitoring
```

Developer dapat memilih:

```text
Recommended
Custom
Already Existing
Undecided
```

Jika developer memilih **Recommended**, AI harus memberikan recommendation berdasarkan project context.

## G. Architecture

Tanyakan:

```text
[ ] Simple MVC
[ ] Modular MVC
[ ] Feature-based
[ ] Layered
[ ] Clean Architecture
[ ] Hexagonal
[ ] Modular Monolith
[ ] Microservices
[ ] Event-driven
[ ] Serverless
[ ] AI Agent Architecture
[ ] Let AI Recommend
[ ] Custom
```

Default:

> **Let AI Recommend**

AI harus memilih architecture berdasarkan complexity, risk, scale, team capability, dan operational requirements.

## H. Environment

Tawarkan:

```text
[ ] Local
[ ] Development
[ ] Test
[ ] QA
[ ] Preview
[ ] Staging
[ ] Production
[ ] Sandbox
```

Default harus minimal.

Contoh:

```text
Simple project:
Local → Production

Medium project:
Local → Development → Staging → Production

High-risk project:
Local → Development → QA → Staging → Production
```

## I. Deployment

Tanyakan:

- hosting;
- container;
- VPS;
- cloud;
- serverless;
- CI/CD;
- domain;
- SSL;
- rollback;
- monitoring.

## J. Data

Tanyakan:

- database;
- schema complexity;
- sensitive data;
- PII;
- retention;
- backup;
- migration;
- seed;
- test data.

## K. Security

Tanyakan:

- authentication;
- authorization;
- secrets;
- PII;
- compliance;
- threat model;
- security level.

## L. Testing

Tawarkan default berdasarkan project:

```text
[ ] Unit
[ ] Integration
[ ] Contract
[ ] Component
[ ] E2E
[ ] Visual Regression
[ ] Accessibility
[ ] Security
[ ] Performance
[ ] Load
[ ] Smoke
```

AI harus memilih test strategy yang proporsional.

## M. Constraints

Tanyakan:

- budget;
- deadline;
- hardware;
- cloud;
- model;
- API credit;
- developer skill;
- framework restrictions;
- licensing;
- deployment restrictions.

## N. AI Preferences

Tanyakan:

- preferred AI model;
- local/cloud;
- preferred agent;
- preferred coding style;
- autonomy level;
- approval requirements.

---

# 7. SMART DEFAULT SYSTEM

Interview harus memiliki default.

Contoh:

```text
Architecture:
→ AI Recommended

Database:
→ PostgreSQL jika relational data diperlukan

Environment:
→ Local + Development + Production untuk project sederhana

Testing:
→ Unit + Integration + E2E jika relevan

UI:
→ Accessible + Responsive

Deployment:
→ Containerized jika sesuai

Git:
→ Feature branch + PR

AI autonomy:
→ L3 untuk development
→ L2 untuk production-impacting operation
```

Default tidak boleh dianggap mutlak.

Developer dapat:

```text
Accept
Modify
Custom
Skip
```

AI harus menjelaskan hanya keputusan yang penting.

Jangan membuat interview terlalu panjang.

---

# 8. PROJECT INTERVIEW OUTPUT

Setelah interview, AI harus menghasilkan:

```text
PROJECT PROFILE
PROJECT SCOPE
USER & ROLE MODEL
FEATURE MATRIX
TECH STACK
ARCHITECTURE
DATA MODEL
API CONTRACT
UI/UX STRATEGY
ENVIRONMENT MATRIX
TEST STRATEGY
SECURITY MODEL
DEPLOYMENT STRATEGY
CONSTRAINTS
ASSUMPTIONS
RISKS
AI WORKFLOW CONFIGURATION
```

Sebelum development:

> AI wajib meminta approval terhadap hasil synthesis.

Developer dapat:

```text
Approve
Edit
Regenerate
Change Decision
```

---

# 9. PROJECT DOCUMENTATION GENERATOR

Setelah approval, AI harus membuat **Project Development Documentation**.

Minimal:

```text
docs/
├── PROJECT.md
├── REQUIREMENTS.md
├── ARCHITECTURE.md
├── TECH-STACK.md
├── DESIGN-SYSTEM.md
├── API-CONTRACT.md
├── DATABASE.md
├── SECURITY.md
├── TEST-STRATEGY.md
├── ENVIRONMENTS.md
├── DEPLOYMENT.md
├── TASK-PLAN.md
├── DECISIONS.md
└── AI-CONTEXT.md
```

Tidak semua file wajib dibuat jika project tidak membutuhkannya.

Gunakan **minimum necessary documentation**.

---

# 10. DOCUMENTATION AS SOURCE OF TRUTH

Setelah documentation disetujui:

> Development harus mengikuti documentation tersebut.

AI tidak boleh sembarangan mengubah architecture atau requirement.

Jika ditemukan kebutuhan baru:

```text
New Requirement
 ↓
Impact Analysis
 ↓
Documentation Update
 ↓
Approval if needed
 ↓
Task Update
 ↓
Development
```

Jangan:

```text
New Requirement
 ↓
langsung coding
```

---

# 11. DEVELOPMENT MODE

Setelah project documentation selesai:

```text
Documentation
 ↓
Task Graph
 ↓
Agent Team
 ↓
Skill Selection
 ↓
Model Routing
 ↓
Context Retrieval
 ↓
Development
 ↓
Testing
 ↓
Review
 ↓
Integration
```

AI harus membaca dokumentasi project sebelum mengerjakan task.

Namun jangan memasukkan seluruh dokumentasi ke context.

Gunakan Context Engineering untuk mengambil hanya bagian relevan.

---

# 12. TASK MAPPING

Gunakan:

```text
PROJECT
 └── EPIC
      └── FEATURE
           └── TASK
                └── SUBTASK
```

Task minimal:

```yaml
task_id:
objective:
type:
priority:
complexity:
risk:
dependencies:
parallelizable:
required_skills:
recommended_agent:
recommended_model:
context_budget:
target_environment:
expected_artifacts:
acceptance_criteria:
test_requirements:
estimated_tokens:
estimated_cost:
autonomy_level:
status:
```

Task graph harus menentukan:

- dependency;
- critical path;
- parallel task;
- sequential task;
- duplicate work;
- task reuse.

---

# 13. PARALLEL AGENTS

Gunakan parallel agent hanya jika aman.

Contoh:

```text
             TASK GRAPH
                 │
      ┌──────────┼──────────┐
      ▼          ▼          ▼
    UI/UX     Backend    Database
      │          │          │
      └──────────┼──────────┘
                 ▼
             Integration
                 ↓
              Testing
                 ↓
               Review
```

Parallelism harus memperhatikan:

- dependency;
- file ownership;
- resource;
- contract;
- environment;
- credit;
- risk.

Gunakan isolated workspace/worktree jika diperlukan.

---

# 14. AGENT ORCHESTRATOR

Orchestrator mengatur:

```text
Understand
Plan
Decompose
Route
Schedule
Execute
Monitor
Verify
Recover
Integrate
Promote
Learn
```

Orchestrator tidak melakukan coding secara default.

Agent mengerjakan task.

---

# 15. DYNAMIC AGENT TEAM

Agent harus dibentuk sesuai kebutuhan.

Contoh SaaS:

```text
Architect
UI/UX
Frontend
Backend
Database
Testing
DevOps
Review
```

Landing page:

```text
UI/UX
Frontend
SEO
Accessibility
Testing
Review
```

Infrastructure:

```text
Architect
DevOps
Security
Testing
Review
```

Jangan menjalankan agent yang tidak diperlukan.

---

# 16. DYNAMIC SKILL SYSTEM

Skill harus modular dan dapat dimuat secara dinamis.

Contoh:

```text
UI/UX Pro Max
21st.dev
Motion.dev
Frontend
Backend
Database
Security
DevOps
Docker
Testing
Accessibility
SEO
Performance
Git
CI/CD
Cloud
```

Flow:

```text
Task
 ↓
Capability Analysis
 ↓
Skill Discovery
 ↓
Skill Selection
 ↓
Skill Load
 ↓
Execution
```

Skill Registry:

```yaml
skill_id:
name:
version:
capabilities:
compatible_agents:
compatible_models:
supported_project_types:
required_tools:
permission_scope:
cost:
quality_score:
success_rate:
```

---

# 17. MODEL ROUTER

Model harus dapat diganti tanpa kehilangan context.

Router memilih model berdasarkan:

```text
Task Complexity
Reasoning Requirement
Context Requirement
Cost
Credit Budget
Latency
Historical Performance
Privacy
Risk
Environment
```

Contoh:

```text
Complex Architecture
→ Strong reasoning model

Simple coding
→ Cheap model

High-volume repetitive task
→ Small/local model

UI task
→ UI-capable model

Critical review
→ Independent strong model
```

Model provider tidak boleh di-hard-code.

---

# 18. TOKEN OPTIMIZATION

Token optimization harus terjadi sebelum dan selama execution.

Optimalkan:

```text
Task
Context
Model
Agent
Parallelism
Cache
Research
Testing
Artifacts
```

Gunakan:

```text
Minimum Sufficient Context
```

bukan full project context.

---

# 19. CONTEXT ENGINEERING

Context lifecycle:

```text
COLLECT
 ↓
CLASSIFY
 ↓
INDEX
 ↓
RANK
 ↓
RETRIEVE
 ↓
COMPRESS
 ↓
INJECT
 ↓
MONITOR
 ↓
EVICT
 ↓
PERSIST
```

Context harus memiliki:

```text
scope
version
source
relevance
sensitivity
timestamp
```

Agent harus mengetahui context version yang digunakan.

---

# 20. MEMORY PERSISTENCE

Persistent memory:

```text
Working Memory
Project Memory
Architecture Memory
Decision Memory
Code Memory
Agent Memory
Skill Memory
Failure Memory
Test Memory
Environment Memory
Release Memory
```

Gunakan Memory Gatekeeper.

Jangan menyimpan:

- secret;
- credentials;
- raw sensitive data;

ke persistent memory biasa.

---

# 21. ARTIFACT & CONTRACT SYSTEM

Agent harus bertukar informasi melalui artifact/contract.

Contoh:

```text
Requirement Spec
Architecture Spec
API Contract
Database Contract
UI Contract
Test Contract
Deployment Spec
Release Spec
```

Gunakan versioning.

Contoh:

```text
API Contract v7
Architecture v12
Design System v4
```

Artifact harus menjadi source of truth, bukan percakapan panjang.

---

# 22. CHANGE IMPACT ANALYSIS

Sebelum perubahan besar:

```text
Code Change
 ↓
Dependency Analysis
 ↓
Impact Analysis
 ↓
Affected Components
 ↓
Affected Tests
 ↓
Affected Environments
 ↓
Risk
```

Gunakan hasilnya untuk:

- memilih test;
- memilih context;
- menentukan agent;
- menentukan environment;
- menghitung cost.

---

# 23. DYNAMIC ARCHITECTURE

Jangan memaksakan MVC.

Pilih berdasarkan:

- complexity;
- domain;
- scalability;
- risk;
- deployment;
- maintainability;
- operational requirements.

Pilihan:

```text
Simple MVC
Modular MVC
Feature-based
Layered
Clean
Hexagonal
Modular Monolith
Microservices
Event-driven
Serverless
```

Gunakan prinsip:

> Architecture follows complexity and operational requirements.

---

# 24. TESTING & VERIFICATION

Testing dipilih berdasarkan:

```text
Project Type
Change Impact
Risk
Environment
```

Contoh:

```text
Frontend
→ Unit + Component + Accessibility + Visual + E2E

Backend
→ Unit + Integration + Contract + Security

Database
→ Migration + Integrity + Rollback

Production
→ Smoke + Health Check + Monitoring
```

Agent tidak boleh menyatakan selesai hanya berdasarkan self-assessment.

Gunakan independent verification untuk critical task.

---

# 25. ENVIRONMENT MANAGEMENT

Environment lifecycle:

```text
REQUESTED
 ↓
PROVISIONING
 ↓
READY
 ↓
TESTING
 ↓
VALIDATED
 ↓
PROMOTING
 ↓
DEPLOYED
 ↓
MONITORED
```

Environment dapat:

```text
Local
Development
Test
QA
Preview
Staging
Production
Sandbox
```

Gunakan environment hanya jika diperlukan.

---

# 26. RELEASE & PROMOTION

Gunakan:

```text
Development
 ↓
Test
 ↓
QA
 ↓
Staging
 ↓
Approval
 ↓
Production
```

Tidak semua project membutuhkan semua tahap.

Gunakan prinsip:

> **Build once, promote the same artifact.**

Release harus memiliki:

```yaml
release_id:
artifact_id:
commit_sha:
source_environment:
target_environment:
test_results:
security_results:
approval:
deployment_status:
rollback_plan:
```

---

# 27. ROLLBACK

Production-impacting change harus memiliki rollback strategy.

Support:

```text
Code Rollback
Deployment Rollback
Configuration Rollback
Feature Flag Rollback
Database Rollback
```

Database rollback dianggap high-risk.

---

# 28. SECURITY & PERMISSION

Pisahkan:

> Capability ≠ Permission

Agent dapat memiliki skill tertentu tetapi tidak otomatis memiliki permission untuk menjalankannya terhadap production.

Gunakan:

```text
Least Privilege
Scoped Permission
Environment-specific Permission
Audit Trail
Secret Management
Data Classification
Model Access Policy
```

---

# 29. COST GOVERNOR

Setiap task memiliki:

```text
estimated_tokens
estimated_cost
priority
value
risk
```

Router menentukan:

```text
Premium Model
→ Medium Model
→ Cheap Model
→ Local Model
```

berdasarkan kebutuhan.

Jangan mengejar cost terendah jika kualitas kritis.

Optimalkan:

```text
Token
Credit
Compute
Time
```

secara bersamaan.

---

# 30. CACHE SYSTEM

Cache:

```text
Project Analysis
Architecture Analysis
Codebase Map
Research
Documentation
Test Results
Build Results
Environment State
Model Responses
```

Prinsip:

> **Never pay twice for knowledge you already possess.**

Cache harus versioned dan memiliki expiry/validation jika diperlukan.

---

# 31. CONTINUOUS LEARNING

Learning berasal dari:

```text
Success
Failure
Cost
Latency
Quality
Tests
Reviews
Deployment
Rollback
Human Feedback
```

Learning target:

```text
Model Routing
Skill Selection
Task Decomposition
Context Selection
Testing Strategy
Cost Strategy
Agent Selection
Environment Strategy
```

Learning tidak boleh langsung mengubah production behavior.

---

# 32. EVALUATION ENGINE

Sebelum policy hasil learning diterapkan:

```text
Learning Candidate
 ↓
Historical Evaluation
 ↓
Benchmark
 ↓
Compare
 ↓
Quality Gate
 ↓
Policy Update
```

Evaluasi minimal:

```text
Quality
Cost
Latency
Reliability
```

---

# 33. FAILURE RECOVERY

Gunakan:

```text
Failure
 ↓
Root Cause Analysis
 ↓
Strategy Change
 ↓
Retry
 ↓
Verification
 ↓
Escalation
```

Jangan mengulang strategy yang sama tanpa alasan.

Escalation:

```text
Cheap Model
 ↓
Medium Model
 ↓
Strong Model
 ↓
Specialist Agent
 ↓
Human
```

---

# 34. CONFLICT RESOLUTION

Untuk parallel agent:

```text
Conflict Detector
 ↓
Textual Conflict
Semantic Conflict
Contract Conflict
Architecture Conflict
 ↓
Resolver
 ↓
Verification
```

Jangan mengandalkan textual Git merge saja.

---

# 35. GIT TRACEABILITY

Hubungkan:

```text
Human Intent
→ Requirement
→ Task
→ Agent
→ Model
→ Skill
→ Artifact
→ Commit
→ Test
→ Release
→ Deployment
```

Setiap perubahan harus dapat ditelusuri.

---

# 36. CHECKPOINT & RESUME

Checkpoint harus menyimpan:

```text
Project State
Task State
Architecture State
Memory State
Context State
Artifact State
Git State
Test State
Environment State
Deployment State
Known Issues
Next Actions
Rollback State
```

Jika AI/model diganti atau session terputus, workflow harus dapat dilanjutkan.

---

# 37. RESOURCE SCHEDULER

Parallel execution harus mempertimbangkan:

```text
CPU
RAM
GPU
API Concurrency
Rate Limit
Token Budget
Credit Budget
Latency
Priority
Environment Capacity
```

Tujuannya bukan maximum parallelism.

Tujuannya:

> **Optimal throughput under resource and cost constraints.**

---

# 38. OBSERVABILITY

Workflow harus dapat menjawab:

```text
Task apa yang gagal?
Agent mana?
Model apa?
Skill apa?
Context apa?
Berapa token?
Berapa credit?
Artifact apa?
Test apa?
Environment mana?
Commit mana?
Release mana?
Siapa yang approve?
```

Gunakan tracing dan audit trail.

---

# 39. ANTI-DUPLICATION

Sebelum task dijalankan:

```text
Existing Work?
Existing Artifact?
Existing Component?
Existing Test?
Existing Research?
Existing Context?
Existing Environment?
```

Prioritas:

```text
REUSE
→ MODIFY
→ CREATE
```

---

# 40. ANTI-LOOP

Simpan:

```text
Attempt Counter
Strategy History
Failure History
Root Cause
Escalation Threshold
```

Agent harus mengubah strategy setelah repeated failure.

---

# 41. DOCUMENTATION DRIFT CONTROL

Project documentation harus selalu konsisten dengan codebase.

Gunakan:

```text
Code Change
 ↓
Documentation Impact Analysis
 ↓
Documentation Update Required?
 ↓
Update
 ↓
Validation
```

Jika code dan documentation tidak sinkron, workflow harus menandainya sebagai drift.

---

# 42. DEVELOPER EXPERIENCE

Workflow harus terasa sederhana.

Developer seharusnya tidak perlu memahami seluruh internal architecture untuk menggunakannya.

Entry point ideal:

```text
"Gunakan workflow ini untuk project saya:
<GitHub Workflow URL>"
```

Kemudian AI:

```text
1. Membaca workflow
2. Menjelaskan bahwa workflow siap
3. Memulai project interview
4. Menawarkan pilihan
5. Menerima custom input
6. Menghasilkan project documentation
7. Meminta approval
8. Membuat task graph
9. Mulai development
```

Workflow internal boleh kompleks.

**Developer interface harus sederhana.**

---

# 43. WORKFLOW INVOCATION PROTOCOL

Dokumentasi workflow harus menjelaskan secara eksplisit cara menerapkannya.

Minimal dokumentasikan:

```text
Prerequisites
Installation / Access
How to provide workflow URL
How AI should initialize
How interview works
How project documentation is generated
How approval works
How development starts
How context is persisted
How model is switched
How workflow resumes
How deployment works
```

Berikan contoh penggunaan:

```text
Developer:

Gunakan workflow ini untuk project baru:
https://github.com/ArrowTin/Universal-Workflow-VC/blob/main/WORKFLOW.md

Project saya adalah aplikasi SaaS untuk...
```

AI kemudian mengikuti workflow tanpa developer harus copy seluruh workflow ke conversation.

Jika platform AI tidak dapat membaca URL langsung, dokumentasikan fallback:

```text
Download WORKFLOW.md
Attach WORKFLOW.md
Paste workflow
Install workflow into project repository
```

---

# 44. WORKFLOW REPOSITORY STRUCTURE

Rancang struktur repository workflow yang reusable.

Contoh:

```text
ai-vibe-workflow/
│
├── README.md
├── WORKFLOW.md
├── QUICKSTART.md
├── INTERVIEW.md
├── AGENTS.md
├── SKILLS.md
├── MODELS.md
├── MEMORY.md
├── CONTEXT.md
├── TOKEN-OPTIMIZATION.md
├── TESTING.md
├── SECURITY.md
├── ENVIRONMENTS.md
├── RELEASE.md
├── RECOVERY.md
├── LEARNING.md
├── TEMPLATES/
│   ├── PROJECT.md
│   ├── REQUIREMENTS.md
│   ├── ARCHITECTURE.md
│   ├── TECH-STACK.md
│   ├── DATABASE.md
│   ├── API-CONTRACT.md
│   ├── TEST-STRATEGY.md
│   ├── ENVIRONMENTS.md
│   ├── DEPLOYMENT.md
│   ├── DECISIONS.md
│   └── AI-CONTEXT.md
└── EXAMPLES/
```

Struktur boleh disederhanakan jika tidak diperlukan.

---

# 45. WORKFLOW VERSIONING

Workflow universal harus memiliki version.

Contoh:

```text
Workflow v1.0
Workflow v1.1
Workflow v2.0
```

Project harus menyimpan:

```yaml
workflow_version:
project_workflow_version:
```

Jika workflow berubah, project lama tidak boleh otomatis rusak.

Gunakan compatibility policy.

---

# 46. PROJECT BOOTSTRAP

Saat workflow diterapkan pada project baru:

```text
WORKFLOW
    ↓
PROJECT DISCOVERY
    ↓
PROJECT PROFILE
    ↓
INTERVIEW
    ↓
PROJECT DOCUMENTATION
    ↓
APPROVAL
    ↓
TASK GRAPH
    ↓
DEVELOPMENT
```

Project documentation harus dapat disimpan di repository project.

Contoh:

```text
/project
├── src/
├── tests/
├── docs/
│   ├── PROJECT.md
│   ├── REQUIREMENTS.md
│   ├── ARCHITECTURE.md
│   ├── TECH-STACK.md
│   ├── TEST-STRATEGY.md
│   ├── ENVIRONMENTS.md
│   └── AI-CONTEXT.md
└── ...
```

---

# 47. DEVELOPMENT CONTINUATION

Jika developer kembali beberapa hari kemudian dan berkata:

```text
"Lanjutkan project."
```

AI harus:

```text
Load Workflow Version
 ↓
Load Project Documentation
 ↓
Load Checkpoint
 ↓
Inspect Git State
 ↓
Inspect Task State
 ↓
Inspect Environment
 ↓
Retrieve Relevant Context
 ↓
Resume
```

Jangan mengandalkan conversation history sebagai satu-satunya sumber continuity.

---

# 48. PROJECT COMPLETION

Project tidak dianggap selesai hanya karena code telah dibuat.

Definition of Done harus mencakup sesuai kebutuhan:

```text
Requirement satisfied
Code implemented
Tests passed
Security validated
Documentation synchronized
Architecture validated
Build successful
Environment validated
Deployment successful
Health checks passed
Release recorded
Checkpoint saved
```

---

# 49. FINAL DESIGN GOAL

Rancang workflow dengan mental model:

```text
                  UNIVERSAL WORKFLOW
                         │
                         ▼
                  PROJECT INTERVIEW
                         │
                         ▼
                 PROJECT PROFILE
                         │
                         ▼
             PROJECT DOCUMENTATION
                         │
                    APPROVAL
                         │
                         ▼
                    TASK GRAPH
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
           AGENT       AGENT       AGENT
             │           │           │
           SKILL       SKILL       SKILL
             │           │           │
           MODEL       MODEL       MODEL
             │           │           │
             └───────────┼───────────┘
                         ▼
                    ARTIFACTS
                         │
                         ▼
                 CHANGE IMPACT
                         │
                         ▼
                     TESTING
                         │
                         ▼
                  VERIFICATION
                         │
                    ┌────┴────┐
                    ▼         ▼
                 SUCCESS    FAILURE
                    │         │
                    ▼         ▼
                INTEGRATE   RECOVER
                    │
                    ▼
                 PROMOTE
                    │
                    ▼
                 DEPLOY
                    │
                    ▼
                OBSERVE
                    │
                    ▼
                 MEMORY
                    │
                    ▼
                 LEARNING
                    │
                    ▼
                NEXT TASK
```

---

# 50. OUTPUT INSTRUCTION

Sekarang rancang **WORKFLOW DOCUMENTATION BLUEPRINT**, bukan application code.

Output harus menjelaskan:

1. konsep workflow;
2. architecture;
3. cara workflow disimpan;
4. struktur GitHub repository workflow;
5. cara developer menerapkan workflow;
6. bagaimana AI membaca workflow;
7. bagaimana interview berjalan;
8. bagaimana pilihan/default/custom input bekerja;
9. bagaimana project documentation dihasilkan;
10. bagaimana approval dilakukan;
11. bagaimana development menggunakan documentation;
12. bagaimana model dapat diganti;
13. bagaimana memory dipertahankan;
14. bagaimana token dioptimalkan;
15. bagaimana credit dioptimalkan;
16. bagaimana agent berjalan paralel;
17. bagaimana skill dinamis bekerja;
18. bagaimana architecture/MVC dinamis;
19. bagaimana testing bekerja;
20. bagaimana environment dikelola;
21. bagaimana deployment dan rollback bekerja;
22. bagaimana failure recovery bekerja;
23. bagaimana continuous learning bekerja;
24. bagaimana workflow dapat di-version;
25. bagaimana project dapat resume setelah session/model berubah.

---

# 51. END-TO-END EXAMPLE

Gunakan contoh:

```text
Developer:

Gunakan workflow ini:
https://github.com/example/ai-vibe-workflow/blob/main/WORKFLOW.md

Saya ingin membuat SaaS dashboard analytics.
```

Simulasikan:

```text
Workflow Loaded
 ↓
Project Interview
 ↓
Questions + Defaults + Custom Options
 ↓
Developer Answers
 ↓
Requirement Synthesis
 ↓
Architecture Recommendation
 ↓
Technology Recommendation
 ↓
Environment Recommendation
 ↓
Testing Recommendation
 ↓
Project Documentation
 ↓
Approval
 ↓
Task Graph
 ↓
Dynamic Agent Team
 ↓
Skill Selection
 ↓
Model Routing
 ↓
Parallel Development
 ↓
Testing
 ↓
Verification
 ↓
Integration
 ↓
Staging
 ↓
Production
 ↓
Monitoring
 ↓
Memory Update
```

Tunjukkan juga bagaimana developer dapat mengganti model di tengah development tanpa kehilangan context.

---

# 52. TOKEN & CREDIT OPTIMIZATION EXAMPLE

Bandingkan:

## Naive Workflow

```text
One Agent
+
Full Context
+
Premium Model
+
Repeated Research
+
Repeated Testing
+
No Cache
+
No Task Mapping
```

dengan:

## Optimized Workflow

```text
Task Graph
+
Specialized Agents
+
Minimum Sufficient Context
+
Model Routing
+
Skill Routing
+
Context Cache
+
Research Cache
+
Artifact Contracts
+
Change Impact Testing
+
Parallel Execution
```

Berikan estimasi konseptual:

```text
Token
Credit
Latency
Rework
```

dan jelaskan mengapa optimized workflow lebih efisien.

---

# 53. FAILURE SIMULATION

Simulasikan minimal:

1. model utama unavailable;
2. model diganti;
3. agent gagal;
4. task conflict;
5. context terlalu besar;
6. credit hampir habis;
7. test gagal;
8. deployment gagal;
9. documentation drift;
10. production rollback.

Untuk setiap kasus tunjukkan:

```text
Detection
→ Decision
→ Recovery
→ Verification
→ Memory Update
```

---

# 54. FINAL SELF-EVALUATION

Setelah merancang workflow, evaluasi:

```text
Simplicity
Reusability
Model Agnosticism
Token Efficiency
Credit Efficiency
Context Continuity
Memory Persistence
Parallelism
Skill Extensibility
Testing
Security
Environment Management
Deployment Safety
Recovery
Observability
Learning
Developer Experience
Maintainability
```

Identifikasi:

```text
Top 5 weaknesses
Top 5 token waste sources
Top 5 credit waste sources
Top 5 failure modes
Top 5 complexity risks
```

Kemudian sederhanakan desain jika ada komponen yang sebenarnya belum diperlukan.

---

# 55. FINAL PRINCIPLES

Gunakan prinsip:

```text
INTENT > PROMPT
SPECIFICATION > GUESSING
CONTEXT > MODEL
ARTIFACT > CONVERSATION
CONTRACT > ASSUMPTION
TASK > CHAT
POLICY > AUTONOMY
VERIFICATION > SELF-ASSESSMENT
REUSE > MODIFY > CREATE
CACHE > RECOMPUTE
MINIMUM SUFFICIENT CONTEXT > FULL CONTEXT
PARALLEL WHEN SAFE
SEQUENTIAL WHEN NECESSARY
CHEAP MODEL WHEN SUFFICIENT
STRONG MODEL WHEN NECESSARY
BUILD ONCE > REBUILD
PROMOTE > RECREATE
CHECKPOINT > MEMORYLESS EXECUTION
DOCUMENTATION > IMPLICIT KNOWLEDGE
EVALUATED LEARNING > BLIND LEARNING
SIMPLE INTERFACE > COMPLEX USER EXPERIENCE
```

---

# 56. ULTIMATE OBJECTIVE

Hasil akhirnya harus memungkinkan workflow universal disimpan sekali di GitHub dan diterapkan ke banyak project.

Developer cukup memberikan referensi workflow kepada AI Vibe Coding.

AI kemudian melakukan:

```text
READ WORKFLOW
      ↓
INTERVIEW DEVELOPER
      ↓
UNDERSTAND PROJECT
      ↓
ASK SMART QUESTIONS
      ↓
OFFER DEFAULTS
      ↓
ACCEPT CUSTOM DECISIONS
      ↓
GENERATE PROJECT DOCUMENTATION
      ↓
GET APPROVAL
      ↓
CREATE TASK GRAPH
      ↓
FORM DYNAMIC AGENT TEAM
      ↓
SELECT SKILLS
      ↓
SELECT MODELS
      ↓
OPTIMIZE CONTEXT
      ↓
EXECUTE PARALLEL WORK
      ↓
TEST
      ↓
VERIFY
      ↓
INTEGRATE
      ↓
PROMOTE
      ↓
DEPLOY
      ↓
OBSERVE
      ↓
PERSIST MEMORY
      ↓
LEARN
      ↓
CONTINUE
```

Workflow universal harus tetap sederhana dari sisi developer:

> **One workflow → one project interview → one generated project documentation set → development follows the documentation.**

Sedangkan kompleksitas internal ditangani oleh workflow engine.

Tujuan akhirnya bukan membuat developer belajar menggunakan banyak AI agent.

Tujuan akhirnya adalah membuat developer cukup mengatakan:

> **"Gunakan workflow ini untuk membangun project saya."**

dan AI memiliki operating procedure yang konsisten untuk memahami, merencanakan, membangun, menguji, memverifikasi, mendokumentasikan, dan menyelesaikan project tersebut.

