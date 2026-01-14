---
layout: single
title: "Work Samples"
permalink: /samples/
toc: true
toc_label: "Sample Categories"
toc_icon: "code"

---

This page contains selected projects and deliverables that demonstrate my technical capabilities across machine learning, full-stack development, data visualization, and educational AI. Many repositories are private to protect proprietary work and sensitive data—access can be provided to hiring managers and recruiters upon request.

---

## Fuel Inventory Management & Optimization Analysis
**Source:** Johns Hopkins University - Python for Data Analytics (Team Project)  
**Technical Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Statistical Analysis

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Description:**  
Collaborated with a team to analyze fuel inventory behavior and refill patterns across multiple gas station locations over a 2.5-year period (January 2017 - August 2019). Performed comprehensive data cleaning, merging five disparate datasets, and conducted statistical analysis to identify operational inefficiencies and cost-saving opportunities. Incorporated inflation-adjusted analysis to account for purchasing power erosion over time.

**Sample Materials:**
Private GitHub repository(https://github.com/PranavDesurkar/Data_Analytics_Projects_Samples) that contains the following files :
-   [Project Report](annotated-Project_20Report.pdf) - Full analysis with visualizations and recommendations
-   [Jupyter Notebook](finalprojects__2_.ipynb) - Complete Python analysis code

**Key Features:**
- Multi-dataset integration and standardization (5 CSV files merged)
- Time-series analysis of fuel levels, utilization rates, and refill patterns
- Discount efficiency calculations and missed savings quantification
- Inflation-adjusted financial analysis using Canadian CPI data
- Correlation analysis exploring variability vs. ordering behavior
- Station-by-station operational efficiency comparison

**Business Impact:**
- Identified $157,549.75 in unrealized savings (78.43% of potential discounts)
- Discovered optimal ordering patterns: Tuesday deliveries showed highest average order sizes
- Quantified inventory risk levels: 3 stations operating below 15% utilization (high outage risk)
- Demonstrated that reactive ordering (high variability) achieved 5x better discount efficiency than proactive ordering
- Provided actionable recommendations for consolidating purchases and optimizing delivery schedules

**Technical Implementation:**
- **Data Cleaning**: Merged and standardized 5 datasets, handled missing values, converted data types, created datetime features
- **Feature Engineering**: Calculated utilization rates (fuel level/tank capacity), discount tiers, missed savings, inflation adjustments
- **Statistical Analysis**: Correlation analysis (Pearson r), variability metrics (σ/μ), time-based aggregations
- **Visualization**: Multi-panel charts comparing station performance across metrics (utilization, savings, order patterns)
- **Economic Modeling**: Incorporated monthly inflation rates to adjust financial metrics for real purchasing power

**Analytical Findings:**
- Most stations operated at 20-35% tank utilization (lower than optimal)
- Strong positive correlation (r=0.727) between order variability and frequency
- Strong positive correlation (r=0.620) between variability and discount efficiency (contradicted initial hypothesis)
- Stations with high variability achieved 17.19% discount efficiency vs. 3.57% for low variability

**My Contributions:**
- Led data cleaning and standardization across five datasets
- Developed inflation adjustment methodology and integrated Canadian CPI data
- Conducted variability analysis exploring reactive vs. proactive ordering patterns
- Co-authored findings section analyzing discount efficiency and operational recommendations

**Skills Demonstrated:** Python data analysis, Pandas data manipulation, statistical analysis, time-series analysis, data visualization, business analytics, inflation adjustment, team collaboration, technical writing

</details>

---

## NBA Statistics Interactive Dashboard
**Source:** Johns Hopkins University - Data Visualization Course  
**Technical Stack:** Tableau, Data Cleaning, Data Blending, Interactive Visualizations

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Sample Materials:**
- [Live Tableau Dashboard](https://public.tableau.com/app/profile/pranav.desurkar/viz/NBAStatisticsDashboard/MAINDASHBOARD?publish=yes) - Fully interactive public dashboard
- Project documentation - Available upon request

**Description:**  
Designed and built an interactive NBA statistics dashboard to enable exploratory analysis of player performance metrics, team statistics, and league-wide trends. The dashboard provides dynamic filtering capabilities and multiple visualization types to support data-driven insights into basketball analytics.

**Key Features:**
- Interactive multi-page dashboard with drill-down capabilities
- Dynamic filtering across multiple dimensions (teams, players, seasons)
- Comprehensive data cleaning and preparation pipeline
- Data blending from multiple NBA statistical sources
- Custom calculations and aggregations for advanced metrics
- Responsive design optimized for user exploration

**Technical Implementation:**
- Data preparation: Cleaned and standardized raw NBA statistical data
- Database normalization: Structured player, team, and game data for efficient querying
- Data blending: Integrated multiple data sources to create unified view
- Interactive features: Implemented parameter controls, filters, and actions
- Visual design: Applied data visualization best practices for clarity and impact

**Analytics Insights:**
- Player performance comparisons across seasons and teams
- Team-level statistical trends and patterns
- League-wide distribution analysis of key metrics

**Skills Demonstrated:** Data cleaning, Tableau development, interactive dashboard design, data blending, statistical visualization, sports analytics

</details>

---
## Dataset Augmentation for Skin of Color Diagnostics
**Source:** Barger Leadership Institute Research Project  
**Technical Stack:** Python, Machine Learning, Computer Vision, ResNet, Dataset Curation

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Sample Materials:**
- [Research Poster PDF](/assets/files/SOC_poster.pdf) - Full research Poster

**Description:**  
Developed dataset augmentation techniques to address racial bias in dermatological machine learning models. Created a representative training dataset with 50% Skin of Color images across the Fitzpatrick scale (F1-F7) to improve eczema classification accuracy for underrepresented skin tones.

**Key Features:**
- Assembled representative dataset balancing Fitzpatrick skin types F1-F7
- Implemented bias mitigation techniques through strategic data augmentation
- Trained ResNet model achieving 85% accuracy on SoC vs 67% for standard models
- Conducted stakeholder research with medical professionals to inform approach

**Research Impact:**
- 10% improvement over traditional models on select metrics
- Significantly improved AUROC scores for SoC classification (0.92 vs 0.50)
- Demonstrated viability of dataset augmentation for healthcare equity

</details>

---

## CodeFairy - AI-Powered Dynamic Programming Tutor
**Source:** University of Michigan - EECS 498: AI in Education (Team Project)  
**Technical Stack:** Python, Flask/Django, JavaScript, SQLite, OpenAI API, ASGI

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Description:**  
Collaboratively developed an intelligent tutoring system that teaches students to solve LeetCode-style Dynamic Programming problems through AI-powered personalized feedback. The system mimics an Online Assessment environment while providing contextualized hints generated by comparing student solutions against expert thought processes using LLM integration.

**Sample Materials:**
- [Private GitHub Repository](https://github.com/PranavDesurkar/aiineducationsamples) - codebase including backend, frontend, and AI integration, along with technical documentation and associated reports.

**Access Instructions:**  
This is a private repository. To request access for portfolio review, please contact me via email at **pdesurka@umich.edu** with "Repository Access Request" in the subject line. I will work to make sure access is granted as soon as possible. Make sure to include your Github account username or associated email. 


**Key Features:**
- Full-stack web application with code editor, test runner, and feedback system
- AI-powered feedback engine that contextualizes LLM with expert solutions and student code
- Model tracing implementation for real-time error detection
- Dual feedback architecture: static test results and AI-generated conceptual guidance
- Dynamic programming problem library with multi-step solution validation

**Technical Implementation:**
- Backend architecture using Python (Flask/Django) with ASGI server
- SQLite database for problem storage and user progress tracking
- OpenAI API integration for generating personalized learning feedback
- Sandboxed code execution environment for running student solutions
- Frontend interface designed to replicate LeetCode coding environment

**Educational Impact:**
- Teaches recursive solution structuring, memoization techniques, and base case formulation
- Implements cognitive tutoring principles: scaffolded hints, immediate feedback, and model tracing
- Demonstrated how AI can scale personalized technical education

**My Contributions:**
I specifically led congitve task analysis interviews with potential users. Coded, debugged and tested the frontend and portions of the backend of this application. 


**Skills Demonstrated:** Full-stack development, AI integration, educational technology, intelligent tutoring systems, Flask/Django, LLM prompt engineering, team collaboration, API development, model tracing

</details>

---

## Sentiment Analysis with SVMs - Amazon Movie Reviews {#eecs445-svm}
**Source:** University of Michigan - EECS 445: Machine Learning  
**Technical Stack:** Python, scikit-learn, NumPy, pandas, Matplotlib, Word2Vec

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Description:**  
Implemented Support Vector Machine classifiers for binary sentiment analysis of Amazon movie reviews, achieving 96.6% AUROC. Explored advanced ML concepts including regularization strategies, class imbalance handling, kernel methods, and algorithmic bias detection.

**Sample Materials:**
- [Private GitHub Repository](https://github.com/PranavDesurkar/ML_Coursework_Sample) - Complete implementation with feature engineering, SVM training, bias analysis, and Detailed analysi report with visualizations. Please reach out for access to github repo.

**Technical Implementation:**
- **Feature Engineering**: Bag-of-words representation with 5,874-word dictionary, sparse feature vectors
- **SVM Optimization**: Cross-validated hyperparameter tuning across C ∈ {10⁻³, 10⁻², 10⁻¹, 10⁰} using multiple metrics (accuracy, F1, AUROC, precision, sensitivity, specificity)
- **Regularization Analysis**: Compared L1 vs. L2 penalties, analyzed L0-norm sparsity patterns
- **Kernel Comparison**: Implemented linear and quadratic kernels with grid search and random search tuning
- **Class Imbalance**: Designed weighted SVM achieving 100% sensitivity while managing specificity tradeoffs

**Key Results:**
- Linear SVM (C=0.1): 91.5% test accuracy, 96.6% AUROC, 91.6% F1-score
- Identified 5 most positive coefficients: "love," "loves," "great," "excellent," "perfect"
- Detected gender bias: "actor" appeared 4.9× more than "actress" in reviews
- Word embeddings showed "talented" associated more strongly with male-gendered attributes

**Advanced Analysis:**
- Bias Detection: Quantified implicit gender bias through word frequency analysis and embedding associations
- Model Interpretability: Analyzed coefficient weights to understand learned word-sentiment relationships
- Challenge Component: Developed custom classifier using N-grams and TF-IDF vectorization


</details>

---

## Image Classification with CNNs - Landmark Recognition {#eecs445-cnn}
**Source:** University of Michigan - EECS 445: Machine Learning  
**Technical Stack:** Python, PyTorch, NumPy, Matplotlib, Grad-CAM

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Description:**  
Designed and optimized Convolutional Neural Networks for landmark image classification (Pantheon vs. Hofburg Imperial Palace), achieving 88.07% test AUROC through systematic experimentation. Implemented transfer learning, custom data augmentation strategies, and Grad-CAM visualization for model interpretability.

**Sample Materials:**
- [Private GitHub Repository](https://github.com/PranavDesurkar/ML_Coursework_Sample) - Complete implementation with feature engineering, SVM training, bias analysis, and Detailed analysi report with visualizations. Please reach out for access to github repo.


**Technical Architecture:**
- **Base CNN**: 3 convolutional layers (filter progression: 16→64→8), 39,754 parameters
- **Custom Preprocessing**: Channel-wise normalization preventing data leakage
- **Training Strategy**: Early stopping (patience=10), Adam optimizer, cross-entropy loss

**Key Implementations:**

**1. Transfer Learning Pipeline**
- Pre-trained 8-class source model achieving 96% validation accuracy
- Systematically evaluated layer freezing strategies across all combinations
- Best configuration: freeze first 2 conv layers (88.62% test AUROC, +19% over baseline)
- Generated confusion matrices identifying Rialto Bridge as most distinctive landmark

**2. Data Augmentation**
- Implemented custom "Grotate" method combining rotation + grayscale conversion
- Reduced train-val gap from 2.38% to 2.31% while improving test AUROC 15.65%
- Tested augmentation combinations: rotation-only, grayscale-only, combined
- Analyzed impact of keeping vs. discarding original images

**3. Model Interpretability (Grad-CAM)**
- Calculated gradient-weighted activations: L = ReLU(Σ αₖAₖ)
- Visualized decision-making process for each class
- Discovered model focused on color patterns (blue/green hues) rather than architectural features
- Identified potential overfitting to irrelevant features (clothing colors, sky)

**4. Systematic Optimization**
- **Batch Size**: Tested {4, 8, 16, 32, 64, 128}, optimal = 32
- **Weight Decay**: Tested {0.001, 0.01, 0.1}, optimal = 0.01  
- **Architecture Depth**: Compared 8 vs. 64 final conv filters, analyzed parameter-performance tradeoff
- **Early Stopping**: Patience 5 vs. 10, selected 10 for validation stability

**Optimization Results:**

| Method | Test AUROC | Improvement |
|--------|-----------|-------------|
| Baseline | 69.20% | - |
| Transfer Learning | 88.62% | +19.42% |
| Data Augmentation | 84.85% | +15.65% |
| **Combined Optimal** | **88.07%** | **+18.87%** |

**Key Findings:**
- Transfer learning most effective with partial freezing (2 layers) vs. full freezing or fine-tuning
- Custom Grotate augmentation outperformed single-method augmentation
- Grad-CAM revealed model vulnerability to color-based shortcuts
- Weight decay (0.01) reduced overfitting without sacrificing training performance
  
</details>

---

## Open Source Contribution - Case-Sensitive URL Bug Fix
**Source:** University of Michigan - EECS 481: Software Engineering (Team Project)  
**Technical Stack:** C++, Qt Framework, CMake, GitHub Actions CI/CD  
**Team Size:** 2 (Partner: Sunidhi Majalikar)

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Description:**  
Fixed a 10-year-old bug in Mumble, an open-source voice chat platform, where channel URLs incorrectly performed case-insensitive matching. Channels with similar names but different capitalization (e.g., "EECS481" vs "eecs481") were treated as identical when accessed via URLs, causing incorrect navigation.

**My Contribution:**  
Complete ownership of bug fix including fault localization, implementation, unit testing, and pull request management. My partner handled a separate feature addition task.

**Technical Solution:**
- Analyzed 3000+ line `MainWindow.cpp` file to locate bug in `findDesiredChannel()` function
- Removed `.toLower()` operations causing case-insensitive comparison (2-3 line fix)
- Designed comprehensive unit test suite (`TestChannelURLCase.cpp`) with parameterized tests and mock objects
- Implemented fallback case-insensitive search based on maintainer feedback
- Successfully passed all CI/CD pipeline checks (build verification, style checks, unit tests)

**Impact:**  
Resolved decade-old navigation bug affecting global user base. Contribution successfully merged into production codebase.

**Key Learning:**  
Quality assurance required 3x more time than implementation (15 hours testing vs. 5 hours coding), demonstrating importance of comprehensive testing in production systems.

**Sample Materials:**
- [GitHub Repository](https://github.com/PranavDesurkar/481-Open-Source-Project) - Complete code including bug fix and unit tests
- [Merged Pull Request](link-to-actual-PR) - Code review history and CI/CD verification
- [Project Report](/assets/files/481_HW_6B.pdf) - Detailed documentation of contribution process

**Skills Demonstrated:** C++ development, unit testing, open source workflows, Git/GitHub, code review, CI/CD pipelines, fault localization, legacy code maintenance

</details>

---

## Rule-Based Cognitive Tutor - Mental Math Problem Solver
**Source:** University of Michigan - EECS 498: AI in Education  
**Technical Stack:** JavaScript, Nools, CTAT (Cognitive Tutor Authoring Tools)

<details markdown="1">
<summary><strong>Click to expand details</strong></summary>

**Description:**  
Developed a rule-based cognitive tutor using CTAT that teaches students a mental math technique for squaring numbers ending in 5. Implemented production rules, multi-level hints, and bug detection to provide intelligent, adaptive guidance through the problem-solving process.

**Sample Materials:**
- [Private GitHub Repository](https://github.com/PranavDesurkar/aiineducationsamples) - codebase including backend, frontend, and AI integration, along with technical documentation and associated reports.

**Access Instructions:**  
This is a private repository. To request access for portfolio review, please contact me via email at **pdesurka@umich.edu** with "Repository Access Request" in the subject line. I will work to make sure access is granted as soon as possible. Make sure to include your Github account username or associated email. 

**Key Features:**
- Production rule system for step-by-step problem validation
- Multi-level progressive hint architecture that maintains productive struggle
- Bug rule detection identifying common student misconceptions
- Multiple test cases with varying digit lengths to validate rule implementation

**Technical Implementation:**
- Rule-based programming using Nools language
- Knowledge representation through production rules
- Cognitive task analysis to decompose problem-solving steps
- Interactive HTML/JavaScript interface integrated with CTAT system

**Pedagogical Approach:**
- First hint encourages self-discovery with general guidance
- Progressive hints become increasingly specific while preserving learning
- Bug rules provide targeted feedback on specific misconceptions (e.g., digit isolation errors)


**Skills Demonstrated:** Rule-based systems, cognitive tutor development, Nools programming, knowledge representation, educational AI, pedagogical design, CTAT platform

</details>

---

