# Planned content of doctoral thesis
## Working Title: _Human Evaluation Methods for Cluster Interpretation_
### Abstract
Document clustering is widely used to identify patterns within large text corpora. Clustering is typically performed in an unsupervised setting, where the quality of clusters depends on the application context. In my work, I utilized a BERTopic pipeline that employs language models such as BERT or Sentence-T5 to embed documents, clustering them based on vector distances (Paper IV). A key challenge in document clustering lies in its evaluation: clusters are only useful if they are interpretable by humans, whose judgments are shaped by personal experience and knowledge, making it difficult to establish a definitive ground truth. Nonetheless, effective evaluation methods are essential in both research and industrial applications, leading to a need for approaches that integrate human judgment and is flexible to specific application goals.

This thesis revolves around a novel method for human cluster evaluation called CIPHE (Paper II), which was developed as a response to the industry needs of contextual advertisement (Paper I). CIPHE focuses on humans interpreting samples of raw document texts rather than abstractions, hypothesizing that this approach provides more reliable cluster characterization. CIPHE was used to study the limitations that keyword-based methods pose on the evaluation of topic models (Paper III). We found that the human interpretation of keywords differs from the interpretation of the full text, which support criticism towards topic coherence metrics not being able to capture the complex nuances of human intepretation. 

Additionally, in Paper V, we also discuss efficient human-in-the-loop validation of document classifiers. We proposed to create acceptance criteria through statements for human evaluators to assess, which can aid them in aligning their judgment with the application goal.

### Papers included in the thesis
1. [Topic Modeling by Clustering Language Model Embeddings: Human Validation on an Industry Dataset](https://aclanthology.org/2022.emnlp-industry.65/) (Eklund & Forsman, EMNLP 2022)
2. [CIPHE: A Framework for Document Cluster Interpretation and Precision from Human Exploration](https://aclanthology.org/2024.nlp4dh-1.52) (Eklund et al., NLP4DH 2024)
3. [Comparing Human-Perceived Cluster Characteristics through the Lens of CIPHE: Measuring Coherence beyond Keywords](https://doi.org/10.5281/zenodo.14622380) (Eklund et al., Submitted JDMDH 2025)
4. [An Empirical Configuration Study of a Common Document Clustering Pipeline](https://aclanthology.org/2023.nejlt-1.7/) (Eklund et al., NEJLT 2023)
5. [Industry Quality Control for Efficient Continuous Human Validation of Deployed Text Classification Systems](https://drive.google.com/file/d/1rgjWHL20X1ZWFAN1KSEo7s2WeOpdhBvq/view?usp=sharing) (Eklund et al., Submitted 2025)



### Other work
1. [PromptStream: Self-Supervised News Story Discovery Using Topic-Aware Article Representations](https://aclanthology.org/2024.lrec-main.1157/) (Hatefi et al., LREC-COLING 2024)
2. [Developing a Multilingual Corpus of Wikipedia Biographies](https://aclanthology.org/2023.ranlp-1.32/) (Devinney et al., RANLP 2023)
