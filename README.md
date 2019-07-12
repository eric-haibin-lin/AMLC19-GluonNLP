AMLC 2019: Dive into Deep Learning for Natural Language Processing
==================================================================

<h3>Time: Friday, July 12, 2019<br/>Location: Meeting Center 02.100, [2031 7th Ave, Seattle, WA 98121](https://goo.gl/maps/LHWeYRDMYPvNKw3n6)</h3>

<span style="color:grey">Presenter: Haibin Lin, Leonard Lausen, Xingjian Shi, Haichen Shen, He He, Sheng Zha</span><br/>

<a href="https://aws.amazon.com/"><img src="_static/aws_logo.png" alt="AWS Icon" height="45"></a> &nbsp; <a href="https://aws.amazon.com/"><img src="_static/amazon_ai.png" alt="AmazonAI Icon" height="58"></a> &nbsp; <a href="https://aws.amazon.com/sagemaker/neo/"><img src="_static/neo.png" alt="Neo Icon" height="58"></a> &nbsp; <a href="https://beta.mxnet.io/"><img src="_static/apache_incubator_logo.png" alt="Apache Incubator Icon" height="39"></a> &nbsp; <a href="https://beta.mxnet.io/"><img src="_static/mxnet_logo_2.png" alt="MXNet Icon" height="39"></a> &nbsp; <a href="https://gluon-nlp.mxnet.io/"><img src="_static/gluon_logo_horizontal_small.png" alt="Gluon Icon" height="42"></a> &nbsp; <a href="http://tvm.ai"><img src="_static/tvm.png" alt="TVM Icon" height="32"></a>

Abstract
--------

Deep learning has rapidly emerged as the most prevalent approach for training predictive models for large-scale machine learning problems. Advances in the neural networks also push the limits of available hardware, requiring specialized frameworks optimized for GPUs and distributed cloud-based training. Moreover, especially in natural language processing (NLP), models contain a variety of moving parts: character-based encoders, pre-trained word embeddings, long-short term memory (LSTM) cells, transformer layers, and beam search for decoding sequential outputs, among others.

This introductory and hands-on tutorial walks you through the fundamentals of machine learning and deep learning with a focus on NLP. We start off with a crash course on deep learning for NLP with [GluonNLP](https://gluon-nlp.mxnet.io/), covering data, automatic differentiation, and various model architectures such as convolutional, recurrent, and attentional neural networks. Then, we dive into how context-free and contextual representations help various NLP domains. Throughout the tutorial, we start off from the basic classification problem, and progress into how it can be structured to solve various NLP problems such as sentiment analysis, question answering, machine translation, and natural language generation. Finally, we demonstrate how we can deploy a state-of-the-art NLP model such as BERT on custom hardware such as EC2 [A1 instances](https://aws.amazon.com/ec2/instance-types/a1/) with the help of [TVM](https://tvm.ai/).

Agenda
------

| Time        | Title                                                         |
|-------------|---------------------------------------------------------------|
| 13:15-14:15 | Natural Language Processing and Deep Learning Basics          |
| 14:15-14:25 | Break                                                         |
| 14:25-15:15 | Word Embeddings and Applications of Basic Models              |
| 15:15-15:55 | Machine Translation and Sequence Generation                   |
| 15:55-16:35 | Contextual Representations with BERT                          |
| 16:35-16:45 | Break                                                         |
| 16:45-17:15 | Model Deployment with TVM                                     |

FAQ
---
- **Q: How do I get access to the notebooks from the tutorial?**
  - For setting it up on SageMaker notebook, you can find the instructions [here](./sagemaker_setup.md).
  - For setting up with Conda, you can use the following Conda environment files: [CPU](env/amlc19-cpu.yml) and [GPU](env/amlc19-gpu.yml). (See this [guide](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) on creating Conda environment from environment file.)
