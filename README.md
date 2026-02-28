# Yassine Mouadi

Computer Science Engineering Student | Data Science & Machine Learning

Currently pursuing a Computer Science Engineering degree at ENSA Kénitra after completing a DEUST at the Faculty of Science and Technology. I learn by building systems end to end—understanding the theory, implementing it manually, then refining it into production-quality solutions.

## What I Do

I focus on data science and machine learning with a strong emphasis on fundamentals. Instead of treating models as black boxes, I start by implementing algorithms from scratch to understand the mathematics and assumptions behind them, then transition to established libraries for scalability and reliability.

My technical path started with C to understand memory and low-level behavior, continued with Java for object-oriented design, and now centers on Python and R for data-intensive and machine learning workflows.

My approach is consistent across projects:  
**understand the theory → implement it manually → engineer it properly.**

## Technical Projects

### [Datawise](https://github.com/yassinexng/datawise)

A full-stack, AI-powered data analysis web application designed to automate exploratory data analysis and intelligent data cleaning.

Users can upload CSV, Excel, or PDF datasets and receive automatic EDA, data type inference, missing value detection, and outlier detection using IQR. The system integrates a large language model to generate reliable, executable Pandas-based data cleaning suggestions. Interactive visualizations—including histograms, scatter plots, and correlation heatmaps—are generated dynamically, and cleaned datasets can be downloaded directly.

The backend is built with async FastAPI and SQLAlchemy on SQLite, while the frontend uses Vue 3 and Vite. Authentication includes email verification and password recovery via Brevo SMTP. The project emphasized async Python, frontend routing, and controlling LLM outputs to ensure valid data transformations.

**Stack:**  
Python, FastAPI, Async SQLAlchemy, SQLite, Vue 3, Vite, Pandas, NumPy, ApexCharts, Groq LLM API, Docker

---

### [DocuMind](https://github.com/yassinexng/documind)

A full-stack Retrieval-Augmented Generation (RAG) system enabling semantic search and question answering over personal documents.

Documents are chunked into fixed 500-character windows and embedded into 384-dimensional vectors using sentence-transformers. Embeddings are stored in PostgreSQL with pgvector, enabling efficient cosine similarity search. Retrieved context is used to generate accurate, context-aware responses.

Includes a complete technical report written in LaTeX detailing system architecture, design decisions, and implementation.

**Stack:**  
Python, FastAPI, React, TypeScript, PostgreSQL, pgvector, Docker, Docker Compose, Sentence Transformers, Google Gemini API

---

### [Student Performance Predictor](https://github.com/yassinexng/student-performance-predictor)

A regression pipeline that predicts student GPA based on study habits and behavioral data.

The project began with a custom gradient descent implementation using NumPy to validate the mathematics, then transitioned to scikit-learn for the final model. Includes full data preprocessing, correlation analysis, and visualizations using Matplotlib.

**Stack:**  
Python, NumPy, Pandas, Matplotlib, scikit-learn

---

### [Quantum-Inspired Linear Regression](https://github.com/yassinexng/quantum-inspired-linear-regression)

An experimental Java project exploring quantum-inspired optimization techniques such as superposition and tunneling.

The goal was to investigate whether quantum-inspired heuristics could escape local minima more effectively than classical gradient descent. Designed with a modular OOP architecture supporting interchangeable objective functions and optimization strategies.

**Stack:**  
Java, Object-Oriented Design, Optimization Theory

---

### [Logistic Regression From Scratch](https://github.com/yassinexng/logistic-regression-churn-from-scratch)

A complete implementation of logistic regression without using high-level machine learning libraries.

Built the sigmoid function, maximum likelihood estimation, and gradient descent manually for customer churn prediction. Achieved accuracy comparable to standard library implementations, validating mathematical correctness.

**Stack:**  
Python, NumPy, Mathematical Optimization

---

### [GDG Data Project](https://github.com/yassinexng/data_project_GDG)

Collaborative data analysis project completed with [YounesPRY](https://github.com/YounesPRY).

Provided hands-on experience with collaborative development, version control workflows, merge conflicts, and shared analytical problem-solving.

**Stack:**  
Python, Data Analysis

## Tech I Use

**Languages:**  
Python, Java, C, R, SQL / PL-SQL

**Data Science & Machine Learning:**  
NumPy, Pandas, Matplotlib, scikit-learn, Streamlit, Gradient Descent, Maximum Likelihood Estimation, Embeddings, Vector Search, RAG

**Web & Full-Stack:**  
FastAPI, Async SQLAlchemy, React, Vue 3, TypeScript, Vite, PostgreSQL, pgvector, SQLite

**DevOps & Tools:**  
Docker, Docker Compose, Git/GitHub, Linux, VS Code, Jupyter Notebooks

I choose tools based on technical suitability rather than trends.

Fluent in Arabic, French, and English—useful for reading research, technical documentation, and collaborating in international environments.

## Contact

- Email: [yassine.mouadi.bns@gmail.com](mailto:yassine.mouadi.bns@gmail.com)
- LinkedIn: [linkedin.com/in/yassine-m-297a71276](https://www.linkedin.com/in/yassine-m-297a71276/)
- GitHub: [github.com/yassinexng](https://github.com/yassinexng)

Open to discussions around data pipelines, algorithm design, and technically interesting problems.
