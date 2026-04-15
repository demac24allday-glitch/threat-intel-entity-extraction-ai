# Threat Intelligence Extraction with spaCy & LLaMA 3

Threat intelligence extraction using spaCy and LLaMA 3 via Ollama.

# 🛡️ Threat Intelligence Extraction with spaCy & LLaMA 3

This project extracts threat indicators from unstructured text using spaCy and enhances analysis using LLaMA 3 via Ollama.

---

## 📌 Project Overview
This lab demonstrates how natural language processing (NLP) and generative AI can be used together to analyze cybersecurity threat reports. Using spaCy, the script extracts threat-related entities such as IP addresses, dates, locations, and attack types. A locally running LLaMA 3 model is then used to generate a threat summary and mitigation recommendations.

---

## 🎯 Objectives
- Extract threat indicators from unstructured text
- Identify key entities such as IP, date, location, and attack type
- Use AI to summarize threats and recommend mitigation
- Simulate a SOC-style threat analysis workflow

---

## 🧰 Tools Used
- spaCy
- Ollama
- LLaMA 3
- Python
- Kali Linux

---

## ⚙️ Setup

### Install dependencies
```bash
sudo apt-get install zstd
sudo apt install pciutils
sudo apt install pipx
pipx install spacy
~/.local/share/pipx/venvs/spacy/bin/python -m spacy download en_core_web_sm

curl -fsSL https://ollama.com/install.sh | sh

ollama run llama3

~/.local/share/pipx/venvs/spacy/bin/python threat_extract_script.py

Multiple failed login attempts detected from IP 192.168.1.100 targeting the SSH service on June 27 in Mumbai.


Then click **Commit changes**.

---

# Step 7: Fix the screenshot names in the README

In the README you just pasted, these lines need your real screenshot file names:

```markdown
![Script Execution](screenshots/your-script-execution-image.png)
![Extracted Entities](screenshots/your-json-output-image.png)
![AI Analysis](screenshots/your-final-ai-output-image.png)


