# CSE252 — Introduction to Artificial Intelligence and Machine Learning

Course material for **CSE252**, Lovely Professional University, session 2026–27
(August–February).

> **Important Note:** If you experience access issues, preview errors, or are
>unable to view any PDF or script directly on GitHub, please download the file
> to your local machine to access it properly.

---

## Course at a glance

| | |
|---|---|
| **Course code** | CSE252 |
| **Course title** | Introduction to Artificial Intelligence and Machine Learning |
| **L : T : P** | 2 : 0 : 2 |
| **Credits** | 3 |
| **Course planner** | 32952 :: Sumit Mittu |
| **Weightage** | ATT 5 · CA 25 · MTT 20 · ETT 50 |
| **Mid Term** | Applicable |

---

## Course outcomes

Through this course students should be able to:

| CO | Outcome |
|---|---|
| **CO1** | Understand the fundamental concepts of Artificial Intelligence, Machine Learning, intelligent agents, and their applications in robotics and autonomous systems. |
| **CO2** | Apply preprocessing, feature engineering, and visualization techniques on datasets for developing AI models. |
| **CO3** | Build supervised machine learning models for solving regression and classification problems using appropriate algorithms. |
| **CO4** | Apply unsupervised learning techniques for clustering and dimensionality reduction to discover hidden patterns in data. |
| **CO5** | Examine and improve machine learning models using appropriate performance metrics and validation techniques. |
| **CO6** | Build simple AI-enabled solutions for real-world robotics and automation problems using Python and Scikit-learn. |

---

## Units

### Unit I — Foundations of Artificial Intelligence
Introduction to AI and its evolution · Types of Artificial Intelligence ·
AI vs ML vs Deep Learning vs Data Science · Problem-solving using AI and the AI
development lifecycle · Intelligent agents and agent environments ·
Applications of AI in robotics, healthcare, manufacturing and smart cities ·
Ethics in AI and Responsible AI · Introduction to Generative AI

### Unit II — Data Preparation and Machine Learning Workflow
Introduction to NumPy, Pandas and Matplotlib · Understanding data — types of
datasets, data collection and exploratory data analysis · Data preprocessing —
handling missing values and detecting outliers · Feature engineering — feature
scaling, encoding and selection · Training and validation — train-test split
and cross validation

### Unit III — Supervised Machine Learning
Regression — linear regression, polynomial regression, decision tree
regression · Classification — logistic regression, K-nearest neighbour,
decision tree classifier, random forest, Naïve Bayes · Concepts of bias,
variance, underfitting and overfitting

### Unit IV — Unsupervised Learning
Clustering — K-means clustering, hierarchical clustering, concept of DBSCAN ·
Dimensionality reduction and Principal Component Analysis · Pattern discovery
— association rule mining and the Apriori algorithm · Unsupervised learning
applications in robotics and sensor data

### Unit V — Model Evaluation and Improvement
Regression metrics — MAE, MSE, RMSE, R² score · Confusion matrix and
classification metrics — accuracy, precision, recall, F1-score, ROC-AUC ·
Model improvement — cross validation, hyperparameter tuning, grid search,
random search · Introduction to Explainable AI

### Unit VI — AI for Intelligent Systems and Robotics
Computer vision — overview of image classification and object detection ·
Natural language processing — NLP fundamentals, chatbots and conversational
AI · Reinforcement learning — agent, state, action, reward · AI for autonomous
robots and future trends

---

## Practicals

| # | Practical | Unit |
|---|---|---|
| 1 | Installation and familiarisation with Python, Jupyter Notebook and Google Colab | I |
| 2 | Data manipulation using NumPy and Pandas | II |
| 3 | Data visualisation using Matplotlib | II |
| 4 | Exploratory data analysis on a real-world dataset | II |
| 5 | Data preprocessing — missing values, encoding and feature scaling | II |
| 6 | Implementation of linear regression | III |
| 7 | Implementation of logistic regression | III |
| 8 | Classification using K-nearest neighbour | III |
| 9 | Classification using decision tree and random forest | III |
| 10 | Clustering using K-means | IV |
| 11 | Dimensionality reduction using PCA | IV |
| 12 | Performance evaluation — confusion matrix, precision, recall, F1-score | V |
| 13 | Hyperparameter tuning using grid search | V |
| 14 | Mini project — an AI solution for robotics, automation or a smart system | VI |

Each practical ships as two notebooks: a **student** copy with `# TODO` gaps to
complete, and an **instructor** copy with the gaps filled and teaching notes
attached. Both run offline — datasets are either bundled with scikit-learn or
generated inside the notebook, so no internet connection is required.

---

## Continuous assessment

| Task | Detail | Marks | Weeks |
|---|---|---|---|
| **Project** | A machine-learning solution to a real-world problem. Group work, submitted online. Rubric: innovation and societal benefit (10), technical quality and completeness (10), report and viva (10). | 30 | 3 / 11 |
| **Test 1** | Subjective test on Units I–II. Concept-based, numerical and coding questions of 5 or 10 marks. | 30 | 4 / 5 |
| **Test 2** | Subjective test on Units I–III. | 30 | 11 / 12 |

CA category **A0203** — best 2 of 3.

---

## Repository layout

```
CSE252/
├── Unit_1_Foundations_of_AI/          Unit - 1.pptx, notes (.tex / .pdf)
├── Unit_2_Data_Prep_and_ML_Workflow/
├── Unit_3_Supervised_Machine_Learning/
├── Unit_4_Unsupervised_Learning/
├── Unit_5_Model_Evaluation/
├── Unit_6_AI_for_Intelligent_Systems/
├── Practicals/
│   ├── Unit_1_Foundations_of_AI/      P01 … student copies
│   │   └── instructor/                P01 … _INSTRUCTOR copies
│   └── …                              one folder per unit
├── _build_tools/                      scripts that generate the notes
├── CSE252_Master_Notes.pdf            all six units in one document
└── CSE252 __ INTRODUCTION TO ….pdf    the official syllabus
```

Slide decks and notes are **generated from scripts**, not hand-edited. To change
a deck, edit its build script and rebuild — editing the `.pptx` directly will be
overwritten on the next build.

---

## Running the practicals

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook
```

Open any notebook under `Practicals/` and run the cells in order, top to bottom.
Practical 1 checks your environment and tells you what is missing, so start
there.

---

## Reading

**Textbook**

- **T-1** — *Artificial Intelligence: A Modern Approach*, Stuart Russell and
  Peter Norvig (Pearson)

**Reference books**

- **R-1** — *Machine Learning with PyTorch and Scikit-Learn*, Sebastian Raschka,
  Yuxi (Hayden) Liu, Vahid Mirjalili (Packt)
- **R-2** — *Python Machine Learning by Example*, Yuxi (Hayden) Liu (Packt)
- **R-3** — *A First Course in Artificial Intelligence*, Deepak Khemani
  (McGraw Hill)
- **R-4** — *Fundamentals of Machine Learning: A Business Perspective*,
  Pratyush Banerjee, Supriti Mishra, Shivashankar Chari (McGraw Hill)
- **R-5** — *Data Science and Machine Learning Using Python*, Reema Thareja
  (McGraw Hill)

---

## A note on scope

The instruction plan is a tentative plan and may change during delivery.
Students should use the syllabus when preparing for examinations, and are
expected to keep up with contemporary developments — **up to 20% of the
questions in any examination or academic task may be drawn from current issues
even where they are not named explicitly in the instruction plan.**

---

*Maintained for teaching use. Question banks and assessment material are
confidential and are deliberately not included in this repository.*
