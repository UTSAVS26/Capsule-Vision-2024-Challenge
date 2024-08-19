# Capsule Vision 2024 Challenge

## Overview

The Capsule Vision 2024 Challenge involves developing AI models for the automatic classification of abnormalities in video capsule endoscopy (VCE) video frames. The goal is to create a vendor-independent and generalized AI model capable of classifying ten different types of abnormalities.

This repository contains the code, documentation, and resources for our participation in the Capsule Vision 2024 Challenge. The project includes data preprocessing, model training, evaluation, and submission scripts.

## Team

- **Utsav Singhal**: Main Lead and Project Coordinator
- **Serra Aksoy**: Training and Evaluating Models
- **Anshul Bansal**: Data Preprocessing

## Project Structure

The repository is organized as follows:

```
capsule-vision-2024-challenge/
├── data/               # Data files (Training, Validation, Testing datasets)
├── notebooks/          # Jupyter notebooks for exploration and experimentation
├── src/                # Source code for data preprocessing, model training, and evaluation
│   ├── data_preprocessing.py  # Scripts for data cleaning and preprocessing
│   ├── model_training.py      # Scripts for model training
│   ├── model_evaluation.py    # Scripts for model evaluation
│   └── utils.py               # Utility functions
├── tests/              # Unit tests and validation scripts
├── requirements.txt    # Python dependencies
├── .gitignore          # Git ignore file
└── README.md           # Project overview and instructions
```

## Installation

To set up the project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/capsule-vision-2024-challenge.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd capsule-vision-2024-challenge
   ```

3. **Install Dependencies:**

   Make sure you have `pip` installed. Then, install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Data

### Training and Validation Data

The training and validation datasets are accessible [here](https://figshare.com/articles/dataset/Training_and_Validation_Dataset_of_Capsule_Vision_2024_Challenge/26403469).

### Testing Data

The test dataset will be released on October 11, 2024.

## Usage

### Data Preprocessing

Preprocess the data using the following script:

```bash
python src/data_preprocessing.py
```

### Model Training

Train the model using the following script:

```bash
python src/model_training.py
```

### Model Evaluation

Evaluate the trained model using:

```bash
python src/model_evaluation.py
```

## Contact

For any queries, please contact: [ask.misahub@gmail.com](mailto:ask.misahub@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
