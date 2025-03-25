# Work Division

## Team Members
- **Cosmin Tianu**  
- **Cosma Razvan**  

## **Task 1: Dataset Generation**  
Generate artificial datasets that illustrate the assumptions and characteristics
of different methods. Datasets are ideally bidimensional.  
### Create datasets with varying:  
  - Number of instances (rows in your dataset table)
  - Number of classes  (for multi-class classification problems)
  - Proportion of classes (balanced and imbalanced class problem)
  - Distribution of points within each class (shape of point clouds)  
  - Decision boundaries (linear etc.)  
  - Noise levels  
  - Class overlap  

### Consider the following methods:
  - Logistic Regression - Cosmin
  - LDA (Linear Discriminant Analysis) - Cosmin
  - QDA (Quadratic Discriminant Analysis) - Razvan
  - Decision Tree (without pruning) - Razvan
  - Decision Tree (with a max depth of 2) - Cosmin
  - SVM linear (Linear Support Vector Machine) - Cosmin
  - SVM RBF (Radial Basis Function SVM) - Razvan

---

### **Task 2: Investigate method assumptions**  
Find for each of the listed methods a dataset where the **respective assumptions are met** and assumptions of the other methods are not met (if possible). In other words, a dataset where that method is hard to beat using **cross validation**.

**Explain** why this dataset is appropriate for the method.

**Suggestion**: use datasets with 2 predictors and one class variable with
only two distinct classes that can be visualized. This is not mandatory, but
may facilitate the task.

---

### **Task 3: Bias-Variance Tradeoff & Model Capacity**   
- Find a dataset where by **varying the level of noise** (or other dataset properties such as border shape) different levels of tree pruning are ideal, from no pruning to maximum pruning. Produce a plot of level of noise (or other some other property if you prefer) against ccp alpha. - Cosmin
- Measure bias and variance error decomposition for three versions of this dataset along ccp alpha (decision trees). - Razvan
- Interpret the results in terms of model capacity, bias error, variance error and total error. - Razvan

---

### **Task 4: Ensemble Learning (Bagging, Random Forest, Boosting)**  
With the dataset you used to study trees, compare Bagging, RandomForest
and AbaBoost and other forms of boosting.
#### **Subtasks**  
- Train and evaluate:  
  - Bagging  - Razvan
  - Random Forest - Cosmin
  - AdaBoost (or another boosting method) - Razvan
- Compare learning curves:  
  - Plot performance vs. the number of trees.  
  - Use Out-of-Bag (OOB) estimates.  
- Validate models with cross-validation and compare results. - Cosmin
- Discuss findings on why certain ensemble methods perform better.  

---

### **Task 5: Report & Presentation**  
 write the final report, and prepare the presentation. - Cosmin  
- Write a structured report including:  
  - Cover page with authors, title, and date.  
  - Methodology and results.  
  - Discussion of key findings.  
  - References and appendix (if needed).  
- Prepare a presentation (both members present in class).  
- Ensure all team members understand each section for evaluation purposes.  

---

## **Notes**  
- Each team member should document their approach clearly.  
- Code should be well-commented for reproducibility.  
- Results should be well-organized with visualizations and tables.  


## **Evaluation**
Components
- Writing 30%
- Technical 60%
- Presentation 10%: Clarity, confidence, communication, timely delivery.