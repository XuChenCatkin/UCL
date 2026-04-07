# UCL MSc Machine Learning Coursework and Notes

This repository contains **coursework assignments, practice notebooks, handwritten notes, and lecture notes** from the MSc Machine Learning programme at University College London.

## Repository Structure

### Course Materials

All coursework is organized in the `Courseworks/` directory:

**COMP0078 - Supervised Learning**
- Coursework on supervised learning methods
- Dataset: Boston housing predictions
- Topics: regression, classification, feature engineering

**COMP0083 - Kernel Methods and Convex Optimisation**
- `ConvexOptimisation/` - Optimization coursework
- `Kernel/` - Kernel methods assignment
- Topics: SVM, kernel tricks, optimization algorithms

**COMP0085 - Approximate Inference**
- Comprehensive coursework on probabilistic inference
- Topics: graphical models, message passing, variational inference, MCMC
- LaTeX lecture notes with extensive theoretical coverage

**COMP0086 - Unsupervised Learning**
- Coursework with practical datasets (MNIST, War and Peace, binary digits)
- Topics: clustering, dimensionality reduction, topic modeling
- Includes preprocessing and symbolic data files

**COMP0089 - Reinforcement Learning**
- 4-part coursework series (part1–part4)
- Topics: MDP, value iteration, policy gradient, Q-learning
- Hands-on RL implementation projects

**COMP0171 - Bayesian Deep Learning**
- `coursework-one/` - Bayesian classifiers and uncertainty quantification
- `coursework-two/` - Variational autoencoders with MNIST data
- Hands-on projects in probabilistic deep learning

### Comprehensive Lecture Notes

Professional LaTeX formatted lecture notes for key topics:
- **Approximate_Inference_Lecture_Notes.tex** - 50+ pages on inference methods
- **Bayesian_Deep_Learning_Lecture_Notes.tex** - 15+ pages covering optimization, automatic differentiation, posterior approximation, deep architectures, and uncertainty quantification
- **Kernel_Lecture_Notes.tex** - Kernel methods and theory
- **Reinforcement_Learning_Course_Notes.tex** - RL fundamentals
- **Supervised_Learning_Lecture_Notes.tex** - Classification and regression
- **Unsupervised_Learning_Lecture_Notes.tex** - Clustering and dimensionality reduction

### Supporting Materials
- **Handwritten_notes/** - Scanned notes from lectures and revision
- **Data files** - Course datasets (MNIST, text corpora, numeric datasets)

## Building the LaTeX Notes

The lecture notes are compiled using LaTeX with `latexmk`:

```bash
cd Notes/
latexmk -pdf <filename>.tex
```

All notes use consistent formatting with theorem environments, definitions, and professional layout based on lecture note best practices.

## Course Progression

The curriculum progresses through:
1. **Supervised Learning** (COMP0078) - Foundation in regression/classification
2. **Kernel Methods** (COMP0083) - Advanced optimization and kernel theory  
3. **Approximate Inference** (COMP0085) - Probabilistic graphical models
4. **Unsupervised Learning** (COMP0086) - Clustering and representation learning
5. **Reinforcement Learning** (COMP0089) - Markov decision processes and learning algorithms
6. **Bayesian Deep Learning** (COMP0171) - Modern deep learning with uncertainty

## Technologies Used

- **Python/Jupyter** - Coursework implementations
- **LaTeX** - Professional lecture notes
- **Datasets** - MNIST, UCI, text corpora for practical assignments

---

*These materials represent the core coursework and learning from the MSc Machine Learning programme at UCL.*
