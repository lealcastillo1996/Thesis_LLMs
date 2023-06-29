Jose Enrique Leal Castillo SN:9066381

# Title: "Investigating Open Source Transformer Techniques for Question Answering Systems on Cloud Domain: A Comparison with ChatGPT3.5-Turbo

- **First examiner:** Ioannis Velegrakis
- **Second examiner:** Enas Khwaileh
- **Candidate:** José Enrique Leal Castillo
- In cooperation with:SUE B.V. June 29, 2023".

Goal: This study aims to examine and compare the performance of different transformer methods, specifically Extracted Pre-trained Transformer (EPT), Generative Pre-trained Transformer (GPT), and Text-to-Text Transfer Transformer (T5), in a real-world Question Answering (QA) task. Furthermore, it seeks to analyze the impact of varying the size of the input context on the quality of responses generated by each model. This research endeavors to contribute to the advancement of QA systems and furnish valuable insights into the factors influencing their performance. By combining human expertise and machine learning-based scoring, it strives to offer meaningful findings and enhance our comprehension of QA systems.

## Research question:

RQ1: Which OS transformer method, EPT, GPT, or T5, demonstrates superior performance when answering the proposed domain questions in overall and by each type of question?

RQ2: Can any of the studied OS transformer techniques compete in terms of performance with ChatGPT3.5-Turbo when answering the proposed domain questions in general and by each kind of question?

RQ3: Is increasing the size of the input context always beneficial for each method in terms of performance?

## Description

The selected domain for simulating a real-world QA task is cloud computing, focusing on questions related to Kubernetes technology. The QA system uses the entire Kubernetes public documentation, enriched by real-time searches on Google, as its primary source of knowledge. To evaluate the performance of each approach, a self-proposed Machine-trained evaluation score (MTES) called estimated human label (EHL) is computed using a Machine Learning (ML) classification model. This model is trained using N-gram-based metrics, which analyze continuous sequences of n words. Additionally, human experts labeled a self-proposed, carefully balanced dataset that encompasses diverse question categories, including close-ended, open-ended, conceptual, situational, command-based, comparative, procedural, and multiple-answer questions. This research endeavors to contribute to the advancement of QA systems powered by OS models and furnish valuable insights into the factors influencing their performance. By combining human expertise and a MTES, it strives to offer meaningful findings and improve our comprehension of QA systems.


## Data:

- Data retrieve from Kubernetes documentation + live search in google
Context retrieve methods:

- Sentence Embeddings cosine similiraty
Data proccesing variables:

- Chunk size [1000,2000,4000,8000]

- Number of chunks to the context [1,3,5,10]

## Models:

1.- Deep Set: RoBERTa-base-Squad2
2.- Google: Flan-t5-xl
3.- Nomic AI: GPT4All-LoRa (7B)
4 .-Open AI: ChatGPT 3.5-turbo

## Methodology

QA SYSTEM

QA EVALUATION


