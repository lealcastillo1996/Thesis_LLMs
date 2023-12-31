Jose Enrique Leal Castillo SN:9066381



# Title: "Investigating Open Source Transformer Techniques for Question Answering Systems on Cloud Domain: A Comparison with ChatGPT3.5-Turbo"

- **First examiner:** Ioannis Velegrakis
- **Second examiner:** Enas Khwaileh
- **Candidate:** José Enrique Leal Castillo
- In cooperation with:SUE B.V. June 29, 2023".

![d1920023e9990675e99e91369cf12dc9.png](https://imgtr.ee/images/2023/06/30/d1920023e9990675e99e91369cf12dc9.png)

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

##Working Calendar

The proposed working schedule is:
<style>
table {
  font-size: 30px;
}
</style>
| Week| Task|Description|State|
| -------- | -------- |  -------- | -------- |
| Week 1 | **Project initial meeeting** |The first steps in the project will involve discussing the scope and conducting a comprehensive literature review to identify key considerations and potential challenges. |Done ✅
| Week 2|  **Data collection**   | Since there is no readily available dataset, the data will be collected via web scraping from the documentation available at https://kubernetes.io/.| Done ✅
| Week 3|  **Open Book QA algorithm development**   | Different techniques for the Open Book QA algorithm will be explored and implemented in code.| Done ✅
| Week 4|  **Test dataset and evaluation framework development**   | A synthetic test dataset will be generated and different metrics will be proposed to evaluate the results.| Done ✅
| Week 5|  **manual labeling of results at SUE**   | An API and possible interactive dashboard will be developed meanwhile SUE labels the results of different models to evaluate with human feedback.| Done ✅
| Week 6|  **Evaluation metrics and Results visualization**   | Evaluation of the models will be conducted, Result visualization code will be developed.| Done ✅
| Week 7|  **Final feedback implementations and code documentation / Paper literature review and introduction**   | Feedback from the implementation will be added to thee project and code documentationn will be done, the paper writing initial part will be started .| Done ✅
| Week 8|  **Paper Methodology and Results**   | .| Done ✅
| Week 9|  **Paper Critical discussion and Conclusion**   | .| Done ✅
| Week 10|  **Paper format review / Final corrections**   | .| Done ✅
