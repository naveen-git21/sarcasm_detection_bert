# Sarcasm Detection with BERT

This repository contains code and data for a sarcasm detection project using a BERT model. The notebook `sarcasm_bert.ipynb` trains and evaluates a BERT model to classify headlines as sarcastic or not, using the provided dataset.

## Files

- **sarcasm_bert.ipynb**: Jupyter notebook with the full model pipeline.
- **Sarcasm_Headlines_Dataset_v2.json**: JSON file containing the dataset for sarcasm detection.

## Instructions

### 1. Clone the Repository and Open in VSCode

```bash
git clone https://github.com/naveen-git21/sarcasm_detection_bert.git
```

Open the folder in Visual Studio Code.

### 2. Create a Virtual Environment
In the terminal, create a virtual environment to manage dependencies:
for windows
```bash
python3 -m venv venv
```

Activate the virtual environment:
```bash
.\venv\Scripts\activate
```
For MacOS/Linux:
```bash
source env/bin/activate
```
### 3. Install Required Libraries
With the virtual environment activated, install the required libraries:
```bash
pip install torch transformers sklearn pandas numpy matplotlib seaborn requests beautifulsoup4 huggingface_hub
```

### 4. Set Up Hugging Face Token
In sarcasm_bert.ipynb, replace #YOUR_HUGGING_FACE_TOKEN# with your personal Hugging Face token to access the BERT model.

### 5. Running the Model Training
The model training will take up to 6 hours. Run each cell in the notebook one by one and monitor the outputs.

### 6. Scraping Part
For the web scraping section in the notebook:

Use your preferred website.
Replace the relevant class names and HTML tags to match your target site’s structure.

