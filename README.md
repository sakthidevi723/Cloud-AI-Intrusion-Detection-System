# 🛡️ Cloud-AI Intrusion Detection System (IDS) - Project Blueprint

A comprehensive system architecture framework utilizing Machine Learning (Random Forest Classification) and AWS Cloud Services to detect multi-vector network traffic anomalies and zero-day threat patterns.

---

## 🏗️ System Architecture & Data Flow Workflow

1. **Ingestion Layer:** Raw network packet traces extracted sequentially via benchmark **CICIDS 2017 Dataset** feature sets (Flow Duration, Packet Size Matrix, Header Length Flags).
2. **AI Inference Pipeline Core:** Cleaned network vectors evaluated inside a unified **Python-Native Full-Stack Environment using Streamlit** hosting a baseline Random Forest Classifier (~97.2% Precision target).
3. **Cloud Infrastructure Core:** Microservice hosted inside an **AWS EC2 (Elastic Compute Cloud) Virtual Linux Machine**, utilizing an absolute independent routing subnet infrastructure for centralized security alert monitoring.

---

## 📁 Active Modules Deployment Roadmap (4-Week Agile Sprint)

### 🚀 Phase 1: Environment Provisioning & Blueprint Layout (CURRENT MILESTONE)
- **Status:** `Active Baseline Framework Locked`
- Finalized repository file structures, dependency frameworks, and deployment target layouts on GitHub.

### 🧠 Phase 2: Google Colab Training Engine Training Loop
- **Status:** `Pending Sequence Initialization (Week 2)`
- Constructing the training engine script over Google Colab notebooks using Pandas, NumPy, and Scikit-Learn libraries to serialize model weights into binary format snapshots.

### 📊 Phase 3: Streamlit Interactive Interface Engine Assembly 
- **Status:** `Pending Integration Testing (Week 3)`
- Scripting the interface script (`app.py`) for live parsing controls and dashboard visualization logic without legacy frontend overhead.

### ☁️ Phase 4: Live AWS EC2 Machine Infrastructure Provisioning
- **Status:** `Pending Deployment Pipeline Setup (Week 4)`
- Moving final files directly via automated Git branches, provisioning an EC2 container subnet, mapping environment configs, and generating live public access endpoints.

---

## 🛠️ Global Stack Requirements Matrix
- **Language Stack:** Python 3.x
- **Core ML Foundations:** Scikit-Learn, Pandas, NumPy
- **Full-Stack Wrapper Engine:** Streamlit Framework
- **Cloud Infrastructure Backbone:** AWS Architecture (EC2 Computing instances, S3 Monitoring logging telemetry)
