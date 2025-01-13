# Planned content of doctoral thesis
## Working Title: _Human Evaluation Methods for Cluster Interpretation_
### Abstract
Document clustering is used to discover patterns in large corpora of documents. Clustering is often done in an unsupervised setting, where the application environment of the clustering model determines whether the quality of the clusters are adequate. Throughout my work, I made use of a BERTopic pipeline where a language model such as BERT or Sentence-T5 embeds documents, which are subsequently clustered based on the vector distances (Paper IV). One particurlar problem that arise in the document clustering domain is in the evaluation. The resulting clusters are only valuable if a human viewing them can interpret the theme and characteristics. This interpretation grounds itself in personal experience and knowledge, leading to difficulties in establishing a definitive ground truth. Still, for many applications, such as in research and industry, clustering models needs to be properly evaluated in their application environment. This leads to a need for evaluation methods that make use of human judgement and is flexible to the application goal.

This thesis revolves around a novel method for human cluster evaluation called CIPHE (Paper II), which we developed through the industry needs of contextual advertisement (Paper I). CIPHE builds on humans digesting samples of the raw document texts instead of abstractions which is hypothesised to give a reliable characterization of clusters. CIPHE is used to study the limitations that keyword-based methods pose on the evaluation of topic models (Paper III). We found that the interpretation from humans reading keywords is skewed compared to when they read the full text, and also support criticism towards topic coherence metrics not capturing the complex nuances of human intepretation. Further, in Paper V, we also discuss efficient human-in-the-loop classifier validation and how to create acceptance criteria through statements for human evaluators to assess. 

### Papers included in the thesis
1. [Topic Modeling by Clustering Language Model Embeddings: Human Validation on an Industry Dataset](https://aclanthology.org/2022.emnlp-industry.65/) (Eklund & Forsman, EMNLP 2022)
2. [CIPHE: A Framework for Document Cluster Interpretation and Precision from Human Exploration](https://aclanthology.org/2024.nlp4dh-1.52) (Eklund et al., NLP4DH 2024)
3. [Comparing Human-Perceived Cluster Characteristics through the Lens of CIPHE: Measuring Coherence beyond Keywords](https://doi.org/10.5281/zenodo.14622380) (Eklund et al., Submitted JDMDH 2025)
4. [An Empirical Configuration Study of a Common Document Clustering Pipeline](https://aclanthology.org/2023.nejlt-1.7/) (Eklund et al., NEJLT 2023)
5. [Industry Quality Control for Efficient Continuous Human Validation of Deployed Text Classification Systems](https://drive.google.com/file/d/1rgjWHL20X1ZWFAN1KSEo7s2WeOpdhBvq/view?usp=sharing) (Eklund et al., Submitted 2025)



### Other work
1. [PromptStream: Self-Supervised News Story Discovery Using Topic-Aware Article Representations](https://aclanthology.org/2024.lrec-main.1157/) (Hatefi et al., LREC-COLING 2024)
2. [Developing a Multilingual Corpus of Wikipedia Biographies](https://aclanthology.org/2023.ranlp-1.32/) (Devinney et al., RANLP 2023)
