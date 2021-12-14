# articles_classification
A Kaggle project focused on classifying scientific articles based on their abstract. The link to the Kaggle project: 
https://www.kaggle.com/vetrirah/janatahack-independence-day-2020-ml-hackathon

## Files and folders:
- Articles Data: train.csv (traininig data), test.csv (testing data), train_data.csv (dataset prepared for training)
- distilbert_1 - HF model checkpoint of the Distilbert model
- tokenizer_distilbert_1 - HF Tokenizer for the model
- EDA.ipynb - Jupyter Notebook with the Exploratory Data Analysis
- Articles_NLP_distilbert.ipynb - Jupyter Notebook with the model fine-tuning and evaluation

## Results:
After the first iteration of fine-tuning the <strong>distiblert-base-uncased</strong> model from the HuggingFace model hub, the model achieve ~87% of accurcy on the test data. The first iteration did not empoyed any custom data cleaning and preprocessing steps -- only tokenizer and label encoding.
