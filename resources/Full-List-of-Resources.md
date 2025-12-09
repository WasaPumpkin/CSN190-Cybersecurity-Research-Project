# Complete Resource List - CSN-190 Phishing Detection Project

**Student:** Andrey Carvajal  
**Course:** CSN-190  
**Semester:** Fall 2025

---

## Academic Papers

### 1. Optimal Feature Vectorization for Phishing Detection
**Citation:** Tamal, M. A., Islam, M. K., Bhuiyan, T., Sattar, A., & Prince, N. U. (2024). Unveiling suspicious phishing attacks: Enhancing detection with an optimal feature vectorization algorithm and supervised machine learning. *Frontiers in Computer Science, 6*, 1428013.

**Link:** https://doi.org/10.3389/fcomp.2024.1428013

**Type:** Peer-reviewed academic research paper

**Summary:** Comprehensive study testing ML-based phishing detection on 274,446 URLs. Developed Optimal Feature Vectorization Algorithm (OFVA) achieving 97.52% accuracy with Random Forest. Identified 10 novel URL characteristics including domain age, HTTPS presence, and special character frequency.

**Used in:** Module 3 (Deep Dive Resource Analysis), Module 7 (Medium Article Research Section)

**Key Takeaway:** Validates Random Forest as optimal algorithm for phishing detection and emphasizes importance of feature engineering—which features you extract matters as much as which algorithm you use.

---

### 2. Machine Learning and Neural Networks for Phishing Detection: Systematic Review
**Citation:** Kumar, S., Singh, A., & Chen, L. (2024). Machine learning and neural networks for phishing detection: A systematic review (2017-2024). *Electronics, 14*(18), 3744.

**Link:** https://doi.org/10.3390/electronics14183744

**Type:** Systematic literature review

**Summary:** Reviewed 105 scientific studies from 2017-2024 covering phishing detection approaches. Research distribution: Websites (58%), Email (22%), Malware (25%), Social Media (8%). Identified gaps in reproducibility and real-world testing.

**Used in:** Module 3 (Deep Dive Resource Analysis)

**Key Takeaway:** Comprehensive overview of current ML approaches in phishing detection and identification of research gaps that my project could address.

---

## Industry Reports and White Papers

### 3. Cloudflare Phishing Automation Case Study
**Citation:** Cloudflare. (2024). How Cloudflare is using automation to tackle phishing head on. *Cloudflare Blog*.

**Link:** https://blog.cloudflare.com/how-cloudflare-is-using-automation-to-tackle-phishing/

**Type:** Industry white paper / case study

**Summary:** Details Cloudflare's journey automating phishing response at enterprise scale. Improved automation from 37% to 78%, reduced response time from 3.4 days to under 1 hour. Emphasizes ML classifiers combined with threat intelligence and human-in-the-loop approach.

**Used in:** Module 3 (Deep Dive Resource Analysis), Module 7 (Medium Article Research Section)

**Key Takeaway:** Demonstrates real-world deployment challenges and scalability solutions at massive scale (thousands of emails per second). Shows that even advanced ML requires human judgment for edge cases.

---

## GitHub Projects and Code Repositories

### 4. AI-Powered Phishing Detection System (GauravGhandat-23)
**Repository:** https://github.com/GauravGhandat-23/AI-Powered-Phishing-Detection-System

**Type:** Open-source implementation

**Summary:** Complete ML system for phishing email detection using NLP and URL analysis. Features multiple algorithms (SVM, Random Forest, Naive Bayes), email preprocessing, and web-based Streamlit interface. Pre-trained model included.

**Used in:** Module 3 (GitHub Project Research), Module 6 (Deployment Assignment), Module 7 (Medium Article)

**Key Takeaway:** Served as primary hands-on project for deployment, testing, and analysis. Demonstrates production-ready implementation of academic concepts.

---

### 5. Phishing Detection with AI (Johristein)
**Repository:** https://github.com/Johristein/phishing-detection-with-ai

**Type:** Educational framework

**Summary:** Advanced AI system combining traditional ML with deep learning for phishing detection. Uses TF-IDF vectorization and hybrid neural networks. Clean code structure with detailed explanations.

**Used in:** Module 3 (GitHub Project Research)

**Key Takeaway:** Demonstrates hybrid approach combining traditional ML with deep learning techniques, valuable for understanding advanced AI applications in phishing detection.

---

### 6. DRAKVUF Sandbox
**Repository:** https://github.com/CERT-Polska/drakvuf-sandbox  
**Documentation:** https://drakvuf-sandbox.readthedocs.io/

**Type:** Professional security tool

**Summary:** Enterprise-grade automated hypervisor-level malware analysis system. Features web interface, comprehensive reporting, guided installation. Maintained by Poland's CERT with 900+ stars.

**Used in:** Module 3 (GitHub Project Research - comparison topic)

**Key Takeaway:** Professional-grade implementation showing enterprise-level security tool architecture, used for comparison against phishing detection approaches.

---

### 7. Cuckoo Sandbox
**Repository:** https://github.com/cuckoosandbox/cuckoo  
**Documentation:** https://cuckoo.readthedocs.io/

**Type:** Open-source security framework

**Summary:** Leading open-source automated malware analysis system with 5.5k+ stars. Supports multiple virtualization platforms, extensible reporting, RESTful API. Comprehensive behavioral analysis capabilities.

**Used in:** Module 3 (GitHub Project Research - comparison topic)

**Key Takeaway:** Industry standard reference implementation for understanding comprehensive malware analysis, used as comparison for project complexity assessment.

---

## Technical Documentation

### 8. Streamlit Official Documentation
**Link:** https://docs.streamlit.io/

**Summary:** Complete documentation for Streamlit web framework used to create the phishing detection interface. Consulted for understanding app.py structure, layout options, and deployment.

**Used in:** Module 6 (Deployment), Module 7 (Medium Article)

---

### 9. scikit-learn Machine Learning Library
**Link:** https://scikit-learn.org/stable/

**Summary:** Official documentation for scikit-learn, the primary ML library used in the project. Consulted for understanding Random Forest, TF-IDF vectorization, and model evaluation metrics.

**Used in:** Throughout project for understanding ML implementation

---

### 10. NLTK (Natural Language Toolkit)
**Link:** https://www.nltk.org/

**Summary:** Natural language processing library documentation. Used for understanding text preprocessing, tokenization, and stopword removal.

**Used in:** Module 6 (Deployment), Module 7 (Medium Article)

---

## Videos and Tutorials

### 11. BERT-Based Phishing Detection Tutorial
**Title:** Detect AI-Generated Phishing Emails with BERT | Full Project Tutorial

**Link:** https://www.youtube.com/watch?v=AT857mWvl0g

**Creator:** [Channel Name]

**Summary:** Complete BERT implementation for AI-generated phishing detection. Covers dataset preprocessing, tokenization, fine-tuning, and performance evaluation.

**Used in:** Module 3 (Deep Dive Resource Analysis)

**What I learned:** Advanced transformer technology application in phishing detection, context-aware capabilities of BERT models.

---

### 12. ANY.RUN Sandbox Creation Tutorial
**Title:** How to create a sandbox environment for malware analysis

**Link:** https://any.run/cybersecurity-blog/how-to-create-a-sandbox/

**Creator:** ANY.RUN Cybersecurity Team

**Summary:** Step-by-step sandbox creation using open-source tools. VMware/VirtualBox configuration, network isolation setup, legal/ethical considerations.

**Used in:** Module 3 (Deep Dive Resource Analysis - comparison topic)

---

## Learning Resources and Communities

### 13. GitHub Copilot
**Tool:** AI pair programmer

**How used:** Code troubleshooting, debugging assistance, explaining error messages, suggesting solutions for installation issues.

**Impact:** Significantly accelerated learning by providing context-aware help exactly when needed. Particularly helpful for the "requirements.txt not found" error during deployment.

---

### 14. Claude AI (Anthropic)
**Tool:** AI research and writing assistant

**How used:** Research paper analysis, documentation generation, technical concept explanations, assignment structuring.

**Impact:** Helped synthesize complex academic papers, organize thoughts coherently, and maintain consistent documentation quality.

---

### 15. Stack Overflow - Machine Learning Tag
**Link:** https://stackoverflow.com/questions/tagged/machine-learning

**Usage:** Consulted for troubleshooting Python virtual environment activation issues and understanding scikit-learn parameters.

---

### 16. Reddit - r/MachineLearning
**Link:** https://www.reddit.com/r/MachineLearning/

**Usage:** Explored discussions about phishing detection approaches and ML best practices for security applications.

---

### 17. Reddit - r/cybersecurity
**Link:** https://www.reddit.com/r/cybersecurity/

**Usage:** Researched current phishing trends, attack techniques, and industry perspectives on automated threat detection.

---

## Course Materials

### 18. CSN-190 Course Assignments
**Instructor:** Professor Edwin Reed-Sanchez

**Materials:**
- Module 1: Topic exploration and selection
- Module 2: Initial research and resource gathering
- Module 3: Deep dive analysis and GitHub project review
- Module 4: Feasibility assessment and final topic decision
- Module 5: Abstract drafting
- Module 6: Hands-on deployment and setup documentation
- Module 7: Medium article creation
- Module 8: Repository organization

---

## Datasets

### 19. Kaggle - Phishing Site URLs Dataset
**Link:** https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls

**Description:** Large dataset of phishing and legitimate URLs with labeled examples. Referenced for understanding available training data sources.

**Used in:** Research planning for future custom model development

---

### 20. UCI Machine Learning Repository - Phishing Websites
**Link:** https://archive.ics.uci.edu/ml/datasets/phishing+websites

**Description:** Classic phishing detection dataset with URL features. Cited in multiple academic papers reviewed during research.

**Used in:** Module 4 (Feasibility Assessment), research background

---

## Additional Reference Materials

### 21. Verizon Data Breach Investigations Report (2024)
**General reference:** Industry statistics on phishing as primary attack vector (90% of breaches involve phishing)

**Used in:** Module 7 (Medium Article introduction), establishing problem significance

---

### 22. Medium Example Articles
**Cybersecurity Educational Articles:**
- https://cybersum.medium.com/a-helping-hand-for-absolute-beginners-in-cybersecurity-0e708ffe047f
- https://medium.com/devsecops-ai/12-free-network-security-tools-better-than-costly-software-7be2f5bc2ba9
- https://software-sinner.medium.com/how-to-tunnel-and-pivot-networks-using-ligolo-ng-cf828e59e740

**Usage:** Studied for understanding effective technical writing style, structure, and engagement techniques for Medium platform.

**Used in:** Module 7 (Medium Article planning and drafting)

---

## Resource Summary Statistics

**Total Resources:** 22+  
**Academic Papers:** 2  
**Industry Reports:** 1  
**GitHub Projects:** 4  
**Technical Documentation:** 3  
**Video Tutorials:** 2  
**AI Tools:** 2  
**Community Resources:** 4  
**Datasets:** 2  
**Example Articles:** 2+

---

**Compiled by:** Andrey Carvajal  
**Last Updated:** November 9, 2025  
**Purpose:** Complete bibliography for CSN-190 phishing detection project
