# pantheon_project
# Pantheon Congestion Control Evaluation

This repository accompanies the report submitted for **Programming Assignment 3** in **Computer Networks**. It contains the full setup, scripts, and results for evaluating three modern congestion control algorithms: **CUBIC**, **BBR**, and **Copa**, using the **Pantheon** testbed and **Mahimahi** emulated networks.

---

## 📦 Contents

- ✅ Test results for:
  - CUBIC
  - BBR
  - Copa
- 📊 Analysis scripts to generate:
  - Time-series throughput
  - RTT over time
  - Packet loss trends
  - Throughput vs RTT trade-offs
- 🔁 Shell script to automate experiment runs
- 📝 Final report (PDF/Markdown)

---

## 🛠️ How to Reproduce

1. **Install Pantheon and Mahimahi**

   Follow the official Pantheon install guide:

   ```bash
   git clone https://github.com/StanfordSNR/pantheon
   cd pantheon
   ./install_deps.sh
