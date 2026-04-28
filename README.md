Uncertainty-Calibrated Transformer Framework for Lumbar Spondylosis Assessment

* Project Overview

This project presents a deep learning-based system for automated diagnosis of lumbar spondylosis from lateral lumbar spine X-ray images. The framework leverages a Swin Transformer backbone, multi-task learning, and uncertainty estimation to provide clinically relevant and reliable predictions.
The system is designed to assist radiologists by offering:

Severity classification (Normal, Moderate, Severe)
Quantitative disc height estimation
Osteophyte detection
Prediction confidence with uncertainty awareness

* Abstract

Lumbar spondylosis is a common degenerative spinal condition that significantly affects quality of life. Traditional diagnosis from X-ray images is manual, subjective, and time-consuming.

This project proposes an uncertainty-calibrated multi-task learning framework using a Swin Transformer architecture for automated lumbar spondylosis assessment. The model integrates quantitative feature extraction from vertebral landmarks with deep learning-based feature representation to improve diagnostic accuracy.

Additionally, an uncertainty estimation module is incorporated to enhance clinical reliability by identifying low-confidence predictions. Experimental results demonstrate that the proposed approach achieves competitive classification performance and superior regression accuracy compared to conventional CNN-based models.

Features
🧩 Multi-task learning (classification + regression + detection)
🧠 Transformer-based feature extraction (Swin Transformer)
📏 Quantitative disc gap computation
⚠️ Uncertainty-aware predictions
🔍 Explainability using Grad-CAM
📊 Comparison with CNN baselines (VGG16, DenseNet121, Custom CNN)

Setup Instructions
Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Create Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate      # Linux / Mac
venv\Scripts\activate         # Windows
Install Dependencies
pip install -r requirements.txt

If requirements.txt is not available, install manually:

pip install torch torchvision transformers timm opencv-python matplotlib scikit-learn
Run the Project

Open the notebook:

jupyter notebook main.ipynb

Then run all cells to:

preprocess data
train model
evaluate results

Outputs
Classification results (Accuracy, Confusion Matrix)
Regression results (MSE)
ROC curves
Grad-CAM visualizations
Model comparison graphs
