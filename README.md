# End-to-End Data Science Project: Wine Quality Prediction

## Overview
This project focuses on building an end-to-end machine learning pipeline for predicting wine quality. It encompasses data ingestion, validation, transformation, model training, and evaluation, ensuring a robust and scalable solution.

---

## Workflows

### ML Pipeline
1. **Data Ingestion**: Collection of raw data for analysis.
2. **Data Validation**: Ensuring the integrity and quality of the data.
3. **Data Transformation**: Feature engineering and preprocessing.
4. **Model Trainer**: Building and training machine learning models.
5. **Model Evaluation**: Utilizing MLflow and DagsHub for tracking and evaluation.

### Project Steps
- **Update `config.yaml`**: Configure general project settings.
- **Update `schema.yaml`**: Define data schema and validation rules.
- **Update `params.yaml`**: Specify hyperparameters and other model settings.
- **Update Entity Layer**: Create entities for structured project management.
- **Update Configuration Manager**: Manage configuration in the `src/config` directory.
- **Update Components**: Implement components for different pipeline stages.
- **Update Pipeline**: Integrate components into a seamless pipeline.
- **Update `main.py`**: Orchestrate the end-to-end execution.

---

## Technologies and Tools Used
- **Flask API**: For deploying the model as a web application.
- **Git and GitHub**: Version control and collaboration.
- **DagsHub**: Repository for data and model versioning.
- **MLflow**: Model tracking and management.

---

## Directory Structure
```plaintext
src/
  ├── config/           # Configuration files and managers
  ├── components/       # Core pipeline components
  ├── pipelines/        # End-to-end pipeline scripts
  └── main.py           # Main script for pipeline execution
config.yaml             # General configuration settings
schema.yaml             # Data schema definitions
params.yaml             # Model hyperparameters
