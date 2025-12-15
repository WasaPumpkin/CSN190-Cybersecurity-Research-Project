# AI-Powered Phishing Detection System

**Author:** Andrey Carvajal  
**EMPLID:** 24521104  
**Course:** CSN-190 - Cybersecurity Research  
**Professor:** Edwin Reed-Sanchez  
**Semester:** Fall 2025  
**Institution:** Bronx Community College

---

## 📊 Project Overview

This repository documents my semester-long research project developing and deploying an AI-powered phishing detection system using machine learning and natural language processing. The project combines academic research, hands-on implementation, and technical documentation to demonstrate how artificial intelligence can enhance cybersecurity defenses against phishing attacks—the leading cause of data breaches affecting 90% of organizations.

## 🛠️ Software/Tools Used

**Core Technologies:**
- **Python 3.12.6** - Primary programming language
- **scikit-learn 1.7.2** - Machine learning algorithms (Random Forest, SVM, Naive Bayes)
- **Streamlit 1.51.0** - Web application framework
- **NLTK 3.9.2** - Natural language processing
- **pandas 2.3.3** - Data manipulation
- **Git/GitHub** - Version control and documentation

**Development Environment:**
- Visual Studio Code with GitHub Copilot
- Python virtual environments
- Jupyter Notebook for experimentation

**AI Assistance Tools:**
- GitHub Copilot - Code assistance and debugging
- Claude AI - Research and documentation support

## 🎯 Key Deliverables

- 📝 [Published Medium Article: "From Clone to Detection"](https://medium.com/@andycarsan10/74ea8323b19e) - Comprehensive deployment tutorial
- 📖 [Setup and Deployment Guide](./docs/SETUP-GUIDE.md) - Step-by-step installation instructions
- 🔬 [Research Analysis](./research-notes/) - Academic and industry research integration
- 📊 [Complete Resource Bibliography](./resources/Full-List-of-Resources.md) - All sources cited
- 💻 [Deployed Project](./src/AI-Powered-Phishing-Detection-System/) - Working ML phishing detector

## 📂 Repository Navigation

| Folder | Description |
|--------|-------------|
| **`/weekly-progress/`** | All weekly assignments and progress updates (Modules 1-6) |
| **`/research-notes/`** | Topic analysis, resource reviews, feasibility assessments, abstracts |
| **`/resources/`** | Complete bibliography of academic papers, tutorials, and documentation |
| **`/src/`** | Source code for AI phishing detection system |
| **`/docs/`** | Technical documentation, setup guides, and tutorials |
| **`/final-paper/`** | Medium article, research papers, and abstracts |
| **`/presentation/`** | Final presentation materials |
| **`/images/`** | Screenshots, diagrams, and visual documentation |

## 🚀 Getting Started

To replicate this phishing detection system on your machine:

### Prerequisites
- Python 3.9 or higher
- Git installed
- 4GB RAM minimum
- Windows, macOS, or Linux

### Quick Setup (5 Steps)

1. **Clone this repository:**
```bash
   git clone https://github.com/yourusername/yourrepo
   cd yourrepo
```

2. **Navigate to the project:**
```bash
   cd src/AI-Powered-Phishing-Detection-System
```

3. **Create virtual environment:**
```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate     # Windows
```

4. **Install dependencies:**
```bash
   pip install -r requirements.txt
```

5. **Launch application:**
```bash
   streamlit run phishing_detection.py
```

**Detailed instructions:** See [Setup Guide](./docs/SETUP-GUIDE.md)

## 📈 Results Summary

### What I Accomplished

Successfully deployed and analyzed a production-grade machine learning phishing detection system, achieving:

- **85-90% classification accuracy** across 20+ test emails (legitimate and phishing)
- **Real-time detection** (0.3-0.8 seconds per email analysis)
- **Comprehensive research validation** against academic benchmarks (97.52% accuracy in peer-reviewed studies) and industry implementation (Cloudflare's automation approach)
- **Complete documentation** from installation through testing and analysis

### Key Learning Outcomes

**Technical Skills Developed:**
- Machine learning implementation (Random Forest, TF-IDF vectorization, feature engineering)
- Natural language processing for text classification
- Python development with virtual environments and package management
- Web application deployment using Streamlit
- Systematic troubleshooting and debugging

**Cybersecurity Insights:**
- Understanding how ML-based threat detection works at scale
- Recognizing the trade-offs between false positives and false negatives
- Appreciating the "human-in-the-loop" approach where AI augments rather than replaces analysts
- Connecting academic research with real-world industry implementation

**Professional Development:**
- Technical writing and documentation for diverse audiences
- Using AI tools (GitHub Copilot, Claude) effectively for learning and problem-solving
- Building a professional portfolio with version control best practices
- Integrating theoretical knowledge with hands-on practical experience

### Research Findings

My analysis validated that:
1. **Random Forest is optimal** for phishing detection (97.52% accuracy in academic studies, 85-90% in my implementation)
2. **Feature engineering matters** as much as algorithm selection—combining URL analysis, text patterns, and linguistic features improves detection
3. **ML automation is viable** but not perfect—Cloudflare achieves 78% automation, requiring human judgment for ambiguous cases
4. **Continuous learning is essential**—phishing tactics evolve, requiring regular model updates

This project demonstrates that student-level implementations can achieve professional-quality results when combining proper research, systematic development, and thorough testing.

## 🎓 Academic Context

This project was completed as part of CSN-190 (Cybersecurity Research) at Bronx Community College, under the guidance of Professor Edwin Reed-Sanchez. The work integrates:

- Academic research from peer-reviewed journals (*Frontiers in Computer Science*)
- Industry case studies (Cloudflare's enterprise phishing automation)
- Open-source community contributions (GitHub projects)
- Hands-on technical implementation and testing

The project aligns with my career goal of working in cybersecurity, particularly in roles involving AI-enhanced threat detection and security automation.

## 📞 Contact

**Andrey Carvajal**  
- 📧 Email: andycarsan10@gmail.com  
- 📝 Medium: [@andycarsan10](https://medium.com/@andycarsan10)  


---

**Last Updated:** December 2025  
**License:** MIT (for original work) | See individual projects for their licenses  
**Acknowledgments:** Professor Edwin Reed-Sanchez, GauravGhandat-23 (original phishing detection system), Bronx Community College CSN-190 class
