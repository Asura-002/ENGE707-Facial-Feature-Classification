# ENGE707 Facial Feature Classification

This project classifies cat and dog facial features into eight classes using an ImageNet-pretrained EfficientNet-B0 model.

## Target Classes

- CatEye
- CatFace
- CatMouth
- CatNose
- DogEye
- DogFace
- DogMouth
- DogNose

## Project Structure

- `notebooks/01_dataset_exploration.ipynb` — dataset exploration and quality checks
- `notebooks/02_preprocessing.ipynb` — preprocessing, augmentation and data loaders
- `notebooks/03_model_training.ipynb` — model development, training and evaluation
- `notebooks/04_kaggle_submission.ipynb` — test prediction and Kaggle submission generation
- `outputs/figures/` — generated figures
- `outputs/evidence/` — Kaggle submission evidence
- `submissions/` — final Kaggle CSV file
- `requirements.txt` — Python package versions

## Setup

Create and activate a virtual environment, then install the required packages:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
