# Support Vector Machines (SVM) (Breast Cancer Dataset)

###  Overview
This project is part of my internship tasks at Elevate Labs.  
It applies **Support Vector Machines (SVM)** to the Breast Cancer dataset to classify tumors as **benign (0)** or **malignant (1)**.

### Steps Performed
- Loaded dataset (`breast_cancer.csv`).
- Split into training (80%) and testing (20%).
- Standardized features using `StandardScaler`.
- Trained **Linear SVM** classifier.
- Trained **RBF Kernel SVM** classifier.
- Compared models using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC-AUC and ROC Curves
- Visualized decision boundaries in 2D using PCA.

###  Files
- `Task7_SVM.ipynb` → Notebook with code + outputs  
- `breast_cancer.csv` → Dataset used  
- `Task7_SVM_Report.docx` → Detailed report  
- `README.md` → This summary  

###  Results
- **Linear SVM**: Good baseline accuracy but limited for non-linear data.  
- **RBF Kernel SVM**: Higher accuracy and ROC-AUC, captured complex decision boundaries.  
- SVM proved to be a robust classifier with excellent performance on medical classification tasks.

