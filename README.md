# Multilingual Sentence Classification from Scratch

## Introduction
This assignment involves building an end-to-end system for text classification in a multilingual setting. The task revolves around identifying the framing of sentences in various languages related to social issues like immigration and same-sex marriage. The assignment encompasses understanding the task specification, collecting and annotating data, training and testing models, and finally deploying the system.

## Task Specification
The task involves identifying the framing of sentences related to social issues in several languages. Framing refers to emphasizing certain aspects of perceived reality in communication texts. The input is a text file with sentences, and the output should be a .tsv file with corresponding labels.

## Data Collection
Data collection involves two rounds of annotation: one by the student and another by two classmates. The data is sourced from various sources, including web scraping and language model experimentation. Annotators label sentences based on predefined framing dimensions.

### Data Source Description
Unlabeled data is gathered from various sources using commands to a language model. Web scraping and manual search for relevant articles, books, and websites contribute to data collection. 150 sentences are chosen for annotation, covering a wide range of topics.

## Model Training and Testing
A text classification model is trained using the collected data. Hyperparameters are fine-tuned to achieve optimal performance. The model is evaluated on the validation and test sets to measure accuracy.

## Running the Python File on Google Colab

To run the Python file on Google Colab, follow these steps:

1. Open Google Colab: Go to [Google Colab](https://colab.research.google.com/).
2. Upload Python File: Upload your Python file to Google Colab by clicking on "File" > "Upload Notebook" or by dragging and dropping the file into the Colab interface.
3. Mount Google Drive (Optional): If your Python file requires access to files stored in Google Drive, you can mount Google Drive by running the following code in a code cell:

```python
from google.colab import drive
drive.mount('/content/drive')
```
## Run Python File
```python
Multi_sentence.ipynb
```

## Data Augmentation
Data augmentation techniques are employed to increase the diversity and size of the training dataset. Techniques include automatic translation, paraphrasing, and label propagation. The augmented data is used to train and evaluate the model.

## Developed a Robust Multilingual Sentence Categorization Model
Our project focused on developing a robust multilingual sentence categorization model, with a specific emphasis on frame recognition within text paragraphs. Key highlights of our approach include:

### Comprehensive Task Execution: 
We executed comprehensive tasks, including data collection, cleaning, annotation, model selection, and training from scratch. This involved gathering raw data, annotating it based on predefined framing dimensions, and generating a labeled .tsv file for model training.

### Utilization of Spacy and Hugging Face Transformers: 
We leveraged advanced NLP tools such as Spacy and Hugging Face Transformers for model refinement. By integrating these libraries, we enhanced the accuracy and performance of our model across diverse languages.

### Integration of Google Translate API: 
To facilitate cross-language analysis and data augmentation, we integrated the Google Translate API into our workflow. This enabled automated translation of text data, allowing for seamless analysis and training across multiple languages.


## Conclusion

This project represents a comprehensive effort to develop a robust multilingual sentence categorization model, focusing on frame recognition within text paragraphs. Through extensive tasks including data collection, cleaning, annotation, model selection, and training from scratch, we have successfully created a labeled .tsv file for model training. Leveraging Spacy and Hugging Face Transformers for model refinement has enhanced accuracy and performance across diverse languages. Integration of the Google Translate API for automated translation during data augmentation has facilitated cross-language analysis. This README serves as a guide to understand the project's objectives, methodologies, and outcomes. We hope this work contributes to the advancement of text classification in multilingual contexts.

