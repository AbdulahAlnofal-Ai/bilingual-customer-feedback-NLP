# Bilingual Customer Feedback Analysis Using NLP

A bilingual English-Arabic Natural Language Processing (NLP) project that analyzes customer feedback using sentiment classification, complaint and praise theme extraction, AI-powered summarization, and a conversational chatbot.

## Project Overview

This project transforms customer reviews into useful insights through pretrained language models and an interactive Gradio dashboard.

## Key Features

- **Bilingual Sentiment Analysis:** Classifies English and Arabic customer feedback.
- **Complaint Analysis:** Identifies common issues such as delivery, customer service, product quality, and pricing.
- **Praise Analysis:** Highlights positive themes such as food quality, friendly staff, and value for money.
- **AI Summarization:** Uses BART to summarize positive and negative reviews.
- **Conversational Chatbot:** Uses TinyLlama to answer questions about customer feedback.
- **Interactive Dashboard:** Presents sentiment charts, feedback themes, summaries, and chatbot interactions.

## Models Used

| Model | Purpose |
|---|---|
| DistilBERT | English sentiment classification |
| CAMeLBERT | Arabic sentiment classification |
| BART | Customer feedback summarization |
| TinyLlama | Conversational chatbot |

## Datasets

- **Yelp Academic Dataset:** English customer reviews.
- **Arabic Sentiment Twitter Corpus:** Arabic sentiment data.

The notebook processes a selected subset of these datasets.

## Technologies

Python, Pandas, NumPy, PyTorch, Hugging Face Transformers, Gradio, Matplotlib, Seaborn, NLTK, and Deep Translator.

## Project Workflow

1. Download and load the datasets.
2. Clean and prepare English and Arabic text.
3. Classify feedback sentiment.
4. Extract complaint and praise themes.
5. Generate positive and negative feedback summaries.
6. Build the chatbot context.
7. Display results in an interactive dashboard.

## Run the Project

1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Configure your Kaggle API credentials.
4. Open `nlp-proj-final-v2.ipynb` in Jupyter Notebook or Google Colab.
5. Run the notebook cells in order.

A Kaggle account is required to download the datasets. A GPU is recommended for faster model inference.

## Demo

Watch the project demonstration in the [`demo/README.md`](demo/README.md) file.

## Repository Structure

```text
bilingual-customer-feedback-NLP/
├── README.md
├── PROJECT_STRUCTURE.md
├── nlp-proj-final-v2.ipynb
├── requirements.txt
├── .gitignore
├── docs/
│   └── README.md
└── demo/
    └── README.md
```

## Limitations

The results depend on the datasets and pretrained models. Theme extraction relies on keyword matching, and chatbot responses may not always be accurate. Model downloads and inference can require substantial storage and processing time.

## License

This repository is provided for educational and research purposes. Refer to the original dataset and pretrained model licenses before redistributing their contents or weights.
