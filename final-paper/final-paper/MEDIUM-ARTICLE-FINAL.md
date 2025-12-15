# AI-Powered Phishing Detection System - Medium Article

**Published on Medium:** https://medium.com/@andycarsan10/74ea8323b19e

**Author:** Andrey Carvajal  
**Date:** December 2025  
**Course:** CSN-190

---
# From Clone to Detection: Deploying an AI-Powered Phishing Detection System in Under an Hour

**By Andrey Carvajal**  
*Cybersecurity Student | Bronx Community College*  
*Course: CSN-190 with Professor Edwin Reed-Sanchez*  
*Date: December 2025*


**📧 Contact:** your.email@example.com  


---

## Introduction

Every day, 3.4 billion phishing emails flood inboxes worldwide, and 90% of data breaches start with phishing. After studying these statistics, I wondered: could machine learning actually catch these attacks? Could I—a student—deploy a real AI detection system myself?

In this article, I'll walk you through my journey deploying an open-source AI-Powered Phishing Detection System from GitHub in under an hour. I'll share every command, error, and solution so you can replicate this process. Whether you're a cybersecurity student like me, a developer curious about ML security applications, or someone who just wants to understand how AI fights phishing, you'll get a practical, honest look at what it takes to deploy a working threat detection system.

By the end, you'll understand not just how to set up this specific tool, but also how machine learning approaches phishing detection, why it matters in today's threat landscape, and what challenges you'll face deploying AI security tools. Fair warning: I made mistakes and got stuck—but that's exactly what made this valuable.

---

## Purpose and Background

### Why I Chose This Project

I wanted to work at the intersection of AI and cybersecurity—two rapidly growing fields. Phishing is the #1 attack vector, yet traditional email filters struggle with sophisticated attacks. I chose the AI-Powered Phishing Detection System by GauravGhandat-23 because it demonstrates a complete implementation using Python, scikit-learn, NLP, and Streamlit—all technologies relevant to my career goals.

### Understanding the Tool

This system uses a Random Forest classifier to analyze email text and URLs, identifying phishing patterns. Unlike simple keyword filters, it recognizes combinations of features: urgency language, suspicious URLs, threat indicators, and linguistic patterns. The pre-trained model processes emails instantly, flagging threats for human review.

In real security operations centers (SOCs), similar systems scan thousands of emails daily, automating first-line defense so analysts can focus on complex cases. This is exactly the "human-in-the-loop" approach industry leaders like Cloudflare use.

### My Initial Concerns

I had intermediate Python skills but had never deployed a complete ML application. Would installation work smoothly? Would I understand the results? Could it catch sophisticated phishing, or just obvious scams? I was excited but nervous about whether this would be a surface-level "it runs" experience or genuine learning.

---

## Installation and Setup Tutorial

**💻 Complete setup code available in my GitHub repository:** [Link to your repo]

### Prerequisites

- **Python 3.9+** (I used Python 3.12.6)
- **VS Code** or any code editor
- **Git** for cloning
- **4GB RAM minimum**
- **Windows, macOS, or Linux**

### Step 1: Create Project Workspace

```bash
cd Desktop
mkdir CSN190
cd CSN190
```

**Why:** Organized workspace makes managing projects easier.

### Step 2: Clone the Repository

```bash
git clone https://github.com/GauravGhandat-23/AI-Powered-Phishing-Detection-System
```

**What happens:** Downloads all code, models, and files to your machine.

**Expected output:**
```
Cloning into 'AI-Powered-Phishing-Detection-System'...
Receiving objects: 100% (25/25), 272.50 KiB, done.
```

**Troubleshooting:**
- **"'git' not recognized"** → Install Git from https://git-scm.com
- **Slow download** → Check internet connection

### Step 3: Navigate to Project

```bash
cd AI-Powered-Phishing-Detection-System
dir  # Windows (or 'ls' on Mac/Linux)
```

You should see: `phishing_detection.py`, `phishing_model.pkl`, `requirements.txt`, `emails.csv`

### Step 4: Create Virtual Environment

```bash
python -m venv venv
```

**Why:** Isolates project dependencies from your system Python.

### Step 5: Activate Virtual Environment

**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

**Success indicator:** `(venv)` appears at start of terminal prompt.

**Troubleshooting:**
- **PowerShell blocks scripts** → Use Command Prompt instead

### Step 6: Install Dependencies

```bash
pip install -r requirements.txt
```

**What's installed:** pandas, scikit-learn, streamlit, nltk, beautifulsoup4, numpy, scipy (40+ packages total)

**Time:** 3-5 minutes

**My Error:** Initially ran this from wrong directory and got "file not found." **Solution:** Made sure I was inside the AI-Powered-Phishing-Detection-System folder first.

### Step 7: Launch the Application

```bash
streamlit run phishing_detection.py
```

**What happens:**
- Streamlit loads the ML model
- Browser automatically opens to `http://localhost:8501`
- Application interface appears

**Total setup time:** 15-20 minutes

**AI Tool Note:** I used GitHub Copilot to troubleshoot the directory error. Asked: "Why can't pip find requirements.txt?" It immediately identified I was in the wrong folder—saved 10 minutes of frustration.

---

## Using the Software - Practical Example

**📊 See full testing results and analysis in my GitHub repository**

### Test Case 1: Obvious Phishing

**Test Email:**
```
URGENT: Your account has been suspended! Click here immediately to verify: 
http://suspicious-bank-login.tk/verify?id=12345 or your account will be 
permanently closed within 24 hours!
```

**Result:** `Prediction: Phishing` ✓

**What the model detected:**
- High-risk keywords: "urgent," "suspended," "verify"
- Suspicious URL structure
- Threat language patterns

### Test Case 2: Legitimate Email

**Test Email:**
```
Hi there, this is a reminder about our team meeting tomorrow at 2 PM in 
Conference Room B. Please bring your project updates.
```

**Result:** `Prediction: Legitimate` ✓

### Test Case 3: Sophisticated Phishing

**Test Email:**
```
Hello Andrey,

I hope this email finds you well. I'm reaching out from IT regarding 
mandatory security updates. We've detected unusual activity on your account.

Please use this secure link: https://company-portal-secure.com/login

Best regards, IT Security Team
```

**Result:** `Prediction: Phishing` ✓

**Impressive!** The model caught this despite professional tone and personalization.

### Performance Summary

Tested 20+ emails total:
- **Accuracy:** 85-90% correct classifications
- **Speed:** 0.3-0.8 seconds per email
- **Strengths:** Catches urgency-based phishing, suspicious URLs
- **Limitations:** Occasionally confused by very short emails

---

## Research Insights

**📚 Full research analysis and bibliography available on GitHub**

### Academic Research

**Source:** Tamal, M. A., et al. (2024). Unveiling suspicious phishing attacks. *Frontiers in Computer Science, 6*, 1428013.

**Key Findings:**
- Tested on 274,446 URLs
- Random Forest achieved **97.52% accuracy**
- Validated importance of feature engineering

**Connection:** This validates Random Forest as optimal. My 85-90% accuracy is respectable for an educational implementation.

### Industry Implementation

**Source:** Cloudflare. (2024). How Cloudflare is using automation to tackle phishing.

**Key Findings:**
- Improved automation from 37% to 78%
- Reduced response time from 3.4 days to under 1 hour
- Emphasizes "human-in-the-loop" approach

**Connection:** Shows the same technology scales from student projects to global infrastructure.

---

## Challenges and Problem-Solving

### Challenge 1: "Requirements File Not Found"

**Error:** `ERROR: Could not open requirements file`

**Solution:** GitHub Copilot identified I was in wrong directory. Used `cd AI-Powered-Phishing-Detection-System` first.

**Lesson:** Always verify current directory before running commands.

### Challenge 2: Virtual Environment Not Activating

**Problem:** PowerShell blocked script execution.

**Solution:** Switched to Command Prompt.

### Challenge 3: Understanding How It Works

**Solution:** 
- Asked specific AI questions
- Tested edge cases
- Read research papers

**The "aha!" moment:** The model converts text to numerical vectors, then uses math to classify patterns.

---

## Conclusion and Future Applications

### What I Accomplished

Successfully deployed, tested, and analyzed a production-grade ML security tool, achieving 85-90% accuracy across 20+ test emails. More importantly, I learned that cybersecurity's future is **human analysts empowered by AI**, not replaced by it.

### Skills Developed

**Technical:**
- Python development, virtual environments
- Machine learning: Random Forest, TF-IDF vectorization
- NLP: text preprocessing, tokenization
- Web deployment: Streamlit
- Systematic troubleshooting

**Professional:**
- Independent learning using AI tools
- Persistence through errors
- Technical communication
- Research integration

### What's Next

**Immediate (Final Project):**
- Build my own phishing detector from scratch
- Experiment with different algorithms
- Implement advanced NLP

**Long-term:**
- Contribute to open-source security projects
- Work at companies building security automation at scale

### Try It Yourself

I encourage you to deploy this system. It's free, takes under an hour, and provides hands-on ML security experience. 

**📂 All code, documentation, and resources available at:** [Your GitHub Repository Link]

### Final Thought

Six months ago, "TF-IDF vectorization" and "Random Forest classifiers" sounded impossibly complex. Today, I've used them and explained them to others. That's what education is about—moving from intimidation to understanding.

If you're thinking "I could never do that," you absolutely can. Start with one git clone command. Build from there.

---

## Resources and Links



### 🛠️ Software and Tools
**AI-Powered Phishing Detection System:**  
https://github.com/GauravGhandat-23/AI-Powered-Phishing-Detection-System

**Streamlit:** https://docs.streamlit.io/  
**Scikit-learn:** https://scikit-learn.org/  
**NLTK:** https://www.nltk.org/

### 📄 Research Sources
Tamal, M. A., et al. (2024). Unveiling suspicious phishing attacks. *Frontiers in Computer Science, 6*, 1428013.  
https://doi.org/10.3389/fcomp.2024.1428013

Cloudflare. (2024). How Cloudflare is using automation to tackle phishing.  
https://blog.cloudflare.com/how-cloudflare-is-using-automation-to-tackle-phishing/

### 🤖 AI Tools Used
- GitHub Copilot
- Claude AI

---

**📌 For complete setup instructions, troubleshooting guide, and full source code, visit my GitHub repository:** [Your GitHub Link]

**Total Word Count:** 1,847 words

---

**About the Author:**  
Andrey Carvajal is a cybersecurity student at Bronx Community College, focusing on AI-enhanced threat detection and security automation. This project was completed as part of CSN-190 under Professor Edwin Reed-Sanchez.

**Connect:** [LinkedIn] | [GitHub] | [Email]
