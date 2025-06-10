# text_summarizer.py

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: B.ASHWINI

*INTERN ID*:CT2MTDM1406

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH



## Task Description: Text Summarization Tool Using Natural Language Processing

### Overview

Text summarization is the process of automatically shortening a text document with the goal of creating a summary that retains the most important points of the original content. This is a significant area of research in the field of Natural Language Processing (NLP) and Artificial Intelligence (AI), as it plays a key role in reducing reading time, improving comprehension, and handling the overwhelming volume of digital information available today.

The aim of this project is to build a Python-based Text Summarization Tool that can take lengthy input articles and generate concise and meaningful summaries. The task involves understanding the core concepts of NLP, utilizing established Python libraries, and applying summarization techniques to produce readable and informative summaries.



### Objective

The main objective of this task is to:

* Create a Python tool that can accept a large piece of text as input.
* Analyze the input using NLP techniques.
* Output a concise summary highlighting the key points and main ideas of the original text.

The final deliverable should be a working Python script that runs in the terminal or command line, accepts input text from the user, and prints a clean, readable summary to the screen.



### Approach

There are two broad categories of text summarization:

1. **Extractive Summarization**: This method involves selecting important sentences, phrases, or paragraphs directly from the original text and stitching them together to form a summary. It does not alter the original text but picks the most relevant parts.

2. **Abstractive Summarization**: This method involves understanding the main ideas in the text and generating new sentences to express them. This approach is closer to how humans summarize and is more complex to implement.

For this task, we begin with **extractive summarization** due to its simplicity and effectiveness. The tool will use the `sumy` library in Python, which provides implementations of several summarization algorithms such as LSA (Latent Semantic Analysis), LexRank, and Luhn.

The script will utilize NLP techniques like tokenization (splitting text into words and sentences), stopword removal, and sentence ranking to identify the most important sentences in the input text.



### Technologies and Tools

* **Python**: The programming language used to implement the tool.
* **VS Code**: The development environment.
* **NLTK**: Natural Language Toolkit for tokenization and text processing.
* **Sumy**: A Python library for extractive text summarization.
* **Terminal Input**: The tool will accept text via standard input from the user.



### Features

* Accepts long text input from the user.
* Summarizes the text using LSA (Latent Semantic Analysis).
* Displays the summarized content in a clean and readable format.
* Easy to use and runs directly from the command line.



### Use Cases

* **Students** can use it to summarize lengthy articles and research papers.
* **Journalists** can quickly extract key points from long reports.
* **Professionals** can summarize emails, documents, or news.
* **Researchers** can use it as a base for developing more advanced summarization tools.



### Expected Outcome

The expected outcome is a working summarization tool that showcases the practical application of NLP in real-world problems. Users will be able to enter large texts and receive meaningful summaries that save time and improve efficiency. It also introduces learners to the foundational concepts of NLP and Python-based development.



