# Introduction to statistical learning and applications 2026

---

Hi :wave: 

This is the main page to look for materials of our classes on "Statistical learning and applications" in 2026. Please note that we **won't be using Chamilo**, so you should be checking this page regularly for updates.

### Instructors
- Pedro L. C. Rodrigues — pedro.rodrigues@inria.fr (CM, TD, and TP)
- Isabella Costa Maia — isabella.costa-maia@grenoble-inp.fr (TD and TP)
- Razan Mhanna — razan.mhanna@inria.fr (Complementary courses for M1AM students)

### Schedule
We will meet on Mondays from 15h30 to 18h30. Each time we will have a 1h30 CM 
and a 1h30 TD or TP session. 

We will be doing a total of 11 CM, 6 TP sessions, and 6 TD sessions.

The (initial) plan for the topics of each of our classes is the following:

- **Week 1 (02-February 2026)** 
  - CM1: Introduction, simple linear regression, multivariate statistics
  - TD1: Exercises on multivariate statistics and regression

- **Week 2 (09-February 2026)** 
  - CM2: Multiple linear regression
  - TP1: Regression

- **Week 3 (23-February 2026)**
  - CM3: Cross-validation, model selection, bias-variance tradeoff
  - TP1: Regression -- **Deadline XX**

- **Week 4 (02-March 2026)**
  - CM4: Principal component analysis
  - TD2: Exercises on linear regression and PCA

- **Week 5 (09-March 2026)**
  - CM5: Linear classification — Discriminative approach
  - TP2: Principal components regression (PCR)
  
- **Week 6 (16-March 2026)**
  - CM6: Linear classification — Generative approach
  - TP2: Principal components regression (PCR) -- **Deadline XX**

- **Week 7 (23-March 2026)**
  - CM7: Decision trees
  - TP3: Benchmarking classification methods
  
- **Week 8.1 (30-March 2026)**
  - CM8: Ensemble methods
  - TD4: Some questions from previous exams

- **Week 8.2 (03-April 2026)**
  - TD3: Some questions from previous exams

- **Week 9 (13-April 2026)**
  - CM9: ML competitions, metrics, etc.
  - TD5: Gradient boosting

- **Week 10 (20-April 2026)**
  - CM10: Tabular Foundational Models (1)
  - TD6: Some questions from previous exams

- **Week 11 (27-April 2026)**
  - CM11: Tabular Foundational Models (2)
  - TP3: Benchmarking classification methods -- **Deadline XX**

### Textbooks
- Many examples and explanations given in class were inspired (or unashamedly copied) from Cosma Shalizi’s excellent lecture notes *“The truth about linear regression”* available [here](https://www.stat.cmu.edu/~cshalizi/TALR/).
- Students should also consider reading chapters from James et al. (2022) *"Introduction to statistical learning with applications to Python"* which is freely (and legally) available [here](https://www.statlearning.com/).
- Another excellent reference is Hastie et al. (2017) *"Elements of Statistical Learning"* which is freely (and legally) available [here](https://hastie.su.domains/ElemStatLearn/).

### Grading
Your final grade will the average of your TP scores (50%) and the final exam (50%). See below for details.

#### -- Concerning the TP scores
During the semester, you will work on three TP subjects in groups of three students. Each TP score will be based on two parts:
(1) The grade of your report (50%)
  - The report is a `ipynb` that should answer the questions from the TP
(2) The performance of your group in the corresponding challenge (50%). The best group gets the best grade (20).
You will send us by e-mail the URL of a github repo containing your report and the code used for the competition

#### -- Concerning the final exam
The final exam will be a 3h practical evaluation on the computers from ENSIMAG. It will have some multiple-choice questions to evaluate your theoretical knowledge and some practical questions similar to what you will do in the TPs. You will not have access to any internet connections, but you can bring your own handwritten notes. In the computer that you will use, we will provide you a folder with the instructions for the exam, the `ipynb` files to fill with your answers and code, as well some materials of the course.

### Setting up a working environment

Here below we show you one way of setting up a `conda` environment so that you're sure of being able to run all the packages necessary for our class.

1) First of all, you should install `conda ` in your computer as detailed [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).
2) Run `conda create -n isla2026` on your terminal.
3) Run `pip install -r requirements.txt` on your terminal.

You should be all set to start working on the TPs. If this is not the case, please make an [issue](https://github.com/ISLA-Grenoble/2026-main/issues) on this repository detailing your problem so that I can either fix it or at least help you out.