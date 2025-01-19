# Customer Churn Prediction with AWS Sagemaker

This repository provides a framework for predicting customer churn using AWS Sagemaker. The solution encompasses data preprocessing, model training, deployment, and monitoring within the AWS environment.

## Table of Contents

1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Workflow](#workflow)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [Folder Structure](#folder-structure)
7. [Technologies](#technologies)
8. [License](#license)

## Overview

Customer churn prediction involves identifying customers who are likely to discontinue using a service or product. This project leverages AWS Sagemaker to create a cloud-based pipeline for predicting churn using machine learning models.

## Key Features

- End-to-end machine learning pipeline for churn prediction.
- Scalable and efficient model training using AWS Sagemaker.
- Deployment of a real-time prediction endpoint.
- Automated workflows for data preprocessing and model evaluation.
- Monitoring tools for performance tracking.

## Workflow

The project follows these key steps:

1. **Data Preparation**: Upload raw customer data to AWS S3 and preprocess it for model training.
2. **Model Training**: Use AWS Sagemaker to train machine learning models.
3. **Evaluation**: Assess model performance using appropriate metrics.
4. **Deployment**: Deploy the trained model as a scalable endpoint for real-time predictions.
5. **Monitoring**: Utilize AWS monitoring tools for ongoing performance tracking and updates.

## Setup and Installation

### Prerequisites

- AWS account with necessary permissions for Sagemaker and S3.
- Python and pip installed locally.
- AWS CLI configured with your credentials.

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/niyathnair/Customer_churn_AWS_SAGEMAKER.git
