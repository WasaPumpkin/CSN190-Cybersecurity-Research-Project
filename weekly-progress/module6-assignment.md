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
**Result:** `Prediction: Phishing` ✅

**Analysis:** Model correctly identified urgency language, threats, and suspicious URL.

---

### Test Case 2: Legitimate Email
**Input:**
**Result:** `Prediction: Legitimate` ✅

**Analysis:** Model recognized natural conversational tone and absence of threats.

---

## What I Learned

### Technical Skills
- Python virtual environment management
- Git repository cloning and navigation
- Dependency installation with pip
- Streamlit web application deployment
- Systematic troubleshooting approach

### ML/Security Concepts
- How NLP preprocessing works (tokenization, stopword removal)
- Random Forest classification in practice
- Real-time threat detection systems
- Trade-offs between false positives and false negatives

### Problem-Solving Skills
- Using AI tools (GitHub Copilot) effectively for debugging
- Reading error messages carefully for clues
- Verifying assumptions (current directory, file locations)
- Persistent troubleshooting when issues arise

---

## How AI Agent Helped

**GitHub Copilot Assistance:**
- Diagnosed directory navigation error immediately when asked: "Why can't pip find requirements.txt?"
- Explained PowerShell execution policy restrictions
- Suggested alternative terminal options
- Provided context for error messages

**Impact:** Saved approximately 15-20 minutes of frustration by providing targeted solutions exactly when needed.

---

## Documentation Created

✅ **Module6-setup-log.md** - Detailed deployment documentation  
✅ **Screenshots** - Application interface, terminal outputs, successful prediction  
✅ **Setup Guide** - Step-by-step tutorial for others to replicate

---

## Connection to Final Project

This deployment experience:
- Validated my topic choice (phishing detection is achievable)
- Provided working reference implementation
- Identified ML concepts I need to understand deeper
- Gave hands-on experience with tools I'll use (scikit-learn, Streamlit)
- Built confidence that I can deploy ML security systems

---

**Status:** Completed  
**Application Status:** Successfully deployed and tested  
**Submitted:** November 9, 2025
