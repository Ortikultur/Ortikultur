# AI Coding Agent Instructions for Ortikultur

## Project Overview
Ortikultur is a personal portfolio and learning repository focusing on **Data Analytics, Machine Learning, and Python development**. This is a multi-disciplinary project exploring ML applications, unsupervised learning, and neural networks.

## Tech Stack & Languages
- **Primary:** Python, SQL, Dart
- **ML/Data:** TensorFlow, PyTorch, Keras, scikit-learn, Pandas, NumPy, SciPy
- **Visualization:** Matplotlib, Plotly, Power BI
- **Deployment:** Google Cloud Platform (GCP)
- **Design:** Figma, Adobe XD, Canva
- **Databases:** MySQL, Microsoft SQL Server
- **Other Tools:** OpenCV, mlflow, WordPress, GitHub Pages

## Repository Structure
```
.
├── README.md              # Personal profile & tech stack showcase
├── Project Test/          # Experimental/test projects
│   └── Test Dart         # Dart language learning file (syntax errors present - for testing)
└── .github/              # CI/CD and documentation
```

## Key Patterns & Conventions

### Code Style & Quality
- Focus on **readable, well-documented Python** for data science projects
- Use **Jupyter notebooks** for exploratory data analysis and model development
- Include docstrings and comments explaining ML concepts, especially for complex transformations
- Follow **PEP 8** guidelines for Python code

### ML & Data Science Workflow
1. **Data Exploration:** Pandas DataFrames, descriptive statistics, visualizations with Matplotlib/Plotly
2. **Model Development:** scikit-learn for classical ML, PyTorch/TensorFlow for deep learning
3. **Model Tracking:** Use mlflow for experiment logging and reproducibility
4. **Validation:** Train-test split, cross-validation, appropriate metrics (not just accuracy)

### Project Organization
- **Exploratory notebooks** in project directories with clear naming (e.g., `01_data_exploration.ipynb`, `02_model_training.ipynb`)
- **Reusable modules** in Python `.py` files for production-ready code
- Include **data** directories with raw and processed data separation
- Separate **utilities** for common preprocessing and model evaluation functions

## Common Tasks & Development

### Running Experiments
- For Python ML projects: Use Jupyter notebooks for interactive development
- For model comparisons: Log metrics in mlflow for tracking
- Test scripts should be executable from command line: `python script_name.py`

### Building & Testing
- No complex build system detected; scripts are typically run directly with Python
- Data-heavy operations may require GCP credentials for cloud-based datasets
- Verify Python version compatibility (Python 3.7+) for modern ML libraries

### External Integrations
- **GCP:** Used for cloud-based data storage and model serving
- **GitHub Pages:** Used for portfolio/blog hosting
- **Medium.com:** Platform for publishing ML/data analytics articles

## Important Files & Their Purpose
- [README.md](README.md) — Personal profile, tech skills, and contact information (also serves as codebase overview)
- [Project Test/Test Dart](Project%20Test/Test%20Dart) — Dart language learning/testing file

## Notes for AI Agents
- This is a **learning and portfolio repository** — code quality varies by project maturity
- Prioritize **clarity and educational value** in code improvements
- When suggesting ML patterns, consider reproducibility and model explainability
- The "Project Test" directory contains experimental code that may have syntax issues
- Always maintain data privacy — no real credentials or sensitive datasets in committed files
