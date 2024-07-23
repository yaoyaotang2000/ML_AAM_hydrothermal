# **Environment**

The most important python packages are:
- python == 3.8.18
- pytorch == 1.2.0
- torch == 1.13.0
- torchvision == 0.14.1
- numpy == 1.24.2


---
# **Command**

### **1. model select**
Use model_select.ipynb
Args:
  - data_path : The path of input CSV file. *E.g. experiment_dataset.csv*
  - dataset_type : The type of dataset. *E.g. classification  or  regression*
  - save_path : The path to save output model. *E.g. model_save*


### **2. model optimized**
Use model_optmized_XGB.ipynb

Args:
  - data_path : The path of input CSV file to predict. *E.g.  experiment_dataset.csv*
  - model_path : The path of trained model. *E.g. model_save/model.pt*


### **3. AAM algorithm select**
Use select_AAM.ipynb
Args:
  - data_path : The path of input CSV file. *experiment_dataset.csv*
  - dataset_type : The type of dataset. *E.g. classification  or  regression*
  

### **4. base on the AAM to screen the max points on the optimzed model**
Use SA_XGB_iteration.ipynb

Args:
  - model_path : The path of trained model. *E.g. model_save/model.pt*



