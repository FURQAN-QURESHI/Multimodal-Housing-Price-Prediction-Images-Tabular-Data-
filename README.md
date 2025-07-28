Multimodal Housing Price Prediction (Images + Tabular Data)
Objective
Predict house prices using both tabular features (e.g., bedrooms, area) and house images (feature extraction with a pre-trained CNN).

Workflow
Dataset: Real Estate Image Dataset (mistag) or your Hugging Face alternative

Tabular Preprocessing: Select and scale numerical features.

Image Features: Extracted using pre-trained ResNet18 (torchvision), no CNN training.

Feature Fusion: Concatenate image and tabular features.

Model: Random Forest Regressor on combined features.

Evaluation: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE).

How to Run
Download and extract the dataset. Ensure images and CSV are in the right folders.

Install requirements:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook/script.

Results
MAE: (your value)

RMSE: (your value)

Repository Structure (Example)
Copy
Edit
/
├── task1_news_classifier/
│   ├── notebook.ipynb
│   ├── streamlit_app.py
│   └── requirements.txt
├── task2_churn_pipeline/
│   ├── notebook.ipynb
│   └── requirements.txt
├── task3_multimodal_housing/
│   ├── notebook.ipynb
│   └── requirements.txt
└── README.md
Notes
Edit the results sections with your actual metric values.

Each task folder should contain the code, data download links, and a mini-README if needed.

For Task 1 and Task 3, you may need a GPU/cloud runtime for full-scale experiments.

