# Practical Data-Centric AI/ML for Biomedical Researchers

  - [Introduction](#introduction)
  - [Learning Objectives](#learning_objectives)
  - [Sponsors](#sponsors)
  - [License](#license)
  - [Schedule](#schedule)

## Introduction
The landscape of biomedical research is experiencing a fundamental shift, transitioning from hypothesis-driven approaches to data-driven discoveries fueled by the large and complex datasets generated through high-throughput technologies. Effectively analyzing and extracting meaningful insights from these datasets requires researchers to be proficient in advanced computational methods such as Artificial Intelligence (AI) and Machine Learning (ML). Furthermore, cloud computing offers flexible, cost-effective, and powerful solutions for data storage, analysis, and collaboration without the infrastructure burden of individual institutions. However, unlocking the full potential of cloud-based AI/ML in biomedical research hinges on equipping researchers with the necessary skills and knowledge. Recognizing this gap, the National Institute of General Medical Sciences (NIGMS) launched the NIGMS Sandbox initiative, aiming to create a repository of cloud-based learning modules for diverse biomedical data science topics. The proposed module, "Practical Data-Centric AI/ML for Biomedical Researchers" aligns perfectly with the NIGMS’s vision to expand the skilled workforce capable of harnessing the power of cloud computing and AI/ML. The module tackles the crucial challenge of upskilling biomedical researchers by equipping researchers with these skills to foster innovation, accelerate scientific discovery. By leveraging the NIGMS Sandbox and cloud platform, the module ensures broad accessibility. This democratizes access to cutting-edge knowledge, empowering researchers regardless of their institutional resources and fostering a more inclusive research landscape. The curriculum prioritizes practical, data-centric techniques, ensuring researchers can immediately apply their acquired knowledge to real-world problems. We pay special attention to critical upstream tasks like data preparation, cleaning, etc. that are the key to successful AI/ML applications. We aim to train the participants with the competencies and skills needed to make biomedical data FAIR ([Findability, Accessibility, Interoperability, and Reusability](https://pubmed.ncbi.nlm.nih.gov/26978244/)) and AI/ML-ready. Our goal is to bring awareness and practices to our trainees so that their data are collected and prepared to support AI/ML applications, with attention to

- use of data and metadata standards to make data FAIR, 
- presentation and labeling of data, including noise, uncertainty, and missing data issues, and 
- ethical and social considerations and collaborative team science. 

The module also utilizes a blend of engaging instructional videos, interactive demonstrations, hands-on exercises to facilitate self-directed learning and knowledge retention. This innovative approach caters to diverse learning styles and maximizes learning outcomes, ensuring a more engaging and effective learning experience for all participants.

## Learning Objectives

- Equip learners with the fundamentals of AI/ML in biomedical research.
- Cover topics such as data preparation, model building, and real-world deployment, and 
- Focus on practical skills and responsible development.

## Sponsors

The cloud-based sandbox module is supported by the NIH National Institute for General Medical Sciences (3T32GM142603-03S1).


## Submodules

**Submodule 1 - Introduction**
```
Study core concepts, diverse applications, introductory algorithms, ethical considerations, and data challenges.
```

- Lecture
  - [Introduction to AI/ML](https://docs.google.com/presentation/d/1QqiLijMrdQ5bwjayNeFz2dCx1v8Te4PVy5brscaL-aY/edit?usp=sharing) ([Quiz](https://forms.gle/xqqr4eRbkM6DdZ1g7))
- Live Demo
  - [Introduction to NumPy](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Live_Demos/Day_1_Live_Demo_2_Introduction_to_NumPy.ipynb)
  - [Introduction to Pandas](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Live_Demos/Day_1_Live_Demo_3_Introduction_to_Pandas.ipynb)
- Exercise
  - [NumPy Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_NumPy.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_NumPy_Solution.ipynb))
  - [Pandas Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_Pandas.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_Pandas_Solution.ipynb))

**Submodule 2 - FAIR Data Principles, Data-Centric AI/ML, and Responsible AI/ML**
```
Learn FAIR principles for responsible data management, evaluate data quality and AI/ML readiness, and understand fairness, transparency, and accountability in AI/ML development and deployment.
```
- Lecture
  - [FAIR Data Principles]() ([Quiz]())
  - [Data Readiness for AI/ML Checklist](https://docs.google.com/presentation/d/1AGXmqoWbo1JHNTcgVqWXVYEbTlPg1Rid7J8mbrm58Kk/edit?usp=sharing) ([Quiz](https://forms.gle/DFWt45wtEN2JbW4v6))
  - [Data-Centric AI/ML]() ([Quiz]())
  - [Responsible AI/ML]() ([Quiz]())
- Live Demo
- Exercise
  
**Submodule 3 - Data Preparation**
```
Learn practical data cleaning techniques, as well as feature engineering, feature scaling, and feature selection techniques.
```
- Lecture
	- [Data Collection and Data Preparation](https://docs.google.com/presentation/d/1iuT2jQpTqY6E8CI2GRbwFALLCTPukQLlCkB7d4xj8jA/edit?usp=sharing) ([Quiz](https://forms.gle/RbGQjivp2N5TXC1LA))
  - [Feature Engineering, Scaling and Selection](https://docs.google.com/presentation/d/1boVdrT2YqcIj0MzOQiObSp8MBqGcgrtaYoJvve0C5IU/edit?usp=sharing) ([Quiz](https://forms.gle/PSkB75tfwhmFS6jNA))
- Live Demo
  - Data Cleaning
    - [Basic Data Cleaning](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_1_Basic_Data_Cleaning.ipynb)
    - [Marking and Removal of Missing Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_2_Mark_and_Remove_Missing_Data.ipynb)
    - [Outlier Identification and Removal](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_3_Outlier_Identification_and_Removal.ipynb)
    - [Missing Data Imputation](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_4_Missing_Data_Imputation.ipynb)
  - Feature Engineering
    - [Encode Categorical Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_1_Feature_Engineering_Encode_Categorical_Data.ipynb)
    - [Change Numerical Data Distribution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_2_Feature_Engineering_Change_Numerical_Data_Distributions.ipynb)
    - [Derive New Input Variables](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_3_Feature_Engineering_Derive_New_Input_Variables.ipynb)
  - Feature Scaling
    - [Numerical Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_LIve_Demo_4_Feature_Scaling_Numerical_Data.ipynb)
    - [Data With Outliers](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_5_Feature_Scaling_Data_with_Outliers.ipynb)
  - Feature Selection
    - [Numerical Input Features](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_6_Feature_Selection_Categorical_Input_Features.ipynb)
    - [Categorical Input Features](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_LIve_Demo_7_Feature_Selection_Numerical_Input_Features.ipynb)
    - [Recursive Feature Elimination](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_8_Feature_Selection_Recursive_Feature_Elimination.ipynb)
- Exercise
	- [Data Wrangling Exericse](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Exercises/Day_2_Exercise_Data_Wrangling.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Exercises/Day_2_Exercise_Data_Wrangling_Solution.ipynb))
  - [Feature Engineering Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Engineering.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Engineering_Solution.ipynb))
  - [Feature Scaling Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Scaling.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Scaling_Solution.ipynb))
  - [Feature Selection Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exericse_Feature_Selection.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exericse_Feature_Selection_Solution.ipynb))

**Submodule 4 - Model Building, Evaluation, Interpretation, and Deployment**
```
Explore different AI/ML model types, and model evaluation techniques, delve into interpretability methods, and learn best practices for model deployment.
```
- Lecture 
  - [AI/ML Models and Model Evaluation](https://docs.google.com/presentation/d/1nk-CBd-6o5J-S8QTVrvXOtalnjUoSRgqgHSNaFEAq4M/edit?usp=sharing) ([Quiz](https://forms.gle/eqjGPvWg517qxP9y7))
  - [Model Tuning, Interpretation and Deployment](https://docs.google.com/presentation/d/1PRIDgPmcQuxxHIs3V0zslJXymmEwQSqdJgwgJ0t3yWY/edit?usp=sharing) ([Quiz](https://forms.gle/CRi9mTaqdZEBinzVA))
- Live Demo
  - [Model Building and Evaluation](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_1_Model_Building_and_Evaluation.ipynb)
  - [Model Tuning, Interpretation, Deployment](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_2_Model_Tunning_Interpretation_Deployment.ipynb)

- Exercise
  - [Exploratory Analysis and Model Prediction with Biomedical Data]() ([Solution]())

**Submodule 5 - AI/ML for Biomedical Applications**
```
Show different types of AI/ML algorithms and their suitability for biomedical data. Explore real-world examples of AI/ML in various areas of biomedicine.
```
- Lecture 
  - [AI/ML Applications in Biomedicine](https://docs.google.com/presentation/d/1z9OktpolGPzeWjN_mz4h61iV22i9Zvf0qTQp5MW7YA4/edit?usp=sharing) ([Quiz](https://forms.gle/GDiDP88bKuJPUxxY9))
  - [Introduction to Deep Learning](https://docs.google.com/presentation/d/1_GNZw6aiE8m9YMsF18NokoIJH6K2tWLWN70S4C98kxM/edit?usp=sharing) ([Quiz](https://forms.gle/9ZSgQJPLxdkvFQjN6))
- Live Demo
  - [Pfam protein sequence classification using Tensorflow and Keras](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_5/Live_Demos/Day_5_Live_Demo_1_Pfam_Protein_Sequence_Classification_with_Tensorflow_Keras.ipynb)

- Exercise
  - [Protein 3D structure prediction using AlphaFold2](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_5/Exercises/Day_5_Exercise_2_AlphaFold.ipynb)
  
  
- [Course Summary](https://docs.google.com/presentation/d/1lqlWVt4-bZHavCK4rfEKl0In6iENZl6tn569CtI0nlA/edit?usp=sharing)
- [Course Survey](https://forms.gle/7D8hrCVzUGJcUwwY7)


