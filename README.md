# ML Training Cookbook

A hands-on, beginner-friendly introduction to Machine Learning designed for newcomers with Python basics but new to ML.

## Overview

This repository contains an interactive 2-hour Jupyter notebook that provides a gentle, non-overwhelming introduction to machine learning fundamentals. Perfect for new hires, students, or anyone looking to understand ML through practical examples and guided exercises.

**What you'll learn:**
- Core ML concepts and definitions
- Types of machine learning (supervised, unsupervised, reinforcement)
- End-to-end ML workflow from problem to deployment
- Hands-on experience with real datasets (Iris, Boston Housing, Customer Churn)
- Popular algorithms and when to use them
- Ethics, bias detection, and responsible AI practices

## Key Features

- **🎯 Interactive Learning**: Guided code cells with fill-in exercises and built-in solutions
- **📊 Real Datasets**: Work with classic ML datasets including Iris classification, house price prediction, and customer churn modeling
- **🔍 Practical Examples**: Business-relevant case studies that demonstrate ML's real-world impact
- **⚖️ Ethics Focus**: Dedicated section on responsible AI, bias detection, and explainability
- **📚 External Resources**: Curated links to continue your ML journey
- **🛠️ Best Practices**: Python coding standards and virtual environment setup

## Getting Started

### Prerequisites

- Basic Python knowledge (pandas, loops, functions)
- Familiarity with Jupyter notebooks
- No prior ML experience required!

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ML-Training-Cookbbok
   ```

2. **Create and activate virtual environment**
   ```bash
   # Create virtual environment
   python -m venv myenv
   
   # Activate (Windows)
   myenv\Scripts\activate
   
   # Activate (Unix/Mac)
   source myenv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   
   Or using the project configuration:
   ```bash
   pip install -e .
   ```

4. **Launch Jupyter notebook**
   ```bash
   jupyter notebook src/Intro_ML_Training_Notebook.ipynb
   ```

### Dependencies

Core libraries included:
- **Data Science**: pandas, numpy, scikit-learn
- **Visualization**: matplotlib, seaborn  
- **Jupyter**: jupyter, ipykernel, notebook

All datasets are loaded programmatically - no manual downloads required!

## Usage

1. **Start the notebook**: Open `src/Intro_ML_Training_Notebook.ipynb`
2. **Follow the sections**: Each section builds on the previous one
3. **Complete exercises**: Try the fill-in code exercises before checking solutions
4. **Experiment**: Modify parameters and explore "what-if" scenarios
5. **Ask questions**: Use the Q&A section for discussion

The notebook is designed to be self-paced but works excellently for group training sessions.

## Time Commitment

- **Core content**: ~2 hours
- **With exercises and discussion**: 2.5-3 hours
- **Optional Q&A extension**: +15 minutes

Each section includes time estimates to help pace your learning.

## Repository Structure

```
ML-Training-Cookbbok/
├── README.md                          # This file
├── requirements.txt                   # Core dependencies
├── pyproject.toml                    # Project configuration
└── src/
    └── Intro_ML_Training_Notebook.ipynb  # Main training notebook
```

## Learning Path

The notebook covers:

1. **Introduction & Setup** (10 min) - Environment setup and Python best practices
2. **What is ML?** (15 min) - Definitions, examples, and data exploration
3. **Types of ML** (20 min) - Supervised vs unsupervised vs reinforcement learning
4. **ML Workflow** (15 min) - 6-step process with house price prediction
5. **Case Study** (20 min) - Customer churn prediction for telecom company
6. **Popular Algorithms** (15 min) - Quick tour of common methods
7. **Ethics & AI** (15 min) - Bias detection, explainability, responsible AI
8. **Next Steps** (10 min) - Resources and project ideas

<!-- ## Contributing

This is an educational resource. If you find issues or have suggestions for improvements, please open an issue or submit a pull request. -->

## License

MIT License - feel free to use this material for educational purposes.

## Support

For questions about the content or technical issues:
- Check the notebook's built-in Q&A section
- Review the external resources linked throughout
- Open an issue in this repository

---

**Ready to start your ML journey?** Open the notebook and dive in! 🚀

*Note: This notebook emphasizes understanding over mathematical rigor, making ML concepts accessible to beginners while maintaining technical accuracy.*