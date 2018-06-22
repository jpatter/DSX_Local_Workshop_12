# DSX Local Workshop (for version 1.2)
In this workshop you will learn how to develop and deploy applications in DSX Local. The workshop has been divided into several stand-alone parts for those who are interested in a certain development tool or a certain deployment task. 

## About this repository
This repository contains several lab subfolders. Some labs include notebooks and data, while others have additional instructions that are located in the *Lab Instructions* folder. 

## Prerequisites
1. Knowledge of analytics. These labs do not teach you the basics of analytics or how to implement analytics in R, Python and SPSS. The purpose of this workshop is to provide hands-on experience with analytics tools and deployment functions in DSX. 
2. To run this workshop you need an instance of DSX Local. **Please note that while most code is the same between DSX Local and Watson Studio, the notebooks included in sample projects will work in DSX Local only**
3. Download [this repository](https://github.com/jpatter/DSX_Local_Workshop_12/raw/master/DSX%20Local%20Projects/DSX_Local_Workshop_12.zip). 

### Setting up lab projects in DSX Local
1. Rename **DSX_Local_Workshop_12.zip** located in **DSX_Local_Projects** folder of the unzipped repository to a unique name, for example, add your initials.    *Note: Project names in DSX Local cluster must be unique. When we create a project "from file", the project name is inherited from the file name*. 
2. Log in to DSX Local.
3. Select "Create New Project" and select "From File".
4. Browse to the .zip file and click **Create**.
![ProjectFromFile](/img/CreateProjectFromFile.JPG?raw=true).

### Use Case 1: Improve customer retention (SparkML models in Jupyter/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **TelcoChurn_SparkML** *Jupyter* notebook. This notebook has been implemented for the Python 2.7 runtime. You can verify the runtime by running the first cell in the notebook. 
3. Follow instructions in the notebook.
4. If you would like to see an example of invoking a published model with a REST client, import the **TelcoChurn_Invoke_Deployed_Model.jupyter.ipynb** notebook into your project and follow instructions in the notebook. 

### Use Case 2: Improve operational efficiency (Scikit-learn and SparkML models in Jupyter/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **CreditCardDefault_SkLearn** notebook. If you want to stay with the telco churn example, you can work through the **TelcoChurn_SkLearn** notebook. 
3. Follow instructions in the notebook.

### Use Case 3: Improve customer retention (SparkML models in Zeppelin/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **TelcoChurn_Zeppelin** notebook.
3. Follow instructions in the notebook.

### Use Case 4: Data science for the automotive industry (R models in Jupyter and Shiny)
1. Follow instructions in the **R_in_DSX.pdf** in the **Lab Instructions** folder of the unzipped repository. 

### Use Case 5: Improve customer retention and fraud prevention (SPSS Modeler in DSX)
1. Follow instructions in the **SPSS_Modeler_in_DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

### Use Case 6: Batch deployment of analytics (Batch Scoring in DSX)
1. Follow instructions in the **DSX_Batch_Scoring.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

### Use Case 7: DSX - a deployment platform for different types of models (PMML in DSX)
1. Follow instructions in the **DSX_PMML_Lab.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

### Use Case 8: DSX - a platform that supports analytics application lifecycle (Model Evaluation in DSX)
1. Follow instructions in the **DSX_Evaluation_in_DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

### Use Case 9: Data access in DSX
1. Follow instructions in the **DSX_Data_Access.pdf** document in the **Lab Instructions** folder of the unzipped repository. 
