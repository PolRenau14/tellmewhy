# Tell me why
Workshop  on AI, Topics: Explainable Artificial Intelligence, Black-Box Models, Ethics (Level: Intermediate)
## Building safe and robust models: Introduction to Explainability 
Problems of confidence and trust arise when automatic decisions are made by Artificial Intelligence. This fact becomes more obvious in sensitive scenarios such as Transportation, Security, or Medicine where decisions involve lives or a high economic factor. To solve this issue a new trend in computing appears: Explainability

 
The workshop comprises different techniques and methods to build explanations using White box Algorithms (Hands-on I) and Black box algorithms (Hands-on II).

## Hands-on 
### Hands-on I: White Box Models (Hands-on I - White Box.ipynb) 
In this hands-on are proposed algorithms where the internal structure allows an easy interpretation of the algorithm
- OneR Algorithm 
- Tree Classifier  
- Decision Rules

### Hands-on II: Black Box Models (Hands-on II - Black Box.ipynb)
In this hands-on are introduced how to explain High Accuracy algorithms (SVM, Deep Learning, Gradient Boosting Trees ... ) which cannot be explained directly due to the complexity. This type of algorithms is also referred to as Black Box Models. To provide explanations from Black Box Models are introduced SHAP and Lime two popular post-hoc techniques.
- LIME 
- SHAP 

### Exercise (Exercise.ipynb)
Train a model and explain the predictions using LIME and SHAP (use your own dataset or titanic data (Data/titanic.xls)

## Prerequisites
- Graphviz library (link: http://www.graphviz.org). If python not found graphviz installation, add installation folder to path. (In windows, add C:...\graphviz\bin to Control Panel > System and Security > System > Advanced System Settings > Environment Variables > Path > Edit > New. 
- An usable python3 installation or Anaconda Python3.7 

## Before start
- Create a new environment using environment.yml or install the libraries using pip (if you prefer not to use Anaconda Platform)

```
cd tellmewhy 
conda env create -f environment.yml 
```

## Launch JupyterLab

```
conda activate tellmewhy
jupyter lab
```
