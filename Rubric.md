Here is the exact transcription of the rubric images into Markdown format.

***

**College of Computer Science and Engineering**
**Department of Computer Science and Artificial Intelligence**
**CCAI-312: Pattern Recognition**

### Project Rubric:

Each component of your project will be evaluated according to the following grading scale. Marks are assigned based on the quality, completeness, clarity, and correctness of your work:

| Grade Level | Description |
| :--- | :--- |
| **Excellent (1.0)** | All requirements are fully met. Work is accurate, complete, and demonstrates strong understanding, clarity, and high quality. |
| **Good (0.75)** | Minor issues are present, but work is mostly correct, complete, and clearly presented. |
| **Fair (0.5)** | Several issues or gaps; work is partially correct or incomplete, showing limited depth or clarity. |
| **Weak (0.25)** | Major errors or unclear presentation; demonstrates poor understanding or minimal effort. |
| **Missing (0)** | Not done or completely incorrect. No meaningful submission or effort demonstrated. |

**Note:**

* Each section of your project, including the report, code, presentation, and both theoretical and practical explanations—will be assessed using this rubric. Scores for each criterion will reflect not only whether it was done, but how well it was done in terms of correctness, clarity, and depth of understanding.
* Each student will be assessed individually based on their explanation of both theoretical and practical aspects of the project during presentation or viva.
* Each member must contribute actively and demonstrate understanding of the entire project. Individual marks may be adjusted by **±2 points** based on the instructor’s evaluation of participation and understanding.

---

### Part A: Code & Implementation (4 Marks)

**Data Preparation & Preprocessing (1 mark)**
* Use a new dataset from a credible source that was not used in class.
* Choose a dataset of appropriate size and feature count — large enough for meaningful learning but manageable for training and analysis.
    > 💡 *Hint: Aim for datasets with around 10000–100,000 rows and 10–30 relevant features. Avoid tiny datasets (under 10000 rows) or extremely large ones (millions of rows) unless you plan to sample or filter.*
* Identify and handle basic data issues such as missing values or duplicates
* Apply necessary preprocessing steps depending on the data and algorithm (e.g., encoding, scaling, normalization)
* Split the data correctly into training and test (or validation) sets
* Ensure the code is clean, modular, and reproducible
* Justify your preprocessing choices — not just apply them blindly

**Model Implementation (1 mark)**
* Implement a **new ML algorithm or a variation** (not simply reuse KNN or Decision Trees exactly as done in labs).
* Key parameters are initialized correctly.
* Logic of the algorithm is correctly applied to the dataset.
* Code runs without errors and produces expected outputs.
* Code is well-commented and structured.

**Evaluation & Tuning (1 mark)**
* Evaluation metrics (e.g., accuracy, F1, precision, recall) are appropriate and clearly used
* Model performance is discussed based on metric results
* Hyperparameters are tuned using suitable techniques (e.g., grid search, manual tuning)
* Performance improvement from tuning is demonstrated
* Visualizations (e.g., confusion matrix, ROC curve) are used to support analysis
* Appropriate techniques are used to detect issues such as overfitting or underfitting (e.g., train/test performance comparison, learning curves, cross-validation)

**Baseline Comparison (1 mark)**
* Compare your model with two class baseline models (e.g., DT, NB, KNN).
* Comparison is based on consistent evaluation metrics.
* Results of all models are presented in tables or charts.
* Insights are drawn from performance differences.

---

### Part B: Report, Data Analysis & Communication (4 Marks)

**Introduction, Problem Definition & Data Description (1 mark)**
* Clearly defines the machine learning problem (classification or regression).
* Provides strong motivation and real-world context.
* Outlines specific, measurable project objectives.
* Identifies input/output variables clearly.
* Include a literature review (4 papers minimum — 1 per student).
* Includes Data Description: Briefly mention the dataset source, name the input and output columns used, and summarize key preprocessing steps. No need to explain all dataset features.

**Methodology & Justification (1 mark)**
* Describes selected algorithm clearly with theoretical background.
* Explains why the algorithm is suitable for the problem.
* Mentions any assumptions or limitations.
* Identifies and explains hyperparameters.
* Describes any model modifications.

**Results & Discussion (1 mark)**
* Presents results with clarity using tables/graphs.
* Explains what the results mean, not just what they are.
* Compares proposed model vs. baselines.
* Analyzes strengths/weaknesses of approach.
* Draws logical insights from the data and outcomes.

**Conclusion, Abstract & Report Quality (1 mark)**
* Summarizes key findings clearly.
* Suggests meaningful directions for future work.
* Abstract provides concise overview of the project.
* References are properly formatted and cited.
* Report is well-written, logically structured, and professionally formatted.

### Part C: Question Answering (2 Marks)

**Theoretical (1 mark)**

Demonstrates clear grasp of the theory behind the chosen algorithm, evaluation metrics, and tuning strategy. Students should be able to explain and justify their modeling decisions using machine learning principles, showing depth of understanding. Each team member is assessed individually.

**Practical (1 mark)**
Shows ability to explain code functionality, preprocessing choices, and model design. Students should demonstrate debugging skills, discuss implementation challenges, and explain how they were addressed. Each team member is assessed individually.

---

### Project Deliverables (November 30th):
**1. Report:**
A structured report, following academic standards (4-5 pages including the cover page). The report should include:
* **Cover Page**
    Project title, course name, group number, full names and IDs of team members.
* **Introduction**
    Brief motivation and relevance of the problem you’re solving.
* **Problem Description**
    Clearly state the classification or regression problem, objectives, and target outcome.
* **Background Study**
    Summary of at least 4 relevant research papers (1 per student) that support your problem, dataset choice, or method.
* **Data Description**
    Dataset source, input/output variables, and key preprocessing steps.
* **Methodology**
    Explain your chosen algorithm and any variations or improvements made.
* **Experiments & Results**
    Present model performance using appropriate metrics, tables, and visualizations (e.g., confusion matrix, ROC curve).
* **Discussion**
    Interpret your results, highlight challenges, and compare your model to baselines.
* **Conclusion**
    Summarize findings and propose possible extensions.
* **References**
    Use proper citation format (APA/IEEE/MLA – consistent throughout).

**2. Code Notebook**

Submit a clean, fully runnable Jupiter notebook with:

* Structured code (modular and commented).
* Clear output sections for results.
* Preprocessing, model training, evaluation, and tuning.
* Code should be consistent with the report.

**3. Presentation (December 1-4-6):** Each team will present their project, explaining their approach, methodology, and findings.