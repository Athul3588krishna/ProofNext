# ProofNest 🛡️
> **AI-Powered SaaS Platform for Verifiable Digital Work Evidence**

ProofNest is an AI-powered Software-as-a-Service (SaaS) platform designed to verify and document digital work through automatically collected and analyzed evidence across multiple digital work platforms.

---

## 📌 Abstract & Problem Statement

In modern remote and distributed work environments, organizations often depend on self-reported updates, screenshots, task descriptions, and manual progress reports to determine whether assigned work has actually been completed. This traditional approach is:
- **Time-consuming** for both contributors and reviewers.
- **Inconsistent & subjective**, lacking clear objective benchmarks.
- **Vulnerable to misrepresentation**, making it hard to reliably verify work integrity.

### 💡 The Solution
**ProofNest** bridges this gap by automatically gathering cross-platform activity records into a chronological evidence timeline. An AI analysis engine benchmarks collected digital footprints against declared deliverables, highlights discrepancies or missing evidence, and computes an objective **Work Verification Score** alongside comprehensive audit reports.

---

## 🚀 Key Features

- **Multi-Source Evidence Aggregation**: Connects to digital work platforms (GitHub, Figma, Google Drive/Cloud Storage, Task Managers like Jira/Trello).
- **Chronological Evidence Timeline**: Structured, tamper-evident stream of commit histories, artifact uploads, and document iterations.
- **AI Verification & Anomaly Detection**:
  - Compares declared tasks vs. real recorded output.
  - Highlights irregular work intervals, missing artifacts, or shallow submissions.
  - Generates confidence ratings and work integrity scores.
- **Centralized Verification Dashboard**:
  - For **Contributors/Freelancers**: Showcase verified proof of work with verifiable links.
  - For **Managers/Agencies**: Monitor team deliverables, review evidence trails, and export PDF/JSON compliance reports.
- **Multi-Tenant SaaS Architecture**: Secure workspace separation, role-based access control (RBAC), and team-level policy customization.

---

## 👥 Target Audience & Use Cases

- **Freelancers & Agencies**: Provide proof of authentic work deliverables to avoid milestone payment disputes.
- **Remote & Distributed Teams**: Transparent progress tracking without invasive surveillance or constant manual status meetings.
- **Internship & Mentorship Programs**: Objective tracking of student/intern progress and automated completion verification.
- **Educational & Capstone Projects**: Assure genuine contribution and team participation.

---

## 🛠️ Tech Stack

- **Frontend**: React (Vite), Modern UI Design with responsive dashboard aesthetics
- **Backend**: Node.js, Express.js
- **Integrations / APIs**: GitHub REST API, Cloud Storage connectors, Webhooks
- **AI Engine**: LLM verification pipelines for deliverable comparison and report generation

---

## 📦 Getting Started

### 1. Clone & Setup
```bash
git clone <repository-url>
cd ProofNext
```

### 2. Install Dependencies
```bash
# Root & Backend dependencies
npm install

# Client dependencies
cd client
npm install
cd ..
```

### 3. Run the Development Environment
```bash
# Start backend server
npm run server

# Start client development server
cd client
npm run dev
```

---

## 📄 License
ISC License
