# Bridging the Gap: Industry-Driven Data Science Curriculum Design

## Context
With the explosive growth of the data science field, understanding industry needs has become essential for designing relevant academic curriculums. Employers demand a blend of technical, analytical, and interpersonal skills, but existing educational programs often fail to address these dynamic requirements comprehensively. This project tackles this challenge by analyzing real-world job postings to identify critical skills and using clustering techniques to design an actionable and industry-aligned curriculum.

## Problem Statement
**How can we design a data science curriculum that aligns with the ever-evolving demands of the job market while providing students with a clear and logical pathway for skill acquisition?**

## Objective
This project focuses on analyzing job postings for data-related roles to identify high-demand skills, group them into meaningful clusters, and create a structured, industry-relevant curriculum for aspiring data professionals.

## Methodology

### 1. Job Posting Analysis
- **Data Collection**: Scraped 1,276 job postings from Canadian and remote locations, exceeding the target of 800. Anti-bot measures were handled using custom scripts.
- **Preprocessing**: Removed duplicates, standardized text, and prepared a clean dataset for analysis.

### 2. Skill Extraction
- Combined all job descriptions into a single corpus and utilized `CountVectorizer` to extract unigrams and bigrams.
- Enhanced the skill list using AI-powered validation via ChatGPT, ensuring relevance and eliminating noise.

### 3. Clustering
- **Hierarchical Clustering**: Used cosine similarity and centroid linkage to form distinct skill clusters.
- **K-Means Clustering**: Applied the Elbow Method to identify optimal cluster numbers and validate groupings.
- **Comparison**: Evaluated the practicality of hierarchical vs. K-means clustering in curriculum design, balancing granularity and coherence.

### 4. Curriculum Design
- Developed a 10-course curriculum based on skill clusters, ensuring logical flow and minimizing redundancy.
- Prioritized industry relevance with foundational programming, advanced machine learning, big data tools, and business intelligence skills.

## Deliverables

### Visual Insights
- **Skill Frequency Bar Chart**: Highlights the most in-demand skills like Python, SQL, and Tableau.
- **Co-occurrence Heatmap**: Reveals relationships between top skills, aiding curriculum design.
- **Clustering Visualizations**: Dendrograms and PCA scatterplots demonstrate skill groupings.
- **Location Trends**: Bar charts show demand by region, emphasizing the dominance of Toronto and remote roles.

### Final Curriculum
The 10-course curriculum provides a structured learning journey, including:
1. **Programming Foundations**: Python, R, SQL, and Pandas.
2. **Data Visualization**: Tableau, Power BI, and advanced libraries.
3. **Machine Learning & AI**: TensorFlow, PyTorch, and Scikit-learn.
4. **Big Data & Cloud**: Hadoop, Spark, and AWS.
5. **Soft Skills and Ethics**: Teamwork, critical thinking, and data governance.

## Tools & Technologies
- **Programming**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Clustering**: Hierarchical Clustering, K-Means
- **Skill Validation**: ChatGPT API

## Outcomes
This project serves as a guide for curriculum developers, job seekers, and educators, addressing the disconnect between academic preparation and industry expectations. It creates a comprehensive blueprint for data science education that balances technical, analytical, and interpersonal skills.
