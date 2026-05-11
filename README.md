# NLP Taxonomy Development for Webinar Content

This repository is a sanitized version of my master's capstone project. For this project, I worked on an NLP-based taxonomy system for a library of 600+ webinar recordings. The goal was to process a large collection of webinar content, extract meaningful themes from the transcript data, and support the development of a controlled taxonomy for better metadata, content grouping, and retrieval.

The project was managed by Professor David Loshin and our client, Jimm Johnson, VP of Data Governance Professionals Organization (DGPO). My role involved helping process webinar recordings into transcript data, applying NLP techniques to analyze the content, and contributing to the taxonomy development process.

The final project was presented at the Data Governance & Information Quality (DGIQ) 2024 conference as an applied example of using NLP to support taxonomy development and data governance.

## Project Overview

The client had a large library of webinar recordings covering topics related to data governance, information quality, metadata, and related professional knowledge areas. Manually organizing and searching through this type of content can become difficult when the collection grows large.

To address this problem, our team built a workflow that used NLP techniques to process transcript data and identify recurring themes across the content. These results helped us organize the content into a more structured taxonomy.

The project combined text preprocessing, keyword extraction, frequency analysis, bigram analysis, and LDA topic modeling. From there, the team reviewed the results and organized them into a controlled taxonomy that could support cleaner metadata, better content grouping, and easier retrieval.

## Main Features

- Processing webinar recordings into transcript-style text data
- PDF and text conversion workflows
- Word counting and frequency analysis
- Keyword extraction
- Keyword search across documents
- Word cloud generation
- Bigram analysis
- LDA topic modeling
- Dataset merging
- Taxonomy development support

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK
- WordCloud
- Matplotlib
- PDF text extraction libraries
- Google Drive and Google Sheets APIs in the original private version

## Notebook Descriptions

### PDF_to_Text_Converter.ipynb

This notebook converts PDF files into text files so they can be used for NLP analysis later in the workflow.

### Word_counter.ipynb

This notebook counts word frequency across text files and helps identify which terms appear most often.

### word_cloud_and_keyword_extraction.ipynb

This notebook generates word clouds and extracts keywords from text documents.

### search_docs_by_keyword.ipynb

This notebook searches through a collection of documents and returns files that contain specific keywords.

### Searching_Bigram_Score_Algorithm.ipynb

This notebook analyzes common two-word combinations and scores bigrams based on how often or how meaningfully they appear.

### TopicModelling.ipynb

This notebook applies LDA topic modeling to identify recurring themes across a group of documents.

### Merging_Datasets.ipynb

This notebook combines multiple datasets into a cleaner structure for further analysis.

### Video_Transcription_to_Audio.ipynb

This notebook was part of the transcript-processing workflow connected to webinar/video-based content analysis.

## Privacy Note

This repository is a public, sanitized version of my master's capstone project. Before uploading it, I removed private datasets, credentials, Google Drive links, internal file paths, document names, generated outputs, and other sensitive information.

Some parts of the notebooks may contain [REDACTED] placeholders. These are intentional. They show where private paths, links, or project-specific information existed in the original version.
