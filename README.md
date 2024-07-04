# Automatic Image Captioning Project

## Overview
This project implements an automatic image captioning system using a CNN-RNN encoder-decoder architecture. It was developed as part of the Deep Learning course (CS60010) , under the guidance of Prof. Pawan Goyal.

## Project Structure
- `Project.ipynb`: Jupyter notebook containing the CNN-LSTM model implementation
- `report.pdf`: Project report detailing methodology and results

## Model Architecture
- Encoder: CNN based on pre-trained ResNet-50


## Dataset
The model was trained and evaluated on the dataset provided in the course materials.

## Evaluation Metrics
- ROUGE-L
  - Precision: 0.35
  - Recall: 0.189
  - F-measure: 0.246

## Running the Code
1. Ensure you have the required dependencies installed (list them here, e.g., PyTorch, torchvision, etc.)
2. Open the Jupyter notebook `team_id_15_a.ipynb`
3. Run all cells in order

## Additional Information
- The model is designed to run within the 15GB GPU limit of Google Colab's free tier.
- Pre-trained encoders were used and fine-tuned on the provided training set.

## Acknowledgements
We would like to thank Prof. Pawan Goyal for his guidance throughout this project.
