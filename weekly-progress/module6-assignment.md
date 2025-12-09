# Module 6: Setup and Deploy First Project

**Student:** Andrey Carvajal  
**Date:** November 9, 2025  
**Course:** CSN-190

---

## Assignment Overview

Hands-on deployment of AI-Powered Phishing Detection System from GitHub, including installation, testing, and comprehensive documentation of the process.

---

## Project Deployed

**Repository:** AI-Powered Phishing Detection System  
**URL:** https://github.com/GauravGhandat-23/AI-Powered-Phishing-Detection-System  
**Author:** GauravGhandat-23

---

## Setup Steps Completed

### 1. Environment Preparation
- Created CSN190 project workspace folder
- Opened VS Code with integrated terminal
- Verified Python 3.12.6 installation

### 2. Repository Cloning
```bash
git clone https://github.com/GauravGhandat-23/AI-Powered-Phishing-Detection-System
cd AI-Powered-Phishing-Detection-System
```

### 3. Virtual Environment Setup
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

### 4. Dependency Installation
```bash
pip install -r requirements.txt
```

**Packages Installed:** pandas, scikit-learn, streamlit, nltk, beautifulsoup4, numpy, scipy, and 30+ dependencies

### 5. Application Launch
```bash
streamlit run phishing_detection.py
```

**Result:** Application successfully launched at `http://localhost:8501`

---

## Problems Encountered and Solutions

### Problem 1: Requirements File Not Found

**Error:** `ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'`

**Cause:** Running pip install from wrong directory (CSN190 parent folder instead of project subfolder)

**Solution:** 
```bash
cd AI-Powered-Phishing-Detection-System
pip install -r requirements.txt
```

**Lesson Learned:** Always verify current directory with `pwd` or `cd` before running file commands.

---

### Problem 2: Virtual Environment Activation

**Issue:** PowerShell blocked script execution, `(venv)` didn't appear in prompt

**Solution:** Switched from PowerShell to Command Prompt, ran activation command again

**Lesson Learned:** Different shells have different security policies; be aware of which terminal you're using.

---

## Testing Results

### Test Case 1: Phishing Email
**Input:**
