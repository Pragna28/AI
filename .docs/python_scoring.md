# Azure services for deploying Python ML

<p align="center">
  <img width="800" src="../images/decision_python_scoring.png" alt="Decision matrix for Python scoring on Azure">
</p>

When deploying machine learning models in Python, your recommended Azure service depends on whether you need real-time or batch scoring, and whether you are using deep learning or classical ML. 

Use the matrix below to find the right service and tutorial for your workload:

| Model Type | Real-Time Scoring | Batch Scoring |
| :--- | :--- | :--- |
| **Deep Learning** | **AKS (with GPUs)**<br>👉 [View Tutorial](https://github.com/Microsoft/AKSDeploymentTutorialAML) | **AzureML Pipelines (with GPUs)**<br>👉 [View Tutorial](https://github.com/Azure/Batch-Scoring-Deep-Learning-Models-With-AML) |
| **Classical ML** | **AKS (CPU only)**<br>👉 [View Tutorial](https://github.com/Microsoft/MLAKSDeployAML) | **AzureML Pipelines (CPU only)**<br>👉 [View Tutorial](https://github.com/Microsoft/AMLBatchScoringPipeline) |
