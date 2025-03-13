# Cancer Detection System for Whole Slide Images

This project provides an end-to-end solution for detecting cancer in whole slide images (WSIs) using deep learning. The system handles the entire pipeline from data collection and preprocessing to model training, validation, and deployment in a cloud environment.

## Features

- Data collection and preprocessing pipeline for whole slide images
- Advanced deep learning models for cancer detection
- Comprehensive model validation and performance metrics
- REST API for model inference
- Airflow workflows for automated training and deployment
- Kubernetes-based scalable architecture
- GCP integration for cloud deployment and storage


The system follows a microservices architecture with the following components:

1. **Data Processing**: Handles WSI data collection, tiling, normalization, and augmentation
2. **Model Training**: Implements various deep learning architectures with distributed training
3. **Model Validation**: Performs extensive cross-validation and reports performance metrics
4. **Inference API**: REST API for real-time cancer detection on WSIs
5. **Workflow Orchestration**: Airflow DAGs for automating the entire pipeline
6. **Cloud Deployment**: Kubernetes deployment on GCP with scalability

## Prerequisites

- Python 3.8+
- Docker and Docker Compose
- kubectl
- Google Cloud SDK
- Access to a GCP project with necessary APIs enabled



## License

MIT

## Citation

If you use this project in your research, please cite:

```
@software{cancer_detection_system,
  author = {Binbin Su},
  title = {Cancer Detection System for Whole Slide Images},
  year = {2025},
  url = {https://github.com/q138ben/cancer-detection-system}
}
```
