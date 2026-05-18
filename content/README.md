---
hide:
  - toc
---
# Cloudera AI MLOps Hands on Lab - Bank Marketing ML Lab

Welcome to the Cloudera AI MLOps Hands on Lab. This lab teaches you the **complete machine learning operations (MLOps) lifecycle** using a real-world bank marketing prediction scenario using _Cloudera AI data service_.

!!! tip "Update Lab Guide for your assigned username"
    By entering your assigned username (e.g. `user001`) and clicking the **UPDATE EXAMPLES** button, the code examples you'll be customized for your user. 
    
    Click the reset button to start again if you make a mistake.
    
    <div class="username-input-container">
        <input type="text" id="user-username-input" placeholder="e.g., john.doe">
        <button id="user-username-save">UPDATE EXAMPLES</button>
        <button id="user-username-clear">RESET</button>
    </div>

    ```sql title="Test Block"
    changed_user=USERNAME;
    ```

    `changed_user=USERNAME;`

**Learning Objects**

* How production ML systems work
* ML Lifecycle Management
* Production Monitoring
* Automated MLOps
* Industry Best Practices

!!! info "Lab Environment Requirements"
    Before you start, ensure you have:

    - [ ] Access to a Cloudera AI workspace
    - [ ] Python 3.10+ runtime available
    - [ ] ~500MB disk space for data and models
    - [ ] Terminal/command line access
    - [ ] Basic familiarity with Python (helpful but not required)

## Modules

<div class="grid cards"  markdown>

- :material-library:{ .lg .middle } &nbsp; **Prerequisites: Understanding ML Evaluation Metrics**

    ***
    Familiarize yourself with the metrics you'll be tracking throughout the lab exercises.

    _**:octicons-clock-16:**_ 15-20 minutes
    ***

    **Key Metrics**

    - [ ] F1 Score
    - [ ] ROC-AUC
    - [ ] Accuracy
    - [ ] Precision
    - [ ] Recall

    ***

    [:octicons-arrow-right-24: View ML Evaluation Metrics Presentation](assets/ML_Evaluation_Metrics_Final.pdf){target="_blank"}

</div>

<div class="grid cards"  markdown>

- :material-rocket:{ .lg .middle } &nbsp; **Module 1. Complete ML Workflow**

    ***
    Build an end-to-end ML pipeline from raw data to production

    _**:octicons-clock-16:**_ 45-90 minutes
    ***

    **Goals**

    - [ ] Data Ingestion: Load bank marketing data
    - [ ] Exploratory Analysis: Understand patterns and trends
    - [ ] Model Training: Build models with MLflow
    - [ ] Model Deployment: Deploy best model as API
    - [ ] Inference Pipeline: Generate customer predictions

    ***

    [:octicons-arrow-right-24: Go to Module 1](modules/module1/README.md)

- :material-chart-bar:{ .lg .middle } &nbsp; **Module 2. Proactive Monitoring**

    ***
    Learn to detect when models degrade in production

    _**:octicons-clock-16:**_ 30-45 minutes
    ***

    **Goals**

    - [ ] Track predictions over time
    - [ ] Monitor accuracy across periods
    - [ ] Detect degradation when performance drops
    - [ ] Alert when intervention needed

    ***

    [:octicons-arrow-right-24: Go to Module 2](modules/module2/README.md)

- :material-refresh:{ .lg .middle } &nbsp; **Module 3. Automated Retraining Loop**

    ***
    Learn to automate the entire MLOps lifecycle

    _**:octicons-clock-16:**_ 60-90 minutes
    ***

    **Goals**

    - [ ] Detect drift using Evidently AI
    - [ ] Acquire labels for drifted data
    - [ ] Retrain model with historical and new data
    - [ ] Deploy automatically when performance improves

    ***

    [:octicons-arrow-right-24: Go to Module 3](modules/module3/README.md)

- :octicons-package-24:{ .lg .middle } &nbsp; **Module 4. ONNX Model Conversion & Deployment**

    ***
    Convert and deploy models in production-optimized format

    _**:octicons-clock-16:**_ 15-30 minutes
    ***

    **Goals**

    - [ ] Convert sklearn models to ONNX format
    - [ ] Register ONNX models in MLflow
    - [ ] Deploy optimized models to Cloudera AI Inference
    - [ ] Support mixed numerical and categorical features

    ***

    [:octicons-arrow-right-24: Go to Module 4](modules/module4/README.md)

</div>
